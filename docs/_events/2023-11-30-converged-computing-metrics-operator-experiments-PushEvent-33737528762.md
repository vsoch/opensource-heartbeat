---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-11-30
repo_name: converged-computing/metrics-operator-experiments
html_url: https://github.com/converged-computing/metrics-operator-experiments/commit/b127259ea618a413bbdf380203f121035cb616d6
repo_url: https://github.com/converged-computing/metrics-operator-experiments
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/converged-computing/metrics-operator-experiments' target='_blank'>converged-computing/metrics-operator-experiments</a>

<small>add early experiment planning for spot

The spot_instances.py is refactored to include spot prices,
and we have an idea of the overall design. I next need to write
a test setup that will implement the features that I want, namely
using the metrics operator to run lammps, hwloc, and then pushing
to a remote oras cache (needs to be developed in the oras-operator)
and also using the aws locality / topology API to get metadata
for each group. Primarily I am interested in testing the different
sizes scoped in the README against problem sizes to better estimate
the total time and thus cost.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/converged-computing/metrics-operator-experiments/commit/b127259ea618a413bbdf380203f121035cb616d6' target='_blank'>View Commit</a>