---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2025-06-27
repo_name: converged-computing/usernetes
html_url: https://github.com/converged-computing/usernetes/commit/611c0baeba3c457820ce4970c24893091ceb52cd
repo_url: https://github.com/converged-computing/usernetes
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/converged-computing/usernetes' target='_blank'>converged-computing/usernetes</a>

<small>on-premises: infiniband fullly working with this setup

Infiniband is working on TOSS
4.18.0-553.56.1.1toss.t4 based on RHEL 8.10.
For this to work, most of the issue was with
respect to network firewalls, kernel modules,
and system security. Fixes here include
needing to create unique CNI names for podman,
add a flag to ignore preflight errors (for
the old kernel) and update the flannel install
to be before 0.25.x when a check for br_netfilter
was added. This used to be part of kubeadm, and
it was removed with K8s 1.30. It is not technically
needed in the podman container (it is needed on
the physical host) but since the check is done
in the container, this will fail flannel from
starting up. For the time being, we will use
an older flannel, and I will open an issue
on the repository to ask for the ability
to disable the check.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/converged-computing/usernetes/commit/611c0baeba3c457820ce4970c24893091ceb52cd' target='_blank'>View Commit</a>