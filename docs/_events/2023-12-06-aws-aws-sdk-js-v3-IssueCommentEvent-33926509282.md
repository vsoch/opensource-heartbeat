---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-12-06
repo_name: aws/aws-sdk-js-v3
html_url: https://github.com/aws/aws-sdk-js-v3/issues/4495
repo_url: https://github.com/aws/aws-sdk-js-v3
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/aws/aws-sdk-js-v3/issues/4495' target='_blank'>aws/aws-sdk-js-v3#4495</a>.

<small>I think this might be an underlying waiters problem (as opposed to a particular JDK). For the Python SDK, it will work for a while, and then entirely stop working, to the point that the waiters just wait forever (and given the `nodegroup_active` waiter) I can easily use the kubeconfig.yaml and kubetl to see the nodegroup has been ready for 10-20 minutes, but the waiter is... still waiting....</small>

<a href='https://github.com/aws/aws-sdk-js-v3/issues/4495' target='_blank'>View Comment</a>