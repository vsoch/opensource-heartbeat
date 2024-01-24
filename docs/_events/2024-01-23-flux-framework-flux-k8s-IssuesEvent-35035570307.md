---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-01-23
repo_name: flux-framework/flux-k8s
html_url: https://github.com/flux-framework/flux-k8s/issues/60
repo_url: https://github.com/flux-framework/flux-k8s
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> open issue <a href='https://github.com/flux-framework/flux-k8s/issues/60' target='_blank'>flux-framework/flux-k8s#60</a>.

<p>When update go version: test pending</p><small>Newer versions of the go API have support for a [PENDING](https://github.com/kubernetes/kubernetes/blob/a07b1aaa5b39b351ec8586de800baa5715304a3f/pkg/scheduler/framework/interface.go#L130) state that would skip the backoff queue, and I think this might be helpful / useful. I did (stupidly) try it this weekend (updating library versions) and it led to like, 5 hours of debugging mysterious panics, so yeah, not something we should do soon/first with all the current debugging we still need to do! But I wanted to put a note because I saw it was added recently....</small><a href='https://github.com/flux-framework/flux-k8s/issues/60' target='_blank'>View Comment</a>