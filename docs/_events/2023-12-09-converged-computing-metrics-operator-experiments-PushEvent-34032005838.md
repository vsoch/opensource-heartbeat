---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-12-09
repo_name: converged-computing/metrics-operator-experiments
html_url: https://github.com/converged-computing/metrics-operator-experiments/commit/74bc844a9a23599853fb82ede1853e5bd825394d
repo_url: https://github.com/converged-computing/metrics-operator-experiments
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/converged-computing/metrics-operator-experiments' target='_blank'>converged-computing/metrics-operator-experiments</a>

<small>Testing new algorithm: adjust bounds based on max cost/core then randomize (#4)

* testing new algorithm

instead of just choosing the first by index, this approach chooses
to remove the most instance size (decrement the max bound by one) for
the most expensive instance type. This means in practice we tend
to keep the cheaper ones (cost per core per hour) around and will
run out of solutions (e.g., around 17). Instead we could
also, when this happens, allow removing one at random. We will
likely need to allow for duplicate results in there, as we are
likely to iterate over the same bounds more than once.
Would be good to discuss this!

* allow for randomizing instead (I like this better)!

eyeballing the data, with the randomization, about 75% of the solutions sill use the cheapest core, but then 25% do not! That seems pretty good, and I think we can adjust things to tweak how we explore the space.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/converged-computing/metrics-operator-experiments/commit/74bc844a9a23599853fb82ede1853e5bd825394d' target='_blank'>View Commit</a>