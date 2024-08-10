---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-08-09
repo_name: converged-computing/fluxnetes
html_url: https://github.com/converged-computing/fluxnetes/issues/4
repo_url: https://github.com/converged-computing/fluxnetes
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> closed issue <a href='https://github.com/converged-computing/fluxnetes/issues/4' target='_blank'>converged-computing/fluxnetes#4</a>.

<p>Discussion: do a reservation instead</p><small>I think instead of `MatchAllocate` we should do `MatchAllocateElseReserve` and then we don't need to run the job again - the work will be scheduled for a future point. I haven't ever used this function, but I'm assuming since a single schedule cycle updates these reservations, we likely need to schedule this to run again at a time in the future (the time of the reservation) and run `MatchAllocateElseReserve` again (and keep going until it's allocated) or use a separate queue. ...</small><a href='https://github.com/converged-computing/fluxnetes/issues/4' target='_blank'>View Comment</a>