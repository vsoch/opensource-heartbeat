---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-10-22
repo_name: flux-framework/flux-core
html_url: https://github.com/flux-framework/flux-core/issues/4569
repo_url: https://github.com/flux-framework/flux-core
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/flux-framework/flux-core/issues/4569' target='_blank'>flux-framework/flux-core#4569</a>.

<small>Adding a note here (and apologies if I missed a detail, there is a lot in this thread!) but I'd like to be able to add arbitrary events that are rpc (not necessarily just the job journal) to be triggered with handle.reactor_run() and then allow me to trigger a callback. For example, for a custom heartbeat, I can subscribe to it and receive the message, but I have to do that synchronously and do some loop that blocks (and prevents me from running my one call to the reactor). My solution now is not to use flux and create a separate thread, but I'd ideally like everything (events wise) coming from one source, and from flux....</small>

<a href='https://github.com/flux-framework/flux-core/issues/4569' target='_blank'>View Comment</a>