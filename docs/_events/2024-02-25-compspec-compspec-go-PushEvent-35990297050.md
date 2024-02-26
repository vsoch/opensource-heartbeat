---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-02-25
repo_name: compspec/compspec-go
html_url: https://github.com/compspec/compspec-go/commit/6c8b8da502594f00f1043770f420cce42f47d608
repo_url: https://github.com/compspec/compspec-go
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/compspec/compspec-go' target='_blank'>compspec/compspec-go</a>

<small>wip: integration with rainbow

This set of small changes is to support node generation for the
rainbow scheduler. There was a small bug in the way I was serializing
the cluster graph that it forgot the top level "graph" key, and
I have also cleaned up passing of arguments for the plugins. The paths
for containment also were slightly off. I will leave this PR open as
I figure out how to actually accept the graph in rainbow. I wanted
to use fluxion but I realize there is not support for extending
or growing a graph so I would not be able to add more than one cluster.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/compspec/compspec-go/commit/6c8b8da502594f00f1043770f420cce42f47d608' target='_blank'>View Commit</a>