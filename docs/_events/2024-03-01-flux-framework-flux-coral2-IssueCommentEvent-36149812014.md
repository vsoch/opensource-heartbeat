---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-03-01
repo_name: flux-framework/flux-coral2
html_url: https://github.com/flux-framework/flux-coral2/issues/131
repo_url: https://github.com/flux-framework/flux-coral2
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/flux-framework/flux-coral2/issues/131' target='_blank'>flux-framework/flux-coral2#131</a>.

<small>@jameshcorbett I was thinking in the context of a jobspec that is able to request storage - it sounds like if the request is too small we would run into trouble, and maybe not every cluster has a behind the scenes solution to set a minimum in that case. So when we check to see if a jobspec can be satisfied (and is valid) we need to ensure it's not too small. And maybe if it is, and it's a global truth (meaning it would be too small for any cluster) we could tweak the jobspec on our own, kind of like a mutating ...</small>

<a href='https://github.com/flux-framework/flux-coral2/issues/131' target='_blank'>View Comment</a>