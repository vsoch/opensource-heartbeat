---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-04-22
repo_name: researchapps/dask-jobqueue
html_url: https://github.com/researchapps/dask-jobqueue/commit/43229c76f2725a9e896474f351b361350e6ddb3e
repo_url: https://github.com/researchapps/dask-jobqueue
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/researchapps/dask-jobqueue' target='_blank'>researchapps/dask-jobqueue</a>

<small>start of work to add flux

Flux has a race condition where after submit (when we get
back a jobid) the file might still be needed. This means
that we need custom logic to not delete the temporary
file until cancel / worker completion. Flux also does
better getting an executable file, and a full path,
and so the submit function is modified for that.
Finally, flux does not support the concept of mem
or an account.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/researchapps/dask-jobqueue/commit/43229c76f2725a9e896474f351b361350e6ddb3e' target='_blank'>View Commit</a>