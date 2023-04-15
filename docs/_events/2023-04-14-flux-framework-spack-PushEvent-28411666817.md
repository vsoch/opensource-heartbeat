---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-04-14
repo_name: flux-framework/spack
html_url: https://github.com/flux-framework/spack/commit/87dca0130c489f407f4fed90ab0298222067e81c
repo_url: https://github.com/flux-framework/spack
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/flux-framework/spack' target='_blank'>flux-framework/spack</a>

<small>(py-)onnx: new version 1.13.0, 1.13.1 (for py-torch@2)  (#36797)

* (py-)onnx: new version 1.13.0, 1.13.1 (for py-torch@2)

ONNX has a new version 1.13.1 which is required for py-torch +onnx_ml.
This version adds python 3.11 support, Mac M1/M2 support. No build
system changes changes.

- https://github.com/onnx/onnx/releases/tag/v1.13.0 (main changes)
- https://github.com/onnx/onnx/releases/tag/v1.13.1 (bugfixes)
- https://github.com/onnx/onnx/commits/main/CMakeLists.txt (top 6
  commits are on top of the last 1.12 release)
- https://github.com/onnx/onnx/blob/v1.13.1/requirements.txt
- https://github.com/onnx/onnx/blob/v1.13.1/requirements-release.txt

* py-onnx: update dependencies

* Apply suggestions from code review

Co-authored-by: Adam J. Stewart <ajstewart426@gmail.com>

* protobuf: new version 3.22.2, depends_on abseil-cpp

* onnx: require c++14 for protobuf

* py-protobuf: new preferred version 3.20.3

* protobuf: new versions 3.20.2, 3.20.3

* [@spackbot] updating style on behalf of wdconinc

* protobuf: no double depends_on abseil-cpp

* py-protobuf: no preferred 3.20.3

---------

Co-authored-by: Adam J. Stewart <ajstewart426@gmail.com>
Co-authored-by: wdconinc <wdconinc@users.noreply.github.com></small>

<a href='https://github.com/flux-framework/spack/commit/87dca0130c489f407f4fed90ab0298222067e81c' target='_blank'>View Commit</a>