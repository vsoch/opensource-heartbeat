---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-08-02
repo_name: kubeflow/training-operator
html_url: https://github.com/kubeflow/training-operator/pull/2171
repo_url: https://github.com/kubeflow/training-operator
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/kubeflow/training-operator/pull/2171' target='_blank'>kubeflow/training-operator#2171</a>.

<small>One last question - any reason to differentiate `schedulerName` and `GangScheduler` ? Can we not just call them the same thing? To use a gang scheduler you should still use `schedulerName`. If we use the same term in both places we can simplify the abstractions we describe, and not limit the scope of what the type means for the future (in case a different term or kind of scheduler arises appropriate to be used as a plugin here)....</small>

<a href='https://github.com/kubeflow/training-operator/pull/2171' target='_blank'>View Comment</a>