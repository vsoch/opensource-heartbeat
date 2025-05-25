---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2025-05-24
repo_name: rootless-containers/usernetes
html_url: https://github.com/rootless-containers/usernetes/issues/373
repo_url: https://github.com/rootless-containers/usernetes
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> open issue <a href='https://github.com/rootless-containers/usernetes/issues/373' target='_blank'>rootless-containers/usernetes#373</a>.

<p>Infiniband for older kernel</p><small>We've been able to get Infiniband working with Usernetes, primarily using UCX and then having the devices `/dev/infiniband` bound from the host. We have a setup of usernetes on on-premises (our first on a production cluster and not in VMs alongside) and what I've found is the avenue to bind devices and then use ibverbs and ucx works up until the point it needs ulimit -l to be unlimited:...</small><a href='https://github.com/rootless-containers/usernetes/issues/373' target='_blank'>View Comment</a>