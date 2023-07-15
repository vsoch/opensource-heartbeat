---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-07-14
repo_name: flux-framework/spack
html_url: https://github.com/flux-framework/spack/commit/2e9e7ce7c49990cccd8a8d777f0491978d72220d
repo_url: https://github.com/flux-framework/spack
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/flux-framework/spack' target='_blank'>flux-framework/spack</a>

<small>Bugfix/spack spec: read and use the environment concretizer:unification option (#38248)

* Bugfix: spack.yaml concretizer:unify needs to be read and used
* Optional: add environment test to ensure configuration scheme is used
* Activate environment in unit tests
  A more proper solution would be to keep
  an environment instance configuration as
  an attribute, but that is a bigger refactor
* Delay evaluation of Environment.unify
* Slightly simplify unit tests

---------

Co-authored-by: Massimiliano Culpo <massimiliano.culpo@gmail.com></small>

<a href='https://github.com/flux-framework/spack/commit/2e9e7ce7c49990cccd8a8d777f0491978d72220d' target='_blank'>View Commit</a>