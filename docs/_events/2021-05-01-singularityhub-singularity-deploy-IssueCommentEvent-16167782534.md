---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2021-05-01
repo_name: singularityhub/singularity-deploy
html_url: https://github.com/singularityhub/singularity-deploy/issues/4
repo_url: https://github.com/singularityhub/singularity-deploy
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/singularityhub/singularity-deploy/issues/4' target='_blank'>singularityhub/singularity-deploy#4</a>.

<small>That's very close! So binoc is tasked with updating the container.yaml files. This means that he parses them, and if a gh:// unique resource identifier is found, knows that the container in question needs to be updated from GitHub. So he then uses the release API to find new releases, and (before) since there would be a known set of tags (e.g., salad) that correspond to a file, he would update the container.yaml file with the new GitHub release for the tag, like:...</small>

<a href='https://github.com/singularityhub/singularity-deploy/issues/4' target='_blank'>View Comment</a>