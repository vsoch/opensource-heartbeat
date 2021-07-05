---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2021-07-05
repo_name: opencontainers/distribution-spec
html_url: https://github.com/opencontainers/distribution-spec/issues/289
repo_url: https://github.com/opencontainers/distribution-spec
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> open issue <a href='https://github.com/opencontainers/distribution-spec/issues/289' target='_blank'>opencontainers/distribution-spec#289</a>.

<p>Content Length Required</p><small>I wanted to open up some discussion about the `Content-Length` header. Currently the spec does not say that all responses are required to have it, and this possibly makes sense because we could look it up, say, in the manifest, but since Content-Length is sort of bread and butter when it comes to communicating about requests/responses, is there any reason to not have it? Many libraries can find this field useful, so we are proposing to have it added to all registry responses that make sense for a future release:...</small><a href='https://github.com/opencontainers/distribution-spec/issues/289' target='_blank'>View Comment</a>