---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-05-03
repo_name: researchapps/flux-core
html_url: https://github.com/researchapps/flux-core/commit/ed8b0acc4c615d37e8cc99b680773bc0505ecb12
repo_url: https://github.com/researchapps/flux-core
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/researchapps/flux-core' target='_blank'>researchapps/flux-core</a>

<small>make SchedResourceList optional in flux.job.info

Problem: We currently cannot package rlist.h with the install (at
least without more work) and since this is a required import for
flux.job.info, without it the Python bindings (installed via pip)
will error.
Solution: the flux.resource module is not technically required,
so we can fallback to catching the ImportError instead and using
the same empty (dummy) class to handle self.resources

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/researchapps/flux-core/commit/ed8b0acc4c615d37e8cc99b680773bc0505ecb12' target='_blank'>View Commit</a>