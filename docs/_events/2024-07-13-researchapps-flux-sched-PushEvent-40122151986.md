---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-07-13
repo_name: researchapps/flux-sched
html_url: https://github.com/researchapps/flux-sched/commit/8d6e187b5856ecfc6c14cf3864b61fc7c825451d
repo_url: https://github.com/researchapps/flux-sched
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/researchapps/flux-sched' target='_blank'>researchapps/flux-sched</a>

<small>chore: flux ion-resource jobspec argument redundancy

Problem: the flux-ion-resource.py match has several subcommands
that require a jobspec positional argument. Each subparser is
calling the same logic to add it, which is redundant.
Solution: iterate through a list to add the same argument
to all of them, eliminating the redundancy and making it easier
for the developer to read.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/researchapps/flux-sched/commit/8d6e187b5856ecfc6c14cf3864b61fc7c825451d' target='_blank'>View Commit</a>