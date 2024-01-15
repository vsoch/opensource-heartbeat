---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-01-14
repo_name: flux-framework/flux-operator
html_url: https://github.com/flux-framework/flux-operator/issues/214
repo_url: https://github.com/flux-framework/flux-operator
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> open issue <a href='https://github.com/flux-framework/flux-operator/issues/214' target='_blank'>flux-framework/flux-operator#214</a>.

<p>feature: suspendWorker boolean or retry count</p><small>We should have either a boolean or count for the user to decide how many times to retry worker pods. The use case is adding a new minSize that allows the minicluster to start with fewer workers. If the other workers eventually come up (and after the job is done) the pods might persist (and not complete) as they are retrying. We would want to avoid that....</small><a href='https://github.com/flux-framework/flux-operator/issues/214' target='_blank'>View Comment</a>