---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2022-03-15
repo_name: snakemake/snakemake
html_url: https://github.com/snakemake/snakemake/issues/1485
repo_url: https://github.com/snakemake/snakemake
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/snakemake/snakemake/issues/1485' target='_blank'>snakemake/snakemake#1485</a>.

<small>oh that's a good idea! So the way we save logs is actually to add an extra step to the job, and that's done [here](https://github.com/snakemake/snakemake/blob/013a6e8459d0659e05546c849f84151860686004/snakemake/executors/google_lifesciences.py#L731). You'll notice that is actually running this [helper script]() and the "logs" subcommand with the logs folder and job name as the last part, e.g.,:...</small>

<a href='https://github.com/snakemake/snakemake/issues/1485' target='_blank'>View Comment</a>