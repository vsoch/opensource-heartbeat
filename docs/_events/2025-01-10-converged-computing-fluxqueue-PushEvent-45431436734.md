---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2025-01-10
repo_name: converged-computing/fluxqueue
html_url: https://github.com/converged-computing/fluxqueue/commit/f2193b4e1a9752d9230c6392ed812e256a564277
repo_url: https://github.com/converged-computing/fluxqueue
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/converged-computing/fluxqueue' target='_blank'>converged-computing/fluxqueue</a>

<small>scheduler and queue: start of work (#3)

* scheduler and queue: start of work

We need a very simple custom scheduler plugin to receive
and deploy (bind) node assignments, and we will do that
with the fluxqueue-scheduler I am adding here. The queue
will live alongside the controller and interact with
the fluxion service, and I have added the skeleton for that
(which needs a lot of work, but it is building so this
is a great start!

* wip: addition of queue logic

This is a WIP to save state of primarily the main.go/sum
because it is currently building, of course still needs a lot
of work on the code!

* queue: job pod is added to queue

Fluxion is also added and serving the cluster.

* fluxion submit is working!

We next need to unsuspend/ungate the pod to send to the
fluxion custom scheduler, and also implement logic to
react to different kubernetes events.

* feat: the full cycle to schedule a pod is working

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/converged-computing/fluxqueue/commit/f2193b4e1a9752d9230c6392ed812e256a564277' target='_blank'>View Commit</a>