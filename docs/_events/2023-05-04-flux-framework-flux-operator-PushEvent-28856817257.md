---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-05-04
repo_name: flux-framework/flux-operator
html_url: https://github.com/flux-framework/flux-operator/commit/72aac4d3900b37589777cfc107bcac3bf5a5b927
repo_url: https://github.com/flux-framework/flux-operator
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/flux-framework/flux-operator' target='_blank'>flux-framework/flux-operator</a>

<small>Add/tbon connect timeout test (#162)

* adding tbon connect timeout
* re-organize log level and option flags too

This will resolve an issue that zeromq by default
has a timeout on retry with exponential backoff. Although
there is still a remaining issue in Kubernetes that adding
a service pod seems to improve network readiness, for now
this addition of the zeromq timeout will reduce the startup
times from grossly large to acceptably so.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/flux-framework/flux-operator/commit/72aac4d3900b37589777cfc107bcac3bf5a5b927' target='_blank'>View Commit</a>