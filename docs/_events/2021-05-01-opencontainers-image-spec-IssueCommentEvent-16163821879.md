---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2021-05-01
repo_name: opencontainers/image-spec
html_url: https://github.com/opencontainers/image-spec/pull/848
repo_url: https://github.com/opencontainers/image-spec
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/opencontainers/image-spec/pull/848' target='_blank'>opencontainers/image-spec#848</a>.

<small>Okay I finally have it working - I had to figure out the structure of the GitHub actions workspace, and then be a little more pendantic about paths. I wound up cloning the repository to where it should be in a gopath, a relative path at `go/github.com/opencontainers/image-spec`, and that is relative to the `GITHUB_WORKSPACE` which weirdly has the repository name twice, like `/home/runner/work/image-spec/image-spec`, which meant that the GOPATH was `/home/runner/work/image-spec/image-spec/go`....</small>

<a href='https://github.com/opencontainers/image-spec/pull/848' target='_blank'>View Comment</a>