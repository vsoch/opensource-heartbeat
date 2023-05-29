---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-05-29
repo_name: researchapps/flux-core
html_url: https://github.com/researchapps/flux-core/commit/0813efd2e481dc1095183476fef6168cf027d8a8
repo_url: https://github.com/researchapps/flux-core
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/researchapps/flux-core' target='_blank'>researchapps/flux-core</a>

<small>start of work to add prometheus plugin

Problem: we want to report metrics from flux to prometheus
Solution: write a plugin!

These early steps create the plugin skeleton, adding build
logic to enable the plugin given particular flags are present.
I next want to try installing this, adding the module load
to rc1, and seeing what happens. I think likely we want the
metrics to be updated from elsewhere (meaning the trigger for
an update) but not fully understanding how modules run
I am not sure yet.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/researchapps/flux-core/commit/0813efd2e481dc1095183476fef6168cf027d8a8' target='_blank'>View Commit</a>