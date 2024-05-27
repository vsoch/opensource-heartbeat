---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-05-26
repo_name: converged-computing/flux-usernetes
html_url: https://github.com/converged-computing/flux-usernetes/commit/148964081a9cda33658d0e43136ed17e7aba3ff3
repo_url: https://github.com/converged-computing/flux-usernetes
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/converged-computing/flux-usernetes' target='_blank'>converged-computing/flux-usernetes</a>

<small>fix: setting the cpu limit sets a cgroup bandwidth

Problem: setting the pod limits, although it still remains burstable,
actually does set a limit on the cgroup! We do not want to do that. When
we remove that, the CPU utilization goes up!

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/converged-computing/flux-usernetes/commit/148964081a9cda33658d0e43136ed17e7aba3ff3' target='_blank'>View Commit</a>