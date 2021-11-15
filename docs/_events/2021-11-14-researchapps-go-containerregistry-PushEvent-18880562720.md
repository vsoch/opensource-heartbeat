---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2021-11-14
repo_name: researchapps/go-containerregistry
html_url: https://github.com/researchapps/go-containerregistry/commit/e562b987cbb648b834aba1e9c7d1449c12166e5b
repo_url: https://github.com/researchapps/go-containerregistry
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/researchapps/go-containerregistry' target='_blank'>researchapps/go-containerregistry</a>

<small>update crane mutate annotation/label args to allow commas in label values

With the current argument type, a common in a label value (a reasonable thing to have)
will be split and parsed as a separate label, and the client errors. This commit updates
the flag to StringToStringVarP so we start with a map[string]string off the bat, and do not
need to do special parsing beyond checking for empty strings.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/researchapps/go-containerregistry/commit/e562b987cbb648b834aba1e9c7d1449c12166e5b' target='_blank'>View Commit</a>