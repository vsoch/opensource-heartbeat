---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-10-16
repo_name: kubernetes-sigs/jobset
html_url: https://github.com/kubernetes-sigs/jobset/pull/244
repo_url: https://github.com/kubernetes-sigs/jobset
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/kubernetes-sigs/jobset/pull/244' target='_blank'>kubernetes-sigs/jobset#244</a>.

<small>ah I think I see! So we basically can define readiness gates, and the readiness gates are references to different probes. And a probe can be https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle/#container-probes anything from that set. And for the kind of probe we want readiness: https://kubernetes.io/docs/tasks/configure-pod-container/configure-liveness-readiness-startup-probes/#define-readiness-probes. Is that correct?...</small>

<a href='https://github.com/kubernetes-sigs/jobset/pull/244' target='_blank'>View Comment</a>