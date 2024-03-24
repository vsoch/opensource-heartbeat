---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-03-24
repo_name: converged-computing/ensemble-operator
html_url: https://github.com/converged-computing/ensemble-operator/commit/c91ec664b775b59a325a8968f95c24487ae7855c
repo_url: https://github.com/converged-computing/ensemble-operator
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/converged-computing/ensemble-operator' target='_blank'>converged-computing/ensemble-operator</a>

<small>wip: add workload demand

This is the starting setup for our first algorithm! Right
now, we are defining jobs in the CRD, and the minicluster is
made interactive so we do not need to worry about adding random
sleeps or waits, etc. We also have validation and member type
support for each algorithm (starting just with minicluster). Where
I am at now is that we are instantiating the workload-demand algorithm
(it is an interface) and it is receiving input from the gRPC sidecar, and
then in the "MakeDecision" function we have our jobs spec (from the CRD)
and queue status. Next (after my run) I am going to work on this interaction!
We will want the algorithm to prepare a response payload that directs the
gRPC service to run all the lammps jobs, and then on the operator side
we will update the jobs spec to indicate they are run (decrementing the count)
and on the next iteration check the queue status again for size, etc and
adjust as needed. This is still early but very cool so far.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/converged-computing/ensemble-operator/commit/c91ec664b775b59a325a8968f95c24487ae7855c' target='_blank'>View Commit</a>