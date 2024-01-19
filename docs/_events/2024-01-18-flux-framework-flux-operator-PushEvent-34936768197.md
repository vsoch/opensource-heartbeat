---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-01-18
repo_name: flux-framework/flux-operator
html_url: https://github.com/flux-framework/flux-operator/commit/289128a8ccbda725bccc7f24742e9a8dcf5d4308
repo_url: https://github.com/flux-framework/flux-operator
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/flux-framework/flux-operator' target='_blank'>flux-framework/flux-operator</a>

<small>feat: add support for downsize

we can allow the cluster to downsize if the follower broker
exits cleanly with 0, without need for the broker index max
completions attribute that is enabled with a feature gate
and requires k8s 1.28. This change also adds support for a
minSize cluster, which will work to start the quorum when
fewer than the size workers are available. note that this does
not adjust tasks given to a job, so might be assigning too
many tasks to too few workers. This also adds in the previous
downsize workers example, except instead of using pkill for
rockylinux we fall back to flux overlay disconnect, as pkill
is not available by default. It is up to the user to ensure
that the follower broker can be disconnected (and is not running
anything). Finally, we add support for a flux->arch tag,
specifically for an arm binary to be downloaded and used
for the go-wait-fs command.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/flux-framework/flux-operator/commit/289128a8ccbda725bccc7f24742e9a8dcf5d4308' target='_blank'>View Commit</a>