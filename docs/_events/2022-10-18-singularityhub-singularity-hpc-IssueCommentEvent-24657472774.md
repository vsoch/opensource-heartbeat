---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2022-10-18
repo_name: singularityhub/singularity-hpc
html_url: https://github.com/singularityhub/singularity-hpc/issues/598
repo_url: https://github.com/singularityhub/singularity-hpc
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/singularityhub/singularity-hpc/issues/598' target='_blank'>singularityhub/singularity-hpc#598</a>.

<small>@audreystott for one more update for my plan - generating the container.yaml files (without aliases) is really easy, but I think we can try to do better - I started generating container.yaml with aliases manually (realized this wouldn't scale) and then I added to the script to extract the aliases, but they wouldn't be high quality if we just include everything (there is a lot of extra stuff typically installed to /usr/local/bin we wouldn't want to include, it's noise). So what I'm going to do is extract aliases in /usr/local/bin across containers, and then I'll find meaningful ones by some filter for frequency (TBA!) For the time being I'm just generating the commands (which might be useful to someone else eventually anyway). I'm up to b's woot! ...</small>

<a href='https://github.com/singularityhub/singularity-hpc/issues/598' target='_blank'>View Comment</a>