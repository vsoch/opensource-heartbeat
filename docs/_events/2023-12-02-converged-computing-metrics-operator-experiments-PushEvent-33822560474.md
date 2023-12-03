---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-12-02
repo_name: converged-computing/metrics-operator-experiments
html_url: https://github.com/converged-computing/metrics-operator-experiments/commit/de306e52303cef4b504dcb2502823f942a6cd76a
repo_url: https://github.com/converged-computing/metrics-operator-experiments
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/converged-computing/metrics-operator-experiments' target='_blank'>converged-computing/metrics-operator-experiments</a>

<small>add support for function to monitor activity of spot instances

We want a separate thread that can control watching the spot instances, and
keeping track of when they appear and go away. While not exact, if this runs
every 15 seconds we can get some sense of this! This function also
currently takes charge of disabling hyper threading via the hotplug
script. Later I am going to explore accomplishing this via a launch
template, so that we can have assurance that the nodes come up
ready to go. My biggest concern here is that the template will not
allow for detailed enough customization of different spot types
and the need for the single thread. We may need to run the logic
on all types, regardless.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/converged-computing/metrics-operator-experiments/commit/de306e52303cef4b504dcb2502823f942a6cd76a' target='_blank'>View Commit</a>