---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-06-04
repo_name: dask/dask-jobqueue
html_url: https://github.com/dask/dask-jobqueue/pull/605
repo_url: https://github.com/dask/dask-jobqueue
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/dask/dask-jobqueue/pull/605' target='_blank'>dask/dask-jobqueue#605</a>.

<small>okay this is a bad design and I can't support moving forward without more thinking. Right now, dask requires a shared temporary space to write the job scripts and have a scratch space for itself. I was doing a hack to make a host volume that would be this location (via `TMPDIR`) but this gets ugly really quickly because other applications grab onto it, and all of a sudden we have the case of needing to clean up the dask stuff, but not the other temporary files (e.g., a flux local socket) and then if you aren't absolultely careful, the entire thing breaks (and it's a really bad setup / standard to start from). If we use this approach:...</small>

<a href='https://github.com/dask/dask-jobqueue/pull/605' target='_blank'>View Comment</a>