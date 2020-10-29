---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2020-10-28
repo_name: datalad/datalad-container
html_url: https://github.com/datalad/datalad-container/issues/98
repo_url: https://github.com/datalad/datalad-container
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/datalad/datalad-container/issues/98' target='_blank'>datalad/datalad-container#98</a>.

<small>I think it would be cleaner to go directly from the Registry API, and then retrieve the exact downloads for the layers and config, which already come with the digests. As I understand docker save, it's going to write on the fly, which means new timestamps and thus new hashes. It would be confusing for the user to see a known image locally (e.g., busybox:vX.X.X) and then not see digests that line up with what is on Docker Hub (or another registry). The benefit of not using docker save is that docker does not become a dependency for datalad. It's also messy to have "the same" layers that appear different because of different timestamps....</small>

<a href='https://github.com/datalad/datalad-container/issues/98' target='_blank'>View Comment</a>