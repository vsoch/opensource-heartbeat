---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2022-08-30
repo_name: buildsi/splice-experiment-runs
html_url: https://github.com/buildsi/splice-experiment-runs/commit/61305b7066b83079373e44b85d38b7771e3b315b
repo_url: https://github.com/buildsi/splice-experiment-runs
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/buildsi/splice-experiment-runs' target='_blank'>buildsi/splice-experiment-runs</a>

<small>Add debuginfo flags for Fedora tests (#3)

* Fedora tests- only copy .so files from requested packages

Not everything in /lib or /lib64 has an associated .debug file. This
ensures we collect only the .so files we care about for testing.

* Fedora tests- unify local debug directories

When copying the debuginfo files, just plop them in the same local
directory while preserving the parent structure. Unlike with the .so
files, we don't care if we pick up extra .debug files as they won't
interfere with the tests.

* Fedora tests- set debuginfo directories for abi-lab and libabigail
* Fedora tests- generate debuginfo for all system libs

This ensures that anything in /lib{64} has a corresponding debuginfo
file and prevents errors when running the predictors.

* Fedora tests- use symlinks for debug directories

The upload-artifact action will follow symlinks, so there's no reason to
copy these files around. This will save a huge amount of disk space.

* Only copy .so files from /lib{64}

* Install complete debuginfo files after installing Fedora libs
This ensures we get .debug files for _all_ installed libraries.

* Create dirs and install install-debug before doing other install tasks
* Preserve full directory paths when making local copies of libraries
* Remove unwanted library files after install
This gets rid of text-ish files that will cause errors in the predictors.
* Use full paths for the DEBUGINFO_DIR env vars

Signed-off-by: vsoch <vsoch@users.noreply.github.com>
Co-authored-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/buildsi/splice-experiment-runs/commit/61305b7066b83079373e44b85d38b7771e3b315b' target='_blank'>View Commit</a>