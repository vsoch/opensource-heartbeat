---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-05-10
repo_name: converged-computing/rainbow
html_url: https://github.com/converged-computing/rainbow/commit/502bfbb8c1ccc4eb5399099ca1f71f50e69e16bc
repo_url: https://github.com/converged-computing/rainbow
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/converged-computing/rainbow' target='_blank'>converged-computing/rainbow</a>

<small>Refactor memory graph (#32)

* feat: basic io match is working

There is still more work to be done with jobspec-go
and parsing from raw values, and also checking the
other match types, but this is a start.

* refactor: memory graph database

Problem: we currently do not have a good model to support traversal
of more than one scheduled slot (a group of resources) and checking
of requires within and outside of the slot.
Solution: Jobspec nextgen provides a function to expose schedul-able
slots. A slot does not necessarily start at the top - it can have
some set of resources at the top level (with requirements) and then
the slot is below it. This means that the graph databases recursive
algorithm needs to first traverse into a vertex to find the slot,
but along the way check the subsystem requirements for types. For
example, even if we want N nodes, we should not continue search
if a node does not have an attribute we are interested in. Once
we find a slot, we create what is akin to a traverser, and the
traverser carries with it a resource counter. The resource
counter holds the count of needed slots vs. found slots, and
then is able to return as soon as we found as many as we need.
It also holds the current state (status) of a current search,
meaning we decrement either a resource or subsystem count
when we find it somewhere in the subgraph of the slot. This
is just the early prototype, and so far just working for the
simple case of submitting a job with some need for cores and
nodes. I am next going to go back through the more specific
IO cases and ensure that they still with, with the goal to
get back to the spack case. I am going back to sleep for a
bit first, kind of tired.

* io example is working

This example is needing to search both compatibility requirements
and look for resources within a slot.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/converged-computing/rainbow/commit/502bfbb8c1ccc4eb5399099ca1f71f50e69e16bc' target='_blank'>View Commit</a>