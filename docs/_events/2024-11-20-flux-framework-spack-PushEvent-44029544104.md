---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-11-20
repo_name: flux-framework/spack
html_url: https://github.com/flux-framework/spack/commit/4f9aa6004b4324bc819fcb25f4ed9acaa6cf11bc
repo_url: https://github.com/flux-framework/spack
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/flux-framework/spack' target='_blank'>flux-framework/spack</a>

<small>visit: add v3.4.0, v3.4.1 (#47161)

* Visit: Add new versions 3.4.0 and 3.4.1

* Adios2: Restrict python, 3.11 doesn't not work for older Adios2

* VisIt: Set the VTK_VERSION for @3.4:

Older versions of VTK used the VTK_{MAJOR, MINOR}_VERSION variables for
VTK detection. VisIt >= 3.4 uses the full string VTK_VERSION.

* CI: Don't build llvm-amdgpu for non-HIP stack

* VisIt: v3.4.1 handles newer Adios2 correctly

* Visit: Add missing links in HDF5, set correct VTK version configuration parameter

* VisIt: Add py-pip requirement and patch visit with configuration changes

* HDF5 symlinks move when inside of callback

* VisIt ninja install fails with python module. Using make does not

* VisIt 3.4 has a high minimum cmake requirement

* HDF5: Early return when not mpi for mpi symlinks

* HDF5: Use platform agnostic method for creating legacy compatible MPI symlinks

* Fix VISIT_VTK_VERSION handling for 8.2.1a hack</small>

<a href='https://github.com/flux-framework/spack/commit/4f9aa6004b4324bc819fcb25f4ed9acaa6cf11bc' target='_blank'>View Commit</a>