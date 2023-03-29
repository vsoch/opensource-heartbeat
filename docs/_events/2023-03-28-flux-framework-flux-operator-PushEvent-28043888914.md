---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-03-28
repo_name: flux-framework/flux-operator
html_url: https://github.com/flux-framework/flux-operator/commit/90427f406d7ef0dc2de94f41519d02e525a506ac
repo_url: https://github.com/flux-framework/flux-operator
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/flux-framework/flux-operator' target='_blank'>flux-framework/flux-operator</a>

<small>support for single services to run alongside minicluster (#132)

* support for single services

If we want to run a singularity container on all nodes of the cluster, we either
need to provision volumes (harder) or pull the container to each node. The latter,
of course, is a really bad idea - we do not want to strain networking to the outside
internet or a registry! A solution is to implement a single service, not a sidecar
in that the service runs alongside each pod (N times) but rather a single service for
the entire cluster. In this case we create a registry, and then we can (once) pull the
container with ORAS to a Singularity image, and then also use oras to push to the OIC
oops OCI compatible registry. Then all the nodes can pull that same container from our
local registry to their systems. In a way it is acting as a pull through cache!

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/flux-framework/flux-operator/commit/90427f406d7ef0dc2de94f41519d02e525a506ac' target='_blank'>View Commit</a>