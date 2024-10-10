---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-10-09
repo_name: flux-framework/spack
html_url: https://github.com/flux-framework/spack/commit/8e4e3c90602e96479214d29bac1ce122e6999679
repo_url: https://github.com/flux-framework/spack
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/flux-framework/spack' target='_blank'>flux-framework/spack</a>

<small>python: rework how we compute the "command" property (#46850)

Some Windows Python installations may store the Python exe in Scripts/
rather than the base directory. Update `.command` to search in both
locations on Windows. On all systems, the search is now done
recursively from the search root: on Windows, that is the base install
directory, and on other systems it is bin/.</small>

<a href='https://github.com/flux-framework/spack/commit/8e4e3c90602e96479214d29bac1ce122e6999679' target='_blank'>View Commit</a>