---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-07-26
repo_name: converged-computing/fluxnetes
html_url: https://github.com/converged-computing/fluxnetes/commit/8047000c5b740f267903269ec30e07c5901f5beb
repo_url: https://github.com/converged-computing/fluxnetes
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/converged-computing/fluxnetes' target='_blank'>converged-computing/fluxnetes</a>

<small>feat: new queue to handle groups

This changeset adds a new queue to the fluxnetes in-tree plugin,
which currently knows how to accept a pod for work, and then
just sleep (basically reschedule for 5 seconds into the future).
This is not currently hooked into Kubernetes scheduling because
I want to develop the functionality I need first, in parallel,
before splicing it in. I should still be able to schedule to
Fluxion and trigger cleanup when the actual job is done. I
think we might do better to remove the group CRD too - it would
hugely simplify things (the in-tree plugin would barely need
anything aside from the fluxion interactions and queue) and
instead we can keep track of group names and counts (that are
still growing) in a separate table, since we already have postgres.
Two things I am not sure about include 1. the extent to which
in-tree plugins support scheduling. I can either keep them (and
then would need to integrate) or have their functionality move
into what fluxion can offer. I suspect they add supplementary
features since we were able to disable most of them. The second
thing I am not sure about (I will figure out) is, given that
we customize the plugin framework, where the right place to
put sort is. If we are adding pods to a table we will need to
store the same metadata (priority, timestamp, etc) to allow
for this equivalent sort.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/converged-computing/fluxnetes/commit/8047000c5b740f267903269ec30e07c5901f5beb' target='_blank'>View Commit</a>