---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-12-18
repo_name: flux-framework/flux-k8s
html_url: https://github.com/flux-framework/flux-k8s/commit/e96e8664d5973bae112756cbf7d340fa398b3370
repo_url: https://github.com/flux-framework/flux-k8s
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/flux-framework/flux-k8s' target='_blank'>flux-framework/flux-k8s</a>

<small>ci: add automated and on demand testing of fluence

Problem: we cannot tell if/when fluence builds will break against upstream
Solution: have a weekly run that will build and test images, and deploy on
successful results. For testing, I have added a complete example that uses
Job for fluence/default-scheduler, and the reason is because we can run
a container that generates output, have it complete, and there is no crash
loop backoff or similar. I have added a complete testing setup using kind,
and it is in one GitHub job so we can build both containers and load into
kind, and then run the tests. Note that MiniKube does NOT appear to work
for custom schedulers - I suspect there are extensions/plugins that need
to be added. Finally, I was able to figure out how to programmatically
check both the pod metadata for the scheduler along with events, and
that combined with the output should be sufficient (for now) to test
that fluence is working.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/flux-framework/flux-k8s/commit/e96e8664d5973bae112756cbf7d340fa398b3370' target='_blank'>View Commit</a>