---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-12-26
repo_name: converged-computing/lammps-stream-ml
html_url: https://github.com/converged-computing/lammps-stream-ml/commit/0a6f16099105645dcfb81d211163782ed0a4c78f
repo_url: https://github.com/converged-computing/lammps-stream-ml
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/converged-computing/lammps-stream-ml' target='_blank'>converged-computing/lammps-stream-ml</a>

<small>Add k8s (#2)

* add kubernetes deployment

this will run the ml-service in kubernetes, and then run lammps alongside
it from a singularity container. We randomly select parameters x,y,z
from some range and then use that to train each of three models in the server.
We then have another script that does the same to generate testing data,
save the predictions alongside the actual values, and calculate an accuracy.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/converged-computing/lammps-stream-ml/commit/0a6f16099105645dcfb81d211163782ed0a4c78f' target='_blank'>View Commit</a>