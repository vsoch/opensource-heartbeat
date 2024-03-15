---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-03-14
repo_name: flux-framework/flux-k8s
html_url: https://github.com/flux-framework/flux-k8s/commit/cbc66f701e1b38a4ec17060c4b5f856e984f727c
repo_url: https://github.com/flux-framework/flux-k8s
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/flux-framework/flux-k8s' target='_blank'>flux-framework/flux-k8s</a>

<small>update: adding back in fluence logic

Problem: fluence is missing!
Solution: add back fluence. This is a different design in that we do the asking
from the perspective of the pod group, meaning that we get back a full set of nodes,
and save them (assigned exactly) to specific pods. This could also be more lenient -
e.g., creating a cache of the list and then taking off the cache, but I like the
finer granularity of 1:1 mapping for future issues that might arise (where one
pod needs a new node). This design also introduces a nice feature that we can ask
for the resources (meaning creating a jobspec) for exactly what we need across pods
for the group because we are listing all pods for the group before we generate
the jobspec. I left it as it currently was before (using one representative pod)
to not incur too many changes but this definitely can be tried. There is likely
more work to be done to test edge cases and account for resources when fluence
starts (and be able to load a state if it restarts) but this is pretty great for
a first shot! The local lammps experiment ran without clogging and I am testing
on GKE as a next step. Finally, I think there is a lot of poetential error in
allowing a ton of other PreFilter plugins to exist, each of which could return
their own set of nodes to consider that might mismatch what fluence has decided
on. For this reason I have done aggressive pruning and we can add things back as
we see fit.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/flux-framework/flux-k8s/commit/cbc66f701e1b38a4ec17060c4b5f856e984f727c' target='_blank'>View Commit</a>