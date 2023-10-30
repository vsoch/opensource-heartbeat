---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-10-29
repo_name: converged-computing/oras-operator
html_url: https://github.com/converged-computing/oras-operator/commit/8daf2ea408fe83487115c186bc7999ad0be9ded9
repo_url: https://github.com/converged-computing/oras-operator
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/converged-computing/oras-operator' target='_blank'>converged-computing/oras-operator</a>

<small>WIP to add entrypoint logic (#3)

* WIP to add entrypoint logic

The oras cache sidecar needs to know how to pull an artifact,
and then create an indicator to the application that it is ready.
The application needs to wait for the indicator, and then
run an entrypoint that wraps the command. Since I want to keep
things simple (and not navigate adding a config map for a webhook
!) I am starting with a wget of the scripts instead of that. We
will see if this is a good idea or not!

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/converged-computing/oras-operator/commit/8daf2ea408fe83487115c186bc7999ad0be9ded9' target='_blank'>View Commit</a>