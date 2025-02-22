---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2025-02-21
repo_name: NVIDIA/nvidia-container-toolkit
html_url: https://github.com/NVIDIA/nvidia-container-toolkit/issues/56
repo_url: https://github.com/NVIDIA/nvidia-container-toolkit
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/NVIDIA/nvidia-container-toolkit/issues/56' target='_blank'>NVIDIA/nvidia-container-toolkit#56</a>.

<small>@elezar it looks like both the PRs you mentioned have been merged - I've been trying to get GPUs working in userspace kubernetes, which means rootless docker running on the host, and then inside the container provided by rootless docker we have kubernetes components. I was able to set `no-cgroups = true` in the host nvidia container runtime config and the container built and started, but then I get an error from the kubelet when trying to install / run the gpu operator via helm (and I suspect I'd hit this for other cases too):...</small>

<a href='https://github.com/NVIDIA/nvidia-container-toolkit/issues/56' target='_blank'>View Comment</a>