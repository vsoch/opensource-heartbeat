---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-07-06
repo_name: converged-computing/kubescaler
html_url: https://github.com/converged-computing/kubescaler/commit/c1008e6a1a6c5c18549bed940644606c671f96f5
repo_url: https://github.com/converged-computing/kubescaler
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/converged-computing/kubescaler' target='_blank'>converged-computing/kubescaler</a>

<small>testing updated algorithm for scaling (#9)

* testing updated algorithm for scaling
* node count must only be LESS THAN max size, not equal to

We currently will go too big because the assumption is scaling
by just 1, so we need to update our scaling functions (now renamed
to increase_by and decrease_by to indicate returning an actual value)
to return the value to actually increment/change by, and then do it.
This is a WIP for testing.

Additional note - AWS seems to count the instances it is removing
with those new creating, so we will eventually need to add some wiggle
room.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/converged-computing/kubescaler/commit/c1008e6a1a6c5c18549bed940644606c671f96f5' target='_blank'>View Commit</a>