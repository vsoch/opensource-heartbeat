---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-06-20
repo_name: spack/spack
html_url: https://github.com/spack/spack/pull/44775
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/spack/spack/pull/44775' target='_blank'>spack/spack#44775</a>.

<small>This change is saying that if flux is provided as an external, it's up to the external provider to set the LUA paths, which I think is logical. The issue is that adding it as an external is going to look for spec with lua, and that likely is not present if lua was only a dependent for flux. It would still not work to add it, because it might be an actual mismatch in version. My only critique might be to check for external and just return early, and then not indent the rest of the function. It would also be good to add a comment above that, explaining the logic for a future package.py reader....</small>

<a href='https://github.com/spack/spack/pull/44775' target='_blank'>View Comment</a>