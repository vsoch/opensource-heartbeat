---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-04-05
repo_name: flux-framework/flux-k8s
html_url: https://github.com/flux-framework/flux-k8s/commit/8c99f108f80f2a6fcbf83dbab8e273e225cb6073
repo_url: https://github.com/flux-framework/flux-k8s
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/flux-framework/flux-k8s' target='_blank'>flux-framework/flux-k8s</a>

<small>test: only allow scheduling first pod

Problem: we currently allow any pod in the group to make the request
Solution: Making a BIG assumption that might be wrong, I am adding logic
that only allows scheduling (meaning going through PreFilter with AskFlux)
given that we see the first pod in the listing. In practice this is the first
index (e.g., index 0) which based on our sorting strategy (timestamp then name)
I think might work. But I am not 100% on that. The reason we want to do that is
so the nodes are chosen for the first pod, and then the group can quickly
follow and be actually assigned. Before I did this I kept seeing huge delays
in waiting for the queue to move (e.g., 5/6 pods Running and the last one
waiting, and then kicking in much later like an old car) and I think with
this tweak that is fixed. But this is my subjective evaluation. I am
also adding in the hack script for deploying to gke, which requires a
push instead of a kind load.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/flux-framework/flux-k8s/commit/8c99f108f80f2a6fcbf83dbab8e273e225cb6073' target='_blank'>View Commit</a>