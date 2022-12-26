---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2022-12-25
repo_name: ACCESS-NRI/oasis3-mct
html_url: https://github.com/ACCESS-NRI/oasis3-mct/issues/13
repo_url: https://github.com/ACCESS-NRI/oasis3-mct
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/ACCESS-NRI/oasis3-mct/issues/13' target='_blank'>ACCESS-NRI/oasis3-mct#13</a>.

<small>I have an example of doing a cache (not of the layer, but of the spack install, but the logic would be similar) here https://github.com/sciworks/spack-updater/blob/db34cdd94dcc1fdb29626e78f85f5fa62156faad/build/action.yaml#L53-L64. E.g., given that spack cares about micro-architecture, we associate the cache key with it. In this case it saves the build about 22 minutes in not needing to build bootstrap from source (and we don't hit the spack binary cache because spack only supports ubuntu 20.04 for it afaik)....</small>

<a href='https://github.com/ACCESS-NRI/oasis3-mct/issues/13' target='_blank'>View Comment</a>