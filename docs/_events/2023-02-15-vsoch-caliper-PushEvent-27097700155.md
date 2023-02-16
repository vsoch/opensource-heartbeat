---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-02-15
repo_name: vsoch/caliper
html_url: https://github.com/vsoch/caliper/commit/b5fc226e9dd40112a5a643360186d3ffa05025ac
repo_url: https://github.com/vsoch/caliper
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/vsoch/caliper' target='_blank'>vsoch/caliper</a>

<small>start of experiment to trace call and compare to signatures

Today I tested standard trace, then pytrace, and realized I could
write my own function around sys.settrace to get detailed metadata
about calls! I got to the point where I have the database of functions
known across versions, and a trace, and next I need an efficient way to
query. I likely will (for next steps) add this as a caliper analyzer using
an sqlite database proper to query.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/vsoch/caliper/commit/b5fc226e9dd40112a5a643360186d3ffa05025ac' target='_blank'>View Commit</a>