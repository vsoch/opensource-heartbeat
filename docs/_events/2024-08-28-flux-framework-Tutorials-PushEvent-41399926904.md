---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-08-28
repo_name: flux-framework/Tutorials
html_url: https://github.com/flux-framework/Tutorials/commit/d90c83a23c6746c1f96c4316d7a7eee12e490528
repo_url: https://github.com/flux-framework/Tutorials
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/flux-framework/Tutorials' target='_blank'>flux-framework/Tutorials</a>

<small>HPCIC 2024: Updates and Fixes DYAD Component of Tutorial (#43)

* dyad: fixes content and DYAD data dyad data loader

This commit corrects logic in the the PyTorch data loader for DYAD.
It also makes various corrections to the text in the DYAD notebook.

* docker: adds workaround regarding Ubuntu Jammy

The flux-sched image for Ubuntu Jammy has a system install of
UCX 1.12.0. However, we are wanting to use UCX 1.13.1 with DYAD.
This commit updates LD_LIBRARY_PATH to point to UCX 1.13.1 to prevent
runtime issues with DYAD.

* dyad: updates the env file for DYAD notebook

In light of the name change of DLIO Profiler to DFTracer, this commit
updates the env file created in the DYAD notebook to use the new names
for environment variables.

* dyad: fixes bug in DYAD data loader

This commit fixes a bug in the DYAD PyTorch data loader
that causes 'brokers_per_node' to not be set before reference.

* dyad: update multiprocessing approach for DLIO

This commit tweaks the DLIO config file to use forking for
multiprocessing instead of spawning

* dyad: changes cpu-affinity for DLIO

This commit changes cpu-affinity to off when running DLIO for
training for consistency

---------

Co-authored-by: Hariharan <mani.hariharan@gmail.com></small>

<a href='https://github.com/flux-framework/Tutorials/commit/d90c83a23c6746c1f96c4316d7a7eee12e490528' target='_blank'>View Commit</a>