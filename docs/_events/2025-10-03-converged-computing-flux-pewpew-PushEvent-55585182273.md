---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2025-10-03
repo_name: converged-computing/flux-pewpew
html_url: https://github.com/converged-computing/flux-pewpew/commit/7e6dd238e1f8c43ab10306d496026a3676d8d5c9
repo_url: https://github.com/converged-computing/flux-pewpew
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/converged-computing/flux-pewpew' target='_blank'>converged-computing/flux-pewpew</a>

<small>init: hello world

This was pretty fun. I do not know why the devcontainer seems to have
a default high match policy. It actually seems to select from the
highest set of cores, but then actually hand them out to the ranks
from the lowest to high. I suspect that fluxion returns the
high set and then flux hands them out still lowest first.
So for asking for 2 cores in 0-7, we first select 6-7, but
then assign 0:6 and 1:7

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/converged-computing/flux-pewpew/commit/7e6dd238e1f8c43ab10306d496026a3676d8d5c9' target='_blank'>View Commit</a>