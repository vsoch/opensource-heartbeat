---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-04-12
repo_name: researchapps/flux-sched
html_url: https://github.com/researchapps/flux-sched/commit/ae71d07da3a27bf5c87da0fd8f9d1cfbdfc8f718
repo_url: https://github.com/researchapps/flux-sched
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/researchapps/flux-sched' target='_blank'>researchapps/flux-sched</a>

<small>fix: convert strings to boost:flyweight

Problem: string comparison is immensely inefficient, taking 6-10%
of resources (reported by Tom) for a trace.
Solution: start with the root of the issue in the scoring
module and work backwards to convert string types to boost::
flyweight. I tried to have a minimal footprint here but it
spread really quickly

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/researchapps/flux-sched/commit/ae71d07da3a27bf5c87da0fd8f9d1cfbdfc8f718' target='_blank'>View Commit</a>