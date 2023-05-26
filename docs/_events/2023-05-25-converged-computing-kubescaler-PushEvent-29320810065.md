---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-05-25
repo_name: converged-computing/kubescaler
html_url: https://github.com/converged-computing/kubescaler/commit/e75b9a07229a1d1da7bf131f2953f3075ff927ef
repo_url: https://github.com/converged-computing/kubescaler
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/converged-computing/kubescaler' target='_blank'>converged-computing/kubescaler</a>

<small>wip to add AWS (#2)

* wip to add AWS
* add support for cluster deletion
* finish up scaling and example, a few bug fixes

the steps here will do a full creation of the cluster, which include
VPC, subnets (private and public), and security group, associating (and
creating if needed) a pem, getting the endpoint and certificate to make
a kube config yaml file to authenticate, and then another stack to
create the workers pool. This is interesting that AWS first creates you
an "empty" cluster, meaning just a control plane, and then you need
to create the workers as a separate request, and apply a config map
secret to the kube-system so the control plane can see the workers!
This is so much more complex than GKE, and now that I have everything
working to go UP I have to go backwards and figure out how to delete
everything before looking into scaling... hahahahahahah aahhhhh! :)

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/converged-computing/kubescaler/commit/e75b9a07229a1d1da7bf131f2953f3075ff927ef' target='_blank'>View Commit</a>