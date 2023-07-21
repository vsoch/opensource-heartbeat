---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-07-20
repo_name: rootless-containers/usernetes
html_url: https://github.com/rootless-containers/usernetes/issues/281
repo_url: https://github.com/rootless-containers/usernetes
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/rootless-containers/usernetes/issues/281' target='_blank'>rootless-containers/usernetes#281</a>.

<small>Tested again - it seems that the issue (aside from that "node" directory under the .configs and the typo in install.sh that there are missing quotes around `${publish}` is that unless I start crio/containerd on that same master node, the cluster doesn't hook up. The setup I created is here: https://github.com/converged-computing/flux-terraform-gcp/tree/usernetes/examples/usernetes and more specifically after doing a clone, copying the .config directory, I am following the logic here: https://github.com/converged-computing/flux-terraform-gcp/blob/usernetes/examples/usernetes/scripts/batch.sh. Note that the only reason the README logs seem to be working is because when I first ran them, I had the manually started all the different services on the master node (and then I saw it come up under `kubectl get nodes`. When I try to follow the logic / commands from the docker-compose, I see the various K8s objects created, but it hangs and times out on the last part. Starting the other two nodes (crio and containerd) akin to the docker-compose doesn't have obvious errors, but `kubectl get nodes` still doesn't work. And sometimes I see warnings:...</small>

<a href='https://github.com/rootless-containers/usernetes/issues/281' target='_blank'>View Comment</a>