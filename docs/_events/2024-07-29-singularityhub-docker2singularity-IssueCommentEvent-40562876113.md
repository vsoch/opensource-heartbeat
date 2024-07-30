---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-07-29
repo_name: singularityhub/docker2singularity
html_url: https://github.com/singularityhub/docker2singularity/issues/133
repo_url: https://github.com/singularityhub/docker2singularity
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/singularityhub/docker2singularity/issues/133' target='_blank'>singularityhub/docker2singularity#133</a>.

<small>@Soratake-HirotakaYajima this morning I built a new release: `quay.io/singularity/docker2singularity:latest` and here is my suggestion. That image has singularity 4.1.4 and I also added the development headers of that library mentioned. Give that a try. If it doesn't work, please shell into the container interactively and try doing something else with Singularity (a singularity run of a docker uri would suffice) to see if you can reproduce the issue. If you can, then please try doing the same run in one of the images here: https://quay.io/repository/singularity/singularity. The main difference is that they are built with an ubuntu base (vs. here is alpine), so we can rule that out. Hopefully some of the above investigation can help shed some light on the issue. Thanks!...</small>

<a href='https://github.com/singularityhub/docker2singularity/issues/133' target='_blank'>View Comment</a>