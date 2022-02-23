---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2022-02-23
repo_name: singularityhub/singularity-hpc
html_url: https://github.com/singularityhub/singularity-hpc/pull/496
repo_url: https://github.com/singularityhub/singularity-hpc
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/singularityhub/singularity-hpc/pull/496' target='_blank'>singularityhub/singularity-hpc#496</a>.

<small>> first of all, it would be good to add a couple of checks when parsing the value of settings.wrapper_subdir in SHPC, including removing leading/trailing slashes, and possibly only allowing one level of subdirectory (i.e bin is fine, but sub/bin to be made illegal). We should also disallow climbing back in the tree with .., which would mess up things across container versions and even repositories, and we might want to also disallow the current directory . , just to keep things tidy and easy. ...</small>

<a href='https://github.com/singularityhub/singularity-hpc/pull/496' target='_blank'>View Comment</a>