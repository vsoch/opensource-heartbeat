---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-08-20
repo_name: converged-computing/google-batch
html_url: https://github.com/converged-computing/google-batch/issues/1
repo_url: https://github.com/converged-computing/google-batch
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> closed issue <a href='https://github.com/converged-computing/google-batch/issues/1' target='_blank'>converged-computing/google-batch#1</a>.

<p>Need some concept of success policy</p><small>What seems to happen more often than not is that the second worker exits, and then the first has the connection close unexpectedly and then is waiting for it to come online. The job then runs indefinitely (I waited until the supposed cutoff time, 1 hour, and it's still going.) We need to be able to have the worker sleep infinity, but be shut down for good when the first VM is done. I'm not sure how to accomplish that yet - it could be as simple as touching a final "done" final and then having an exit....</small><a href='https://github.com/converged-computing/google-batch/issues/1' target='_blank'>View Comment</a>