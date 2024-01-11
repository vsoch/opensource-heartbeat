---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-01-10
repo_name: flux-framework/flux-operator
html_url: https://github.com/flux-framework/flux-operator/commit/c129246122f46214ffa2e2144c44e4bd677cd16d
repo_url: https://github.com/flux-framework/flux-operator
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/flux-framework/flux-operator' target='_blank'>flux-framework/flux-operator</a>

<small>ensure that worker exits with 0 so pod cleans up

If we do a flux drain <node> <reason> and then flux overlay disconnect <node>,
the broker should exit cleanly (meaning exit status 0) and then the pod will
also complete, and this means any autoscaler can clean it up too. No need for
us to issue a pod kill or similar command.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/flux-framework/flux-operator/commit/c129246122f46214ffa2e2144c44e4bd677cd16d' target='_blank'>View Commit</a>