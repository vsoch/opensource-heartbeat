---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2025-02-15
repo_name: flux-framework/fluxion-go
html_url: https://github.com/flux-framework/fluxion-go/commit/fc2e8cd340d93e2931f9c9e26dd3ad16bf705936
repo_url: https://github.com/flux-framework/fluxion-go
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/flux-framework/fluxion-go' target='_blank'>flux-framework/fluxion-go</a>

<small>bug: find can return > 0, should not be called an error

This is due to a call to check_array_size
that returns an rc, but it is not actually
a return code, it is the sum of elements
in the array. The function can also return
a negative value (when things go wrong)
but it seems it can look like an error when
it goes right and returns a positive, nonzero
value. For the time being I am tweaking our
reapi error parser to call anything >=0
not an error (nil)

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/flux-framework/fluxion-go/commit/fc2e8cd340d93e2931f9c9e26dd3ad16bf705936' target='_blank'>View Commit</a>