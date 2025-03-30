---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2025-03-29
repo_name: converged-computing/state-machine-operator
html_url: https://github.com/converged-computing/state-machine-operator/commit/448655e0898ae2f67619ed67c2513df2723fe177
repo_url: https://github.com/converged-computing/state-machine-operator
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/converged-computing/state-machine-operator' target='_blank'>converged-computing/state-machine-operator</a>

<small>wip: add support for workflow events (#27)

* wip: add support for workflow events

This will add support for ending the workflow early due
to a count of successes, failures, or job duration metric.
We need to next add ability to grow or shrink (need to think
about how to do that, since we want a cloud agnostic solution)
and then how to handle application specific metrics

Signed-off-by: vsoch <vsoch@users.noreply.github.com>

* feat: add support for minicluster

If we really want to test scale (shrink and grow) of a job
and have it work with the cluster autoscaler, plus collecting
metrics from an HPC app, we can most easily do that with
the flux operator. This feature adds support for specifying
a minicluster property to convert the previous indexed job
into a MiniCluster. The flux operator needs to be installed.

Signed-off-by: vsoch <vsoch@users.noreply.github.com>

* feat: shrink with flux minicluster example working.

Signed-off-by: vsoch <vsoch@users.noreply.github.com>

* save state

Signed-off-by: vsoch <vsoch@users.noreply.github.com>

* feat: support for custom metrics

In this example, the user is allowed to provide a custom script
that will be used against the log, and it needs to return a dictionary
of values (the custom metrics). These are passed back to the manager
from the state machine step and can influence workflow behavior (e.g.,
stop early, grow, or shrink.

Signed-off-by: vsoch <vsoch@users.noreply.github.com>

---------

Signed-off-by: vsoch <vsoch@users.noreply.github.com>
Co-authored-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/converged-computing/state-machine-operator/commit/448655e0898ae2f67619ed67c2513df2723fe177' target='_blank'>View Commit</a>