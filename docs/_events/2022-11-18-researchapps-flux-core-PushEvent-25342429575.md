---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2022-11-18
repo_name: researchapps/flux-core
html_url: https://github.com/researchapps/flux-core/commit/30463c91b5cbe73f39bd7cddf6fdfe74fe9f58e8
repo_url: https://github.com/researchapps/flux-core
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/researchapps/flux-core' target='_blank'>researchapps/flux-core</a>

<small>python: add flux.job.get_job

Problem: most users of the Python API (or any API in
general) ideally want an intuitive user interface.
An early likely interaction is to do a flux.job.submit,
and then (for many use cases) the next desire is to get
more information about the job. As currently implemented,
the user needs to stumble on flux.job.job_list_id and
decide to try it, and then further to look at the rpc
object returned and figure out they can do get_str and
json loads that, OR a less intuitive "get" to do the same.
OR they could figure out some interaction with a JobInfo
object, which to be frank, I do not see how they would
know to go there because it is located in a totally
separate place, and requires knowing how to instantiate
(and is not just calling an easy function). See
https://github.com/flux-framework/flux-core/issues/4760

Solution: the ideal solution from the point of user
expectation is to place an obvious "get_job" directly
on the same module the user is already interacting with.
It can be quickly found and returns the expected data
structure without further parsing needed.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/researchapps/flux-core/commit/30463c91b5cbe73f39bd7cddf6fdfe74fe9f58e8' target='_blank'>View Commit</a>