---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-05-19
repo_name: kubernetes/kubernetes
html_url: https://github.com/kubernetes/kubernetes/issues/117819
repo_url: https://github.com/kubernetes/kubernetes
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/kubernetes/kubernetes/issues/117819' target='_blank'>kubernetes/kubernetes#117819</a>.

<small>okay added [instructions](https://github.com/converged-computing/operator-experiments/tree/add/bare-metal-experiment-setup/google/service-timing/run10#scripted-runs) and the [script](https://github.com/converged-computing/operator-experiments/blob/add/bare-metal-experiment-setup/google/service-timing/run10/time-minicluster-lammps.py) that mirrors what I was doing.  This also loops over zeromq timeouts - let me know if you want me to remove that and just use the default. That will save a tagged output directory (name of your choice) under a local "data" directory and automate everything. You create the cluster / install the operator as before, but then just run the script. Let me know if you have questions or there are any issues - I'd usually test this in full before sharing but it's quite a chonky cluster I'd need to bring up so I didn't this time!...</small>

<a href='https://github.com/kubernetes/kubernetes/issues/117819' target='_blank'>View Comment</a>