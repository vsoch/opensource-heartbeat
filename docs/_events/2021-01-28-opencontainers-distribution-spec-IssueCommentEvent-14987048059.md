---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2021-01-28
repo_name: opencontainers/distribution-spec
html_url: https://github.com/opencontainers/distribution-spec/issues/187
repo_url: https://github.com/opencontainers/distribution-spec
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/opencontainers/distribution-spec/issues/187' target='_blank'>opencontainers/distribution-spec#187</a>.

<small>I think so - I was thinking that it would make sense to add a line to the spec that the content type of each subsequent PATCH is required to be the same as the first, and if it doesn't matches, maybe a particular response code is returned. I don't see any cases where it would be a good thing / realistic for a content type to change mid upload. Another idea would be that it's required for the first, but then just not checked for subsequent (and then errors could happen if the type changes, but this would be a user error)....</small>

<a href='https://github.com/opencontainers/distribution-spec/issues/187' target='_blank'>View Comment</a>