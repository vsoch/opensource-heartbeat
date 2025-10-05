---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2025-10-04
repo_name: vsoch/flux-sched
html_url: https://github.com/vsoch/flux-sched/commit/a49e9cc3de354ad1752ca94e386bf57145c0c376
repo_url: https://github.com/vsoch/flux-sched
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/vsoch/flux-sched' target='_blank'>vsoch/flux-sched</a>

<small>test: exclusivity check

Problem: we need to be able to check that a change to fluxion does not
change cpu mapping decisions. This is a WIP set of changes that will
discovery the local resources with hwloc, and then submit simple
jobs and compare the discovered mapping with expected, where expected
is a consistent pattern we can derive. The identifiers of the cpusets
should hypothetically not matter as long as the patterns are consistent.
Finally, I tested using faux or emulated resources, and everything works
up until when we need to get the cpusets via the pid. I was not able to
get a pid that makes sense. That said, it will be worth one more try
before giving up!

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/vsoch/flux-sched/commit/a49e9cc3de354ad1752ca94e386bf57145c0c376' target='_blank'>View Commit</a>