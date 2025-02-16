---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2025-02-14
repo_name: researchapps/eksctl
html_url: https://github.com/researchapps/eksctl/commit/947f8987cbf2c64344110d4ee8201755be6745cd
repo_url: https://github.com/researchapps/eksctl
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/researchapps/eksctl' target='_blank'>researchapps/eksctl</a>

<small>bug: placement group should not be added for reservation

Reservations are special cases that often can be created
with placement already in mind, or have instances in different
availability zones (or far enough away) so adding a placement
group automatically will prevent provision of a large set of
resources. Changing the default behavior to always require the
user to specify a placement group for EFA is overkill, but
a good balance is, in the case EFA is enabled and there is no
placement group, when there is a reservation do not add the
group automatically, but issue a warning to the user they can
choose to respond to. TLDR: when a user deploys a cluster via
a reservation they are responsible for adding the placement
group.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/researchapps/eksctl/commit/947f8987cbf2c64344110d4ee8201755be6745cd' target='_blank'>View Commit</a>