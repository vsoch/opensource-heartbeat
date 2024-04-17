---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-04-16
repo_name: researchapps/flux-sched
html_url: https://github.com/researchapps/flux-sched/commit/bc3053092aa6304d7714f7ccd57109b1c87b3e62
repo_url: https://github.com/researchapps/flux-sched
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/researchapps/flux-sched' target='_blank'>researchapps/flux-sched</a>

<small>qmanager: Preserve reservations across sched-loop iterations

Problem: Currently we remove all of the temporary
reservations created in sched-fluxion-resource to
backfill jobs. This has a side effect in that we can't
use that information as start-time estimates for
pending jobs.

Preserve those temporary reservations across
two consecutive schedule loop iterations.</small>

<a href='https://github.com/researchapps/flux-sched/commit/bc3053092aa6304d7714f7ccd57109b1c87b3e62' target='_blank'>View Commit</a>