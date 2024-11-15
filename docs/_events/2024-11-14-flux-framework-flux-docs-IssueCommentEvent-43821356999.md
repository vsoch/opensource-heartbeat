---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-11-14
repo_name: flux-framework/flux-docs
html_url: https://github.com/flux-framework/flux-docs/issues/288
repo_url: https://github.com/flux-framework/flux-docs
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/flux-framework/flux-docs/issues/288' target='_blank'>flux-framework/flux-docs#288</a>.

<small>I might not have the best advice (and our flux devs will step in during work hours) but I would check `flux resource list` to see if you actually have two nodes. It could be that running `flux start` a la carte like that is just getting one node. So I might try an srun in the allocation for flux start that ensures the command goes across the nodes, e.g., here is what I'm doing in a development environment with slurm (and flux installed):...</small>

<a href='https://github.com/flux-framework/flux-docs/issues/288' target='_blank'>View Comment</a>