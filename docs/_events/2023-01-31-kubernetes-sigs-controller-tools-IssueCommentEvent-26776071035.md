---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-01-31
repo_name: kubernetes-sigs/controller-tools
html_url: https://github.com/kubernetes-sigs/controller-tools/issues/636
repo_url: https://github.com/kubernetes-sigs/controller-tools
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/kubernetes-sigs/controller-tools/issues/636' target='_blank'>kubernetes-sigs/controller-tools#636</a>.

<small>Yes! Sorry forgot to do so. For future readers, it was actually really important to use `IntOrString` because although my hack appeared to work, the variables in the CRD for that field (with the hack) were always null and it never took. Changing to `IntOrString` fixed the bug / the CRD worked. Thanks for your help here @JoelSpeed ! I can't speak for @armsnyder but it's good to close for me....</small>

<a href='https://github.com/kubernetes-sigs/controller-tools/issues/636' target='_blank'>View Comment</a>