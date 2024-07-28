---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-07-28
repo_name: converged-computing/fluxnetes
html_url: https://github.com/converged-computing/fluxnetes/commit/633bf3644c3cddf8665e8e0a92b5133e144de466
repo_url: https://github.com/converged-computing/fluxnetes
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/converged-computing/fluxnetes' target='_blank'>converged-computing/fluxnetes</a>

<small>worker: retrieval of podspec and AskFlux

This changeset creates separate worker and podgroup fluxnetes
package files, and they handle worker definition and pod group
parsing functions, respectively. Up to this point we can now
1. retrieve a new pod and see if it is in a group.
2. if no (size 1) add to worker queue immediatel.
   if yes (size N) add to pods table to be inspected later
3. retrieve the podspec in the work function
4. parse back into podspec and ask flux for the allocation.
I next need to do two things. First, figure out how to pass
the node assignment back to the scheduler - I am hoping
the job object "JobRow" can be modified to add metadata.
Then we need to write the function to run at the end of
a schedule cycle that moves groups from the provisional
table to the worker queue

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/converged-computing/fluxnetes/commit/633bf3644c3cddf8665e8e0a92b5133e144de466' target='_blank'>View Commit</a>