---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2025-10-04
repo_name: vsoch/flux-sched
html_url: https://github.com/vsoch/flux-sched/commit/f6c598d65a5496320170386435e27e16c4e931ee
repo_url: https://github.com/vsoch/flux-sched
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/vsoch/flux-sched' target='_blank'>vsoch/flux-sched</a>

<small>feat: binding prediction

Problem: we need to be able to predict a binding, meaning a cpuset,
physical and logical cores (the PUs) based on a shape.
Solution: we can do this by parsing an existing xml or the
live system with hwloc, and then having an understanding of
the shape. A flux submit can then use hwloc to get the exact
cpuset mask, logical and physical cores, and of course numa
nodes, and we can compare what we *actually* get to the shape
we expect. Note that this DOES require that the shape provided
is what we actually get. This is probably something that both
flux developers and users should (and will) get a better
understanding of. E.g., that asking for exclusive allows exposure
to all resources under a NUMA node, or that setting cpu affinity
per task will limit to a subset of tasks (vs. not and having
different flux ranks with full access to all cores).

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/vsoch/flux-sched/commit/f6c598d65a5496320170386435e27e16c4e931ee' target='_blank'>View Commit</a>