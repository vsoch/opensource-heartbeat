---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-08-03
repo_name: converged-computing/fluxnetes
html_url: https://github.com/converged-computing/fluxnetes/commit/24ed8d2922f2435ff1386187829d19fa8b03ba97
repo_url: https://github.com/converged-computing/fluxnetes
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/converged-computing/fluxnetes' target='_blank'>converged-computing/fluxnetes</a>

<small>cleanup: basic functionality added (#13)

* cleanup: basic functionality added

This changeset adds support for a duration that drives cleanup,
meaning a duration in seconds can be provided as a label, and then
the label will be populated into the duration (seconds) to kickoff
a cleanup job after allocation. This currently is not doing a cleanup,
as we will need to walk up to a parent level abstraction (often deleting
the pod is not sufficient) and issue cancel to fluxion, but that will
come soon/next. I am also converting the fluxion service container build
to be multi-stage to hopefully make it smaller

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/converged-computing/fluxnetes/commit/24ed8d2922f2435ff1386187829d19fa8b03ba97' target='_blank'>View Commit</a>