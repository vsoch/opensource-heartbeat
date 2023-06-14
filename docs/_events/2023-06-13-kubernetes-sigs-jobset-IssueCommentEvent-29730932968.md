---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-06-13
repo_name: kubernetes-sigs/jobset
html_url: https://github.com/kubernetes-sigs/jobset/pull/171
repo_url: https://github.com/kubernetes-sigs/jobset
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/kubernetes-sigs/jobset/pull/171' target='_blank'>kubernetes-sigs/jobset#171</a>.

<small>@ahg-g I want to push back a bit on this design of having it in the webhook - I don't like it. It's added complexity to the testing, and I think it would be more reliable to not rely on the webhook but rather place the single source of truth for setting this in the controller. ...</small>

<a href='https://github.com/kubernetes-sigs/jobset/pull/171' target='_blank'>View Comment</a>