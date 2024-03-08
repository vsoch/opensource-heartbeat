---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-03-07
repo_name: flux-framework/flux-k8s
html_url: https://github.com/flux-framework/flux-k8s/commit/a250385d21c8d0e0744d0ff1f9bb994c22df2f94
repo_url: https://github.com/flux-framework/flux-k8s
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/flux-framework/flux-k8s' target='_blank'>flux-framework/flux-k8s</a>

<small>refactor: testing idea to wrap coscheduling

This is the "skeleton" of a new idea to wrap coscheduling, adding
in the logic for fluence only where it is needed, likely in
the PodGroup (in the new fluence/core/core that wraps the same
in coscheduling). This is just a skeleton because we are deploying
the sidecar with the wrapped scheduling and absolutely no logic
ported over to AskFlux. I think I have a sense of where to put
this, but wanted to save this vanilla/skeleton state in case
we need to go back to it. Note that it did not work to have
fluence inherit the functions from coscheduler, so I opted for
a strategy of adding it as a helper field, and then just
using it when necessary.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/flux-framework/flux-k8s/commit/a250385d21c8d0e0744d0ff1f9bb994c22df2f94' target='_blank'>View Commit</a>