---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-09-06
repo_name: converged-computing/metrics-operator
html_url: https://github.com/converged-computing/metrics-operator/commit/437c42e4bf52cda900e81166f8979641350570f2
repo_url: https://github.com/converged-computing/metrics-operator
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/converged-computing/metrics-operator' target='_blank'>converged-computing/metrics-operator</a>

<small>add new design for perf metric (#55)

in this application design, we create an empty volume to
be shared by two containers in a pod. One container (with
a modular install of software) can move it along with
any other needed assets to the shared volume, and then
customize the application entrypoint to move the volume
assets where they might need to be and wait for files
to be present.

Signed-off-by: vsoch <vsoch@users.noreply.github.com>
Co-authored-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/converged-computing/metrics-operator/commit/437c42e4bf52cda900e81166f8979641350570f2' target='_blank'>View Commit</a>