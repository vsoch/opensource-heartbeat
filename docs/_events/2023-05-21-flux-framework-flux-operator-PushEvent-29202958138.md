---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-05-21
repo_name: flux-framework/flux-operator
html_url: https://github.com/flux-framework/flux-operator/commit/69dae3936240a73b4a084a764c003b39a6b10100
repo_url: https://github.com/flux-framework/flux-operator
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/flux-framework/flux-operator' target='_blank'>flux-framework/flux-operator</a>

<small>unique label for hpa selector (#175)

we are currently using the headless service label,
which is not ideal because we would include the pod
for a sidecar service! This update will use a separate
hpa-selector label instead, which will only select for
the pods within the indexed job of the named minicluster

Signed-off-by: vsoch <vsoch@users.noreply.github.com>
Co-authored-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/flux-framework/flux-operator/commit/69dae3936240a73b4a084a764c003b39a6b10100' target='_blank'>View Commit</a>