---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-01-06
repo_name: converged-computing/kubescaler
html_url: https://github.com/converged-computing/kubescaler/issues/18
repo_url: https://github.com/converged-computing/kubescaler
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> open issue <a href='https://github.com/converged-computing/kubescaler/issues/18' target='_blank'>converged-computing/kubescaler#18</a>.

<p>Experiment with GKE scaler to add spot instance groups</p><small>I recently adopted the linear programming algorithm to calculate optimized instance groups for Google Cloud, and (superficially) it looks like we might have some promising combinations, meaning groups of spot instances that beat on demand prices. https://github.com/converged-computing/metrics-operator-experiments/tree/main/google/spot-instances/run0. To support this, we will need to do similar to what I added to AWS to create the cluster and then add on / delete managed node groups. GKE, unlike AWS, does not allow for an empty control plane, so I might need to create a cluster with one tiny node first, not sure because I haven't looked at this library in a while (but will soon)....</small><a href='https://github.com/converged-computing/kubescaler/issues/18' target='_blank'>View Comment</a>