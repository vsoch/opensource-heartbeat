---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-04-01
repo_name: converged-computing/rainbow-experiments
html_url: https://github.com/converged-computing/rainbow-experiments/commit/6252dc20e8742b479c89820699ce55f206e5cee0
repo_url: https://github.com/converged-computing/rainbow-experiments
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/converged-computing/rainbow-experiments' target='_blank'>converged-computing/rainbow-experiments</a>

<small>Add reliabuild version range experiments (#1)

* wip: running reliabuild experiments

Signed-off-by: vsoch <vsoch@users.noreply.github.com>

* refactor: match based on versions

Signed-off-by: vsoch <vsoch@users.noreply.github.com>

* wip: refactored reliabuild experiments

This experiment has become primarily about the build use case,
and specifically package versions as the compatibility metadata.
Since we cannot generate every perfect cluster, I think the result
is going to be an example of how adding too much (in terms of
requirements) leads to a poorer outcomes. Of course it is entirely
based on the number of clusters I made, etc. I currently have only
100 clusters for about 10K jobs and over 200 dependency metadata
(of course not every one is relevant for every package) so the odds
of getting a matching cluster are pretty slim when you start asking
for more detail. Hopefully folks can help to think of smarter
experiments too.

Signed-off-by: vsoch <vsoch@users.noreply.github.com>

* results: add raw files in case I do something stupid

Signed-off-by: vsoch <vsoch@users.noreply.github.com>

* add results

Signed-off-by: vsoch <vsoch@users.noreply.github.com>

---------

Signed-off-by: vsoch <vsoch@users.noreply.github.com>
Co-authored-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/converged-computing/rainbow-experiments/commit/6252dc20e8742b479c89820699ce55f206e5cee0' target='_blank'>View Commit</a>