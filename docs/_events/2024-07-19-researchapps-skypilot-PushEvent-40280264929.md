---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-07-19
repo_name: researchapps/skypilot
html_url: https://github.com/researchapps/skypilot/commit/1ef6ec4b3cbb27db9afa1d47c553d33bfbb04409
repo_url: https://github.com/researchapps/skypilot
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/researchapps/skypilot' target='_blank'>researchapps/skypilot</a>

<small>feat: adding flux as a cloud

This changeset adds flux as a new cloud, which largely
wraps the Kubernetes cloud class, but provides the separation
to make it clear we are deploying Flux, and to allow for other
small tweaks to the customization. This currently works to
deploy Kubernetes (via the Flux cloud) and when I uncomment
the deploy_vars "module" variable it will be able to use a
work in progress provisioner module, which is not added to
this changeset. Note that my strategy is to make as minimal
changes as possible, so I am using the same Kubernetes classes
and templates and editing only when necessary.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/researchapps/skypilot/commit/1ef6ec4b3cbb27db9afa1d47c553d33bfbb04409' target='_blank'>View Commit</a>