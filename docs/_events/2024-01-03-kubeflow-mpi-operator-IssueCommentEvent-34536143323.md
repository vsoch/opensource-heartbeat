---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-01-03
repo_name: kubeflow/mpi-operator
html_url: https://github.com/kubeflow/mpi-operator/issues/611
repo_url: https://github.com/kubeflow/mpi-operator
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/kubeflow/mpi-operator/issues/611' target='_blank'>kubeflow/mpi-operator#611</a>.

<small>This would be handled well by the flux operator, which uses zeromq to bootstrap and if a pod (follower broker) goes down flux would see the node as down, and we could schedule to another node (possibly newly added, which would join the cluster and then be seen as going from down to up). Nodes going up and down happens all the time in HPC so our workload managers are used to handling that, and for the flux operator you essentially get your own scheduler within the indexed job. We do, however, use a headless service and not the host file....</small>

<a href='https://github.com/kubeflow/mpi-operator/issues/611' target='_blank'>View Comment</a>