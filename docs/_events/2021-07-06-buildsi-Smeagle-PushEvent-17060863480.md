---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2021-07-06
repo_name: buildsi/Smeagle
html_url: https://github.com/buildsi/Smeagle/commit/6c07fc477d7fe7e382f53a23f72f41cf9f6c71c5
repo_url: https://github.com/buildsi/Smeagle
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/buildsi/Smeagle' target='_blank'>buildsi/Smeagle</a>

<small>Use Dyninst for x86_64 classification of types (#34)

* Refactor getRegisterClassFromType to use Dyninst for type processing
This also adds a first-pass at handling some cases for vectors of
floating point types.

* Fix comment
* Add placeholders for classifying types other than scalars
* Tidy up includes in allocators.hpp
* Merge getRegisterString and getRegistersString
This also expands vector register handling.
* Use the new interfaces for classification and allocation.
* Remove unused variables in parse_parameters
* Use exact name matching in get_one
Also, don't copy and edit the vector- just return the found function.
* Generate test cases programmatically

This will allow us to more easily expand test cases later when we add
pointers, references, aggregate types, and multiple parameters per
function. Also, change the test function linkages to C-style so that
exact name matching can be done instead of the broken pattern matching
that was done previously in `get_one`.

* Rename `Class` to `classification`
* Combine the x87 register allocation checks
* Use dyninst master for build in main.yaml
* Use dyninst master for style tests
* Use dyninst master for docs tests

Co-authored-by: Vanessasaurus <814322+vsoch@users.noreply.github.com></small>

<a href='https://github.com/buildsi/Smeagle/commit/6c07fc477d7fe7e382f53a23f72f41cf9f6c71c5' target='_blank'>View Commit</a>