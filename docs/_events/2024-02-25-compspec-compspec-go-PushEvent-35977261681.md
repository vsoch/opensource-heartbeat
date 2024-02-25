---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-02-25
repo_name: compspec/compspec-go
html_url: https://github.com/compspec/compspec-go/commit/11118b1d93fccd0dcfb8d865361159a7a2879360
repo_url: https://github.com/compspec/compspec-go
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/compspec/compspec-go' target='_blank'>compspec/compspec-go</a>

<small>wip: add support for node extraction -> cluster metadata

Problem: we need a extract metadata for nodes and then parse into a cluster graph
Solution: create a compspec create nodes subcommand.

In this PR I am adding a ClusterGraph, which still needs work to improve the output
to easily map into a JGF (right now it has elements that can support any type
that need further parsing). I am also generalizing the idea of plugins more, so
we will have extractors and converters (that run create) but I need to finalize
the design for the latter, right now the create commands are very separate. I
am opening the PR sooner than later in case my computer explodes. A few problems
I have run into is that NFD does not have cpu counts, let along physical vs.
logical. This information is in /proc/cpuinfo for x86 but not arm. We also
do not have a way to get socket -> core mapping. So likely we do need to add
the hwloc extractor, and provide an automated build for doing that since
it requires hwloc on the system. I will put some thought into this.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/compspec/compspec-go/commit/11118b1d93fccd0dcfb8d865361159a7a2879360' target='_blank'>View Commit</a>