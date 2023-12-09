---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-12-08
repo_name: singularityhub/singularity-cli
html_url: https://github.com/singularityhub/singularity-cli/issues/213
repo_url: https://github.com/singularityhub/singularity-cli
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/singularityhub/singularity-cli/issues/213' target='_blank'>singularityhub/singularity-cli#213</a>.

<small>No worries! So `execute` is supposed to minic `singularity exec`. And `run_command` was previously a more hidden helper command to (one off) run a random command, but not inside the container (to the system).  I do think it would be more intuitive if this current `run_command` was an exec to the instance, and then the current was moved back to be a helper (hidden) function. I am happy to test this out and open another PR if you agree....</small>

<a href='https://github.com/singularityhub/singularity-cli/issues/213' target='_blank'>View Comment</a>