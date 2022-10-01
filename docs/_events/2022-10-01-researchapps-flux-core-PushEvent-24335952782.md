---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2022-10-01
repo_name: researchapps/flux-core
html_url: https://github.com/researchapps/flux-core/commit/f7cdeb29d8a638e249cfeb0fc9ff780f12559a18
repo_url: https://github.com/researchapps/flux-core
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/researchapps/flux-core' target='_blank'>researchapps/flux-core</a>

<small>consolidate python linting and formatting

Problem: the developer experience is challenging because
linting and formatting are hard to debug locally, and then
the separation in the CI means 3+ clicks to see what is
going on! To fix this, this changeset adds the use of
pre-commit, which will always run linting/formatting
(and with automated fixes for a subset of the tools)
right before commit, so the developer can have some
confidence that passing locally == passing in the CI.
In the case that there is a bug in the CI, we will
now just have one place to look instead of 3+. This
should be a start of a new setup, including addition
of pre-commit and consolidation of settings into a
pyproject.toml (and setup.py for flake8) and we can
further tweak as we establish our linting preferences.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/researchapps/flux-core/commit/f7cdeb29d8a638e249cfeb0fc9ff780f12559a18' target='_blank'>View Commit</a>