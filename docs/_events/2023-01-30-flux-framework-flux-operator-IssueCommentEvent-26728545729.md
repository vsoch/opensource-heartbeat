---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-01-30
repo_name: flux-framework/flux-operator
html_url: https://github.com/flux-framework/flux-operator/issues/35
repo_url: https://github.com/flux-framework/flux-operator
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/flux-framework/flux-operator/issues/35' target='_blank'>flux-framework/flux-operator#35</a>.

<small>This is fixed - we've now run experiments with 64 nodes and having the pods come up in random order with respect to the broker. The strategy we use is to put the command for the worker to start in a loop (with some sleep) so when the broker is up it will eventually connect, and then it can exit when the broker finishes running the job....</small>

<a href='https://github.com/flux-framework/flux-operator/issues/35' target='_blank'>View Comment</a>