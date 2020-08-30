---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2020-08-29
repo_name: snakemake/snakemake
html_url: https://github.com/snakemake/snakemake/issues/457
repo_url: https://github.com/snakemake/snakemake
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/snakemake/snakemake/issues/457' target='_blank'>snakemake/snakemake#457</a>.

<small>I think I remember discussing this with @johanneskoester and @moschetti and we decided against it (or it could have been a different method toward the same goal?) and I can't remember the details now! So @aryam7 you are suggesting that we would need to still upload these inputs to storage on the first go, but then create a filesystem, add the files to it, and then mount the filesystem to all steps and clean up at the end? This feels like overkill since we can just upload once and then access from storage. I do see your point about the redundancy, and I'm concerned that creating this extra step would require making another instance just to populate files, and then waiting for that....</small>

<a href='https://github.com/snakemake/snakemake/issues/457' target='_blank'>View Comment</a>