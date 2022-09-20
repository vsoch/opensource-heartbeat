---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2022-09-19
repo_name: researchapps/flux-core
html_url: https://github.com/researchapps/flux-core/commit/b06fdb9aa775322ea5050dde6f81ab32a20aaba5
repo_url: https://github.com/researchapps/flux-core
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/researchapps/flux-core' target='_blank'>researchapps/flux-core</a>

<small>docker: add namespaced builds for spack/ubuntu

We currently build one set of containers that are
spack focused, and ideally we should provide this
along with more vanilla (e.g., ubuntu) builds.
This update will move the spack builds into a
spack subdirectory and add two ubuntu builds -
one a base container, and the other that just
runs a make check-prep to run some tests.
This ubuntu base could be used for other contexts
of testing, and I think after the python work is
integrated we would migrate the container there
into this directory too.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/researchapps/flux-core/commit/b06fdb9aa775322ea5050dde6f81ab32a20aaba5' target='_blank'>View Commit</a>