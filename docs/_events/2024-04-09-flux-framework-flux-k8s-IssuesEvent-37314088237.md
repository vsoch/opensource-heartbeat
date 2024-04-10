---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-04-09
repo_name: flux-framework/flux-k8s
html_url: https://github.com/flux-framework/flux-k8s/issues/73
repo_url: https://github.com/flux-framework/flux-k8s
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> open issue <a href='https://github.com/flux-framework/flux-k8s/issues/73' target='_blank'>flux-framework/flux-k8s#73</a>.

<p>Test using Active queue "Activate Siblings" vs Current approach</p><small>Coscheduling uses a strategy of moving siblings to the active Q when a pod that is about to hit a node hits the Permit endpoint. The strategy I have in place to schedule the first pod seems to be working OK, but I'd like to (after we merge the current PR) test this approach. I can see pros and cons to both ways - having to rely on another queue (subject to other issues) seems less ideal than having them all scheduled at the right time. On the other hand, if something might happen with the latter approach that warrants the active queue, maybe it makes sense. I think empirical testing can help us determine which strategy we like best (or even a combination of the two)....</small><a href='https://github.com/flux-framework/flux-k8s/issues/73' target='_blank'>View Comment</a>