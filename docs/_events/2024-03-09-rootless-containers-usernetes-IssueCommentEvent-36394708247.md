---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-03-09
repo_name: rootless-containers/usernetes
html_url: https://github.com/rootless-containers/usernetes/issues/322
repo_url: https://github.com/rootless-containers/usernetes
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/rootless-containers/usernetes/issues/322' target='_blank'>rootless-containers/usernetes#322</a>.

<small>Ah, got it working! I will post the full update tomorrow - basically I needed to hack the daemonset a bit, and then add the correct annotations for it to bind to the pod (of the job). Then I could run a sleep job, shell in, install `fi_info` for libfabric, and see efa and run the tests....</small>

<a href='https://github.com/rootless-containers/usernetes/issues/322' target='_blank'>View Comment</a>