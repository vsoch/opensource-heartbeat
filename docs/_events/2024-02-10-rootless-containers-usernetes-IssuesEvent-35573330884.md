---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-02-10
repo_name: rootless-containers/usernetes
html_url: https://github.com/rootless-containers/usernetes/issues/321
repo_url: https://github.com/rootless-containers/usernetes
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> closed issue <a href='https://github.com/rootless-containers/usernetes/issues/321' target='_blank'>rootless-containers/usernetes#321</a>.

<p>Testing on ARM</p><small>I'm building a node for arm, and I noticed the Dockerfile is hard coded to a sha, which I would suspect is for AMD64. I am wondering if it would make sense to remove the sha pin and allow for the platform to be selected instead? What I'm doing now is trying out an arm sha and can report back. It does look like the rest of the Dockerfile is going to account for arm (e.g., CNI plugins). I suspect there might be more issues though....</small><a href='https://github.com/rootless-containers/usernetes/issues/321' target='_blank'>View Comment</a>