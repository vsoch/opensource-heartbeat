---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2021-02-20
repo_name: spack/spack-monitor
html_url: https://github.com/spack/spack-monitor/commit/383feb908151afd7230219ec387b5f2bcad77972
repo_url: https://github.com/spack/spack-monitor
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/spack/spack-monitor' target='_blank'>spack/spack-monitor</a>

<small>start of work to add Build table

We need to include BuildEnvironment and objects alongside a Spec build,
and we need it to be possible to build the same spec in different environments
and have different ids/rows in the table. This is start of work to do that,
and also clean up some of the API namespace. I next need to go into spack
and refactor for this structure, and figure out how to get a list of object
files after a build to (eventually) parse and send to the spack monitor

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/spack/spack-monitor/commit/383feb908151afd7230219ec387b5f2bcad77972' target='_blank'>View Commit</a>