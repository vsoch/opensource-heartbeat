---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2022-11-15
repo_name: flux-framework/flux-operator
html_url: https://github.com/flux-framework/flux-operator/commit/58092385c932ddc36685bf90bdea0e83cc59ec70
repo_url: https://github.com/flux-framework/flux-operator
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/flux-framework/flux-operator' target='_blank'>flux-framework/flux-operator</a>

<small>add support for multiple containers (#32)

* add support for multiple containers

this is working for our single, and to complete
the multi container example I will first need to get the Dockerfile
for the multi-container examples, provide a multi-stage build here,
and then use those bases for it. I believe the current containers
do not have the right users (there is no sudo) so I need to
investigate first

* adding WIP multi container pods

these are not entirely working yet - I need to better
understand how the containers should run!
* lifecycle post start exec should be optional
* add badass gopher

look out here he comes!

* Add Restful API (#34)
* earlywork to add restful api

the main issue is exposing the service for
the indexed pod - I am not sure if this is possible
* addng quasi temporary solution to expose service
* auth is enabled, command removed from crd, next we need pip installable client
* add how to submit a job using flux-restful-cli

we now need a way to derive logs for the job
since they do not stream in the console/

* confirmed that restful and command line jobs work!

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/flux-framework/flux-operator/commit/58092385c932ddc36685bf90bdea0e83cc59ec70' target='_blank'>View Commit</a>