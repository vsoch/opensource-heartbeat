---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-01-11
repo_name: singularityhub/singularity-hpc
html_url: https://github.com/singularityhub/singularity-hpc/issues/625
repo_url: https://github.com/singularityhub/singularity-hpc
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/singularityhub/singularity-hpc/issues/625' target='_blank'>singularityhub/singularity-hpc#625</a>.

<small>Thanks for opening this issue @surak - this is indeed a bug with the automation! We update the recipes in main with several ways, but the actual update of the docs, in that it runs on push to main, could not actually be triggered by another bot. So the solution is to add a nightly run (which would happen right after the manual run) and I've just triggered the update now for you. Try again - I just updated the docs and did a run so it should be the correct version now....</small>

<a href='https://github.com/singularityhub/singularity-hpc/issues/625' target='_blank'>View Comment</a>