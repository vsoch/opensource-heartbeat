---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2022-10-04
repo_name: researchapps/flux-core
html_url: https://github.com/researchapps/flux-core/commit/f2d8cb2a5abdd27c49fa9a5a413f7ef0c63fac61
repo_url: https://github.com/researchapps/flux-core
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/researchapps/flux-core' target='_blank'>researchapps/flux-core</a>

<small>job-manager: integrate queue class with submit logic

Problem: jobs are accepted when submitted with a named queue when
queues are not configured.

Call queue_submit_check() on each submitted job.  The job is rejected
if a requested queue is not configured, or if the queue is disabled.

As part of the integration, the job-manager.submit-admin RPC is moved
temporarily to queue.c.  It will be removed once tools have been updated
to use the new RPCs.

Fixes #4440</small>

<a href='https://github.com/researchapps/flux-core/commit/f2d8cb2a5abdd27c49fa9a5a413f7ef0c63fac61' target='_blank'>View Commit</a>