---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2021-12-22
repo_name: abitrolly/fedora-packages-static
html_url: https://github.com/abitrolly/fedora-packages-static/issues/9
repo_url: https://github.com/abitrolly/fedora-packages-static
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/abitrolly/fedora-packages-static/issues/9' target='_blank'>abitrolly/fedora-packages-static#9</a>.

<small>oh that makes sense! So watchme is probably different in terms of goals - with watchme the idea is that you can store files in git over time, and then assemble all the results in one place upon an extraction. E.g., git A has a json structure with value 2, git timepoint B has 3, the results will be [2,3]. But it sounds like you want to be able to just get the entire summary statistics for a given timepoint. You are correct you'll hit a point of failure if you have, say, 100 of these running at once all trying to fetch and push - it's just hugely likely that upstream will change in the process and then the push will fail. Even for watchme, trying to run extractions on a cluster was a massive failure because git just isn't intended to work that way....</small>

<a href='https://github.com/abitrolly/fedora-packages-static/issues/9' target='_blank'>View Comment</a>