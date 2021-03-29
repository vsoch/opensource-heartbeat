---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2021-03-28
repo_name: singularityhub/singularity-compose
html_url: https://github.com/singularityhub/singularity-compose/issues/43
repo_url: https://github.com/singularityhub/singularity-compose
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/singularityhub/singularity-compose/issues/43' target='_blank'>singularityhub/singularity-compose#43</a>.

<small>`self.client.instance` is creating a new instance, it's called [here](https://github.com/singularityhub/singularity-cli/blob/d17ed1e1523b25824261d0aef3de9edb763f0803/spython/instance/__init__.py#L13) and it also calls start by default. It is not bypassing the start args - I tested the example that you provided me, and as I mentioned you need to bind the PWD to somewhere on your host to see the file, and it's simply not going to work if you don't have a startscript that accepts args. The startscript you showed above would need to be:...</small>

<a href='https://github.com/singularityhub/singularity-compose/issues/43' target='_blank'>View Comment</a>