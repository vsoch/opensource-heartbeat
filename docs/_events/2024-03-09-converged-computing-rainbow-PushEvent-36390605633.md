---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-03-09
repo_name: converged-computing/rainbow
html_url: https://github.com/converged-computing/rainbow/commit/b505e8a8423452e9a8e5027f105d77fbb03cd6c4
repo_url: https://github.com/converged-computing/rainbow
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/converged-computing/rainbow' target='_blank'>converged-computing/rainbow</a>

<small>feat: add register -> nodes in graph endpoint

This adds the registration command for the subsystem, ensuring
that the subsystem root is created (e.g., for IO) and the cluster
name (e.g., IO for cluster keebler) created off of that. We currently
allow any vertex to be created with an edge to itself (within the
same subsystem) OR to a reference in the dominant subystem. We have
that reference birectional so if/when there is a delete command
we can parse the subsystem nodes (e.g., IO) to find the link to
the dominant subsystem node, and then clean it up from the other
side (and no dangling entries that no longer exist). Now that
this is added I can work on a prototype of intents (basically
a jobspec asking to request resources for this)

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/converged-computing/rainbow/commit/b505e8a8423452e9a8e5027f105d77fbb03cd6c4' target='_blank'>View Commit</a>