---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-11-11
repo_name: snakemake/snakemake-interface-executor-plugins
html_url: https://github.com/snakemake/snakemake-interface-executor-plugins/issues/43
repo_url: https://github.com/snakemake/snakemake-interface-executor-plugins
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> open issue <a href='https://github.com/snakemake/snakemake-interface-executor-plugins/issues/43' target='_blank'>snakemake/snakemake-interface-executor-plugins#43</a>.

<p>Question: looking for means to run a final job step (that will be run locally)</p><small>I'm developing the kueue executor, and as a final step I either want to pull the final artifact from the registry, OR tell snakemake that we should not expect output locally (and then instruct the user to pull). I am not able to pull during the completion of the job step because as it is using asyncio I can't call portforward:...</small><a href='https://github.com/snakemake/snakemake-interface-executor-plugins/issues/43' target='_blank'>View Comment</a>