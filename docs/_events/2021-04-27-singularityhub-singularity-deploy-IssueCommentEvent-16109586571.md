---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2021-04-27
repo_name: singularityhub/singularity-deploy
html_url: https://github.com/singularityhub/singularity-deploy/issues/4
repo_url: https://github.com/singularityhub/singularity-deploy
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/singularityhub/singularity-deploy/issues/4' target='_blank'>singularityhub/singularity-deploy#4</a>.

<small>One issue I'm thinking about is that, given that we use GitHub releases as tags, that means you can only associate one image with a release tag. It's probably akin to an issue we haven't addressed yet with architecture - there can be multiple digests for the same tag on Docker Hub or elsewhere for different architectures, and we currently just provide one. So if it's the case that one release == one container, and the release tag (e.g., 0.0.1) is associated with an exact (single) file that we could derive by way of parsing the release artifacts, I think this could work. But if we require multiple files per release tag, OR if the bot binoc cannot discover the name of the tag, then we have an issue. For shpc pull, the name of the binary in the release also needs to be predictable, so I am not sure doing something like a hash is an option....</small>

<a href='https://github.com/singularityhub/singularity-deploy/issues/4' target='_blank'>View Comment</a>