---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-03-28
repo_name: flux-framework/flux-docs
html_url: https://github.com/flux-framework/flux-docs/pull/221
repo_url: https://github.com/flux-framework/flux-docs
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/flux-framework/flux-docs/pull/221' target='_blank'>flux-framework/flux-docs#221</a>.

<small>Yes you would need to basically run that command from a host or container with Flux. If you'd like to use a container, the .devcontainer Dockerfile https://github.com/flux-framework/flux-docs/blob/master/.devcontainer/Dockerfile should give you the right environment, and you'd want to build it and bind your working directory to `/workspace/flux-docs` (note that VSCode does this all for you!). Make sure you run the `flux start make html` inside the container in that root, and commit from the outside....</small>

<a href='https://github.com/flux-framework/flux-docs/pull/221' target='_blank'>View Comment</a>