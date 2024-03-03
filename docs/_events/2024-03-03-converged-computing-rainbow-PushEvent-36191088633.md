---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-03-03
repo_name: converged-computing/rainbow
html_url: https://github.com/converged-computing/rainbow/commit/0832df10c531c911b1212734cada3afb24a57052
repo_url: https://github.com/converged-computing/rainbow
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/converged-computing/rainbow' target='_blank'>converged-computing/rainbow</a>

<small>feat: add support for assignment table

When the graph database returns clusters that satisfy a jobspec, they need to be redirected
to the rainbow cluster to be assigned. This is a two step process, where first we add
the jobid to the jobs table (and it is not assigned) and then we will add it to an assignment
table with each cluster id that can receive it. At this point we are going to ask the clusters
if they can satisfy (and when) to assign it, and I do think we need a push model for the assignment.
We will need to allow for failure to connect (and retry) and some kind of heartbeat to do that,
but I first need to think about how a cluster can have work pushed to it - likely we need a
special client running there that I have not written yet

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/converged-computing/rainbow/commit/0832df10c531c911b1212734cada3afb24a57052' target='_blank'>View Commit</a>