---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-10-21
repo_name: converged-computing/ensemble-python
html_url: https://github.com/converged-computing/ensemble-python/commit/82b92fb3aa37132eb4e1aa76057e9d1cf4fc9bd4
repo_url: https://github.com/converged-computing/ensemble-python
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/converged-computing/ensemble-python' target='_blank'>converged-computing/ensemble-python</a>

<small>feat: grow/shrink requests are being hit

I need to put this into the ensemble operator next to have the request
actually do something, like request the minicluster to scale up or
down. I will also need to have a way to communicate the member name
and namespace. This could either be done via discovery (requiring the
kubernetes API within the ensemble python and the rbac to use it),
or more simply done, just put the member name that is expected in
the same namespace. More ideally there can be a registration step at
the onset that generates a random name and sends it over to the grpc
service to associate.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/converged-computing/ensemble-python/commit/82b92fb3aa37132eb4e1aa76057e9d1cf4fc9bd4' target='_blank'>View Commit</a>