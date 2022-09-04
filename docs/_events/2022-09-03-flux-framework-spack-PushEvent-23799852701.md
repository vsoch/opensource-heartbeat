---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2022-09-03
repo_name: flux-framework/spack
html_url: https://github.com/flux-framework/spack/commit/c25b7ea89867836bd7e8491689c5342af09fc743
repo_url: https://github.com/flux-framework/spack
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/flux-framework/spack' target='_blank'>flux-framework/spack</a>

<small>Apply hip workaround for raja-framework (#32469)

* add workaround for broken behavior in HIP

Hip has a longstanding cmake issue where they calculate include paths
incorrectly, this works around it for raja and adds an explicit rocprim
dependency.

* propagate openmp requirement and workaround to camp

* refactor and include umpire

* propagate openmp option to camp in umpire and use main camp for main and develop raja and umpire

* bump camp to new patch release</small>

<a href='https://github.com/flux-framework/spack/commit/c25b7ea89867836bd7e8491689c5342af09fc743' target='_blank'>View Commit</a>