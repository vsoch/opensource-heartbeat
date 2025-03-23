---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2025-03-22
repo_name: converged-computing/state-machine-operator
html_url: https://github.com/converged-computing/state-machine-operator/commit/bdc85aed9c4d37b37dd562f60c49fe03f1d6326c
repo_url: https://github.com/converged-computing/state-machine-operator
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/converged-computing/state-machine-operator' target='_blank'>converged-computing/state-machine-operator</a>

<small>feat: save kubernetes logs.

We have been saving artifacts for everything, relying on the
application to take the burden of saving its own logging
retrieved from the registry. For experiments with gpu
selection we just need one little value, and I think
it would be easier to save all the logs instead of
using oras. This feature supports that, where the
user adds a properties -> save-path, and under that
path "logs" is created that is named by the job,
step, and pod index.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/converged-computing/state-machine-operator/commit/bdc85aed9c4d37b37dd562f60c49fe03f1d6326c' target='_blank'>View Commit</a>