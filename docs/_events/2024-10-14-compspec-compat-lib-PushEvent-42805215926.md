---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-10-14
repo_name: compspec/compat-lib
html_url: https://github.com/compspec/compat-lib/commit/87f865131b63942cde748470cc592a549c983d9e
repo_url: https://github.com/compspec/compat-lib
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/compspec/compat-lib' target='_blank'>compspec/compat-lib</a>

<small>compatibility: add use case for library server

We want to be able to check software compatbility, amongst other things.
In Kubernetes, Node Feature Discovery (NFD) has a design where a daemon
runs on the nodes, can parse what they provide, and then provides
that to a central service. For our case, we can do similar - having
a service (that can run on the node and either work with a local client
OR a scheduler) that knows how to read either a compatibility artifact
directly (json payload) or retrieve from a registry, where it describes
an application or container, and then based on the libraries needed,
quickly determine if the node can satisfy the needs. This I am calling
a Compatibility server and check because it extends to other things
beyond libraries / software.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/compspec/compat-lib/commit/87f865131b63942cde748470cc592a549c983d9e' target='_blank'>View Commit</a>