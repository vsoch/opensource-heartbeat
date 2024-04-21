---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-04-20
repo_name: researchapps/flux-sched
html_url: https://github.com/researchapps/flux-sched/commit/c9fb2bf54a6e8d514359863d641a97fa66da20bf
repo_url: https://github.com/researchapps/flux-sched
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/researchapps/flux-sched' target='_blank'>researchapps/flux-sched</a>

<small>reapi c++: add satisfy endpoint

Problem: the c++ bindings do not have satisfy support.
Solution: add satisfy to them.

In practice I was adding this for exposure to the Go
bindings, but I do not think it is necessary, because
the Go bindings use the C bindings, which already have
reapi_cli_match_satisfy. I saw that match_allocate
seems to have support to provide the SATISFIABILITY
match_op, which is provided to the traverser, so I
tried to call that same function. I am opening this
PR in case it is interesting or useful. If not,
please close and disregard.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/researchapps/flux-sched/commit/c9fb2bf54a6e8d514359863d641a97fa66da20bf' target='_blank'>View Commit</a>