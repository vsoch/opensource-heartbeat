---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2022-03-30
repo_name: singularityhub/singularity
html_url: https://github.com/singularityhub/singularity/commit/78a46fe090bd991316457e2c67410ea307d30687
repo_url: https://github.com/singularityhub/singularity
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/singularityhub/singularity' target='_blank'>singularityhub/singularity</a>

<small>updating --env flags to be a map[string]string

the current flag using a splice type will truncate on commas. In order to better
support commas in --env variables we should have support for types of map[string]string.
This change will add this new option and fix the current --env bug described in slack
that splits name=val1,val2 into just name=val1 and outputs a warning. I saw some custom
parsing code in a different file that maybe was intended to handle this, but it never
gets called because the envar is skipped. If it is not skipped the comma would already
be truncated by the flag parser.

Apologies for mistakes - have not looked at Singularity source code in years it seems!

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/singularityhub/singularity/commit/78a46fe090bd991316457e2c67410ea307d30687' target='_blank'>View Commit</a>