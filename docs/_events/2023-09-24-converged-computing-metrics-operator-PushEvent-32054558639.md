---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-09-24
repo_name: converged-computing/metrics-operator
html_url: https://github.com/converged-computing/metrics-operator/commit/67ad62f7190cb9c0a380eeae4a15c5c3e5fd869e
repo_url: https://github.com/converged-computing/metrics-operator
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/converged-computing/metrics-operator' target='_blank'>converged-computing/metrics-operator</a>

<small>[wip] second design for metrics operator (#63)

* WIP to refactor

This is going to be a huge refactor to remove the application/storage "hard coded"
legos replaced by a more flexible setup where we have one base metric set (no
subtypes) and then metrics generate the replicated jobs (as many as they like, how
they please) and then addons are provided to them, which can range from additional
volumes to containers (that provide volumes) to any kind of customization. This
is not ready for any kind of testing but I am mostly concerned about my computer
blowing up and losing the work so I am saving for good measure :) Also, yay today! :D


* definitely making bad life decisions
* very satisfying deletion of things.
* lammps ran!
* amg is back
* bdas is back
* add back hpl

we did not get this completely working before (likely
the spack mpi install as a basic hostname does not work
) so a basic conversion is sufficient

* add back kripke
* laghos
* test signing again
* add back nekbone
* add back pennant
* add back quicksilver

also simplify logic of applications - the launcher worker
pattern is generic and can be shared

* workflow format bug
* add back fio
* add back host volume example
* add back ior
* add back osu benchmarks!
* add back chatterbug

it is accepted this does not fully work, we need to
come back to it.

* add back netmark
* systat and lammps working again
* hpctoolkit design at least works

but shared libraries are failing to load. HPCToolkit
you are a jerk. I am laughing. And crying. And mostly
crying.

* clean up docs a little bit
* addon documentation is good
* hopefully fix bug
* fixing workingdir bug!
* update to v1alpha2
* bugfix
* a single touch marker at the end of the copy is more reliable than a file that is part of it!
* support to customize container for any metric, and for hpctoolkit to run post commands
* support for custom container
* add print at end of post analysis for hpctoolkit
* fixing bug with internal crd state

if we do not make a copy (refect) of the interface,
the state seems to change (and perist) between runs. While
I am still worried about this design, this at least seems
to fix that bug. I am also wondering about garbage collection
(e.g., if making the copies means they stay around and the
operator will use increasing memory) but that is TBA
explored.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/converged-computing/metrics-operator/commit/67ad62f7190cb9c0a380eeae4a15c5c3e5fd869e' target='_blank'>View Commit</a>