---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-07-31
repo_name: kubernetes/kubernetes
html_url: https://github.com/kubernetes/kubernetes/issues/117758
repo_url: https://github.com/kubernetes/kubernetes
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/kubernetes/kubernetes/issues/117758' target='_blank'>kubernetes/kubernetes#117758</a>.

<small>I have a related use case (but I'm not sure it's exactly the same). For any service / worker setup, you'd often want the lead service to start up first, and be ready to receive the workers. We'd want to be able to say "start the workers when the lead broker is ready." However, this would be between ReplicatedJobs within a JobSet, and I'm not sure that is relevant to the issue here, which seems to be about an entire Job being ready (for a user interaction or similar)....</small>

<a href='https://github.com/kubernetes/kubernetes/issues/117758' target='_blank'>View Comment</a>