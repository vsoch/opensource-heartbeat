---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2022-10-11
repo_name: researchapps/flux-core
html_url: https://github.com/researchapps/flux-core/commit/9a8e3ccc11a51df915843d464a73120fb124870c
repo_url: https://github.com/researchapps/flux-core
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/researchapps/flux-core' target='_blank'>researchapps/flux-core</a>

<small>add devcontainer environment for vscode

Problem: it is hard to develop flux-core locally.
This addition will allow VSCode users to quickly
run (and work in) a development container, defined
under .devcontainer in the root, which contains a
devcontainer.json file and a Dockerfile that uses
the fluxrm/testenv:focal base to quickly pull and
spin up the container. We need the Dockerfile to
support a post start command to fix a git security
issue, and also add developer tools like formatters,
linters, etc. This is a vanilla install, meaning it
just will allow for build of the core flux, and as
other developers try this out we can easily add
other extensions that make the development experience
better!

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/researchapps/flux-core/commit/9a8e3ccc11a51df915843d464a73120fb124870c' target='_blank'>View Commit</a>