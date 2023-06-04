---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-06-03
repo_name: flux-framework/flux-operator
html_url: https://github.com/flux-framework/flux-operator/commit/e495c668b4a47d9a59c37677fed0bbd3ff78efa6
repo_url: https://github.com/flux-framework/flux-operator
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/flux-framework/flux-operator' target='_blank'>flux-framework/flux-operator</a>

<small>cleanup client commands (#179)

the design I have seen  more often is to use the controller client directly
on the reconciler. We cannot do that directly for Create since we have
events (that require then name) but we can wrap the command and use r.New
instead (and all others, r.Patch, r.Status, R.Get appear to work).

Signed-off-by: vsoch <vsoch@users.noreply.github.com>
Co-authored-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/flux-framework/flux-operator/commit/e495c668b4a47d9a59c37677fed0bbd3ff78efa6' target='_blank'>View Commit</a>