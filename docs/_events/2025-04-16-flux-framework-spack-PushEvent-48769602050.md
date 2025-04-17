---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2025-04-16
repo_name: flux-framework/spack
html_url: https://github.com/flux-framework/spack/commit/21e369fc163e5ec1657994651064b8c184a9f217
repo_url: https://github.com/flux-framework/spack
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/flux-framework/spack' target='_blank'>flux-framework/spack</a>

<small>flux-sched: build older flux-core

flux sched 0.38 was the first that required gcc
version 12 or higher, and flux-core continued to
build for some time, but eventually added
features that we are now seeing break with
sched 0.37 and the latest flux. This conflicts
should ensure that older flux-sched, which
is being built by having an older compiler,
only builds with flux-core up to 0.68.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/flux-framework/spack/commit/21e369fc163e5ec1657994651064b8c184a9f217' target='_blank'>View Commit</a>