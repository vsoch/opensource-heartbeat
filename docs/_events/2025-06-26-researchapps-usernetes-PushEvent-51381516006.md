---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2025-06-26
repo_name: researchapps/usernetes
html_url: https://github.com/researchapps/usernetes/commit/3c8880333c99483f7e61eca8b19786cf2e5187ea
repo_url: https://github.com/researchapps/usernetes
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/researchapps/usernetes' target='_blank'>researchapps/usernetes</a>

<small>docs: note on order of starting components

flannel requires an annotation to use a host external ip for a multi-node setup. If the ip addresses that are in the private space can be routed between nodes (possible in some clouds) this is not an issue. It is only an issue in an HPC or similar environment where the private 10.x address might go to a router and not be understood (and dropped). We ran into this issue on our HPC system, and I realized it was because of the order
of operations - we should make sync-external-ip first (adding the annotation) and then make install-flannel to use it. This would only be a bug for specific, multi-node environments.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/researchapps/usernetes/commit/3c8880333c99483f7e61eca8b19786cf2e5187ea' target='_blank'>View Commit</a>