---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-02-12
repo_name: converged-computing/rainbow
html_url: https://github.com/converged-computing/rainbow/commit/b454bf3e01caf4749d91c6a35fa480c0ee6f472a
repo_url: https://github.com/converged-computing/rainbow
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/converged-computing/rainbow' target='_blank'>converged-computing/rainbow</a>

<small>add job submit commands, database, and new client

This change adds the JobSubmit, to proto, and to each
of the client and server. At this point we can request
a job to be submit to a specific cluster, and the
token that was generated on register of the cluster
is required to "authenticate." We then validate those
things and add the job to the database! Next we need a
small client to run from within a flux instance and
check for jobs assigned to it, and when it receives
one, it will be removed from the database. I think I
want to make flux-core "bindings" for Go first.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/converged-computing/rainbow/commit/b454bf3e01caf4749d91c6a35fa480c0ee6f472a' target='_blank'>View Commit</a>