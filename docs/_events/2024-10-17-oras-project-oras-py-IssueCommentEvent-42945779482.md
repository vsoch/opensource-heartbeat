---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-10-17
repo_name: oras-project/oras-py
html_url: https://github.com/oras-project/oras-py/issues/164
repo_url: https://github.com/oras-project/oras-py
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/oras-project/oras-py/issues/164' target='_blank'>oras-project/oras-py#164</a>.

<small>The bug is [here](https://github.com/oras-project/oras-py/blob/36ef98afb6036eb4e3b70890aa941a8236937613/oras/auth/token.py#L117) @tarilabs - the prefix is expected to be for the registry, but with the refactor it was removed. It was originally derived here: https://github.com/oras-project/oras-py/blob/36ef98afb6036eb4e3b70890aa941a8236937613/oras/provider.py#L69 and so an easy fix is to move it, or pass forward....</small>

<a href='https://github.com/oras-project/oras-py/issues/164' target='_blank'>View Comment</a>