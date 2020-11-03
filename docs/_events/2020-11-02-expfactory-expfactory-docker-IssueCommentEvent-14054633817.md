---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2020-11-02
repo_name: expfactory/expfactory-docker
html_url: https://github.com/expfactory/expfactory-docker/issues/185
repo_url: https://github.com/expfactory/expfactory-docker
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/expfactory/expfactory-docker/issues/185' target='_blank'>expfactory/expfactory-docker#185</a>.

<small>You could definitely try saving as a string, and then converting later - I've tried this before with a different kind of blob (an OCI manifest) and wound up finding it easier to change to the Binary Type Field instead. I'm not a developer here anymore, but my intuition is that this would be a special use case that you'd best implement on your branch. if you want to give this a shot I'd first add a binarydata field alongside taskdata in turk.models.Result, and then you'd need to add logic where [sync is done](https://github.com/expfactory/expfactory-docker/blob/master/expdj/apps/experiments/views.py#L609) to check for the additional data (or something about the sync that indicates it's present) and then save to that field....</small>

<a href='https://github.com/expfactory/expfactory-docker/issues/185' target='_blank'>View Comment</a>