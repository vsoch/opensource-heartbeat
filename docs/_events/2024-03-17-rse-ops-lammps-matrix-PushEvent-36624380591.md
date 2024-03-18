---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-03-17
repo_name: rse-ops/lammps-matrix
html_url: https://github.com/rse-ops/lammps-matrix/commit/21866dd3f10c7187f8ed19c4ee2517eb8dc21ad3
repo_url: https://github.com/rse-ops/lammps-matrix
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/rse-ops/lammps-matrix' target='_blank'>rse-ops/lammps-matrix</a>

<small>scheduler: save state of experiments

I spent a few days on this, and ultimately am abandoning this
approach to use lammps. I do not have it in me to debug 18 different
lammps installs on common clusters. It worked previously because
we could deploy the exact environment alongside lammps that
the container was built with (and thus it run). Trying to remove
that extra layer, and just run these on the base OS is a huge
undertaking that I have decided is too much anguish to do.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/rse-ops/lammps-matrix/commit/21866dd3f10c7187f8ed19c4ee2517eb8dc21ad3' target='_blank'>View Commit</a>