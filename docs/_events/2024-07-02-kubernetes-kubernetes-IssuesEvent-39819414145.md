---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-07-02
repo_name: kubernetes/kubernetes
html_url: https://github.com/kubernetes/kubernetes/issues/125852
repo_url: https://github.com/kubernetes/kubernetes
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> open issue <a href='https://github.com/kubernetes/kubernetes/issues/125852' target='_blank'>kubernetes/kubernetes#125852</a>.

<p>/dev/shm can be oversubscribed compared to host</p><small>Hi! I noticed that when we create the emptyDir and specify [Memory as the storage medium](https://github.com/kubernetes/kubernetes/blob/ff8834cdd7abb9a2975f20dffb575d7f00a1d4d3/pkg/volume/emptydir/empty_dir.go#L150) and allow to calculate the sizeLimit "to match the host" - it does so based on the pod resource spec, [here](https://github.com/kubernetes/kubernetes/blob/ff8834cdd7abb9a2975f20dffb575d7f00a1d4d3/pkg/volume/emptydir/empty_dir.go#L122-L132).  I was testing this on an AWS hpc7g instance, which has 64 GB in `/dev/shm` (on the host) and the entire host has 128GB:...</small><a href='https://github.com/kubernetes/kubernetes/issues/125852' target='_blank'>View Comment</a>