---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2022-06-22
repo_name: singularityhub/singularity-hpc
html_url: https://github.com/singularityhub/singularity-hpc/commit/d1d1f74a42f711938f44b9a9ccd54bd07dc1fe51
repo_url: https://github.com/singularityhub/singularity-hpc
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/singularityhub/singularity-hpc' target='_blank'>singularityhub/singularity-hpc</a>

<small>Various wrapper scripts improvement (#548)

* Defines the constructor arguments just once
* Factored out the shell method as it is almost the same between both container technologies
* The DockerContainer doesn't need to know about its subclass any more
* Stop forbidding templates from being named podman.sh
Only use WrapperScript - no more subclasses.
* WrapperScript objects don't have the wrapper_template attribute anymore
* Merged the three generation methods of WrapperScript into one
* Rewrote the template search
- Don't restrict user-defined global templates to be named singularity.sh or
  docker.sh as in shpc's default template directory
- Properly defined the search path based on all available template directories
- Minor bugfix: do not search the templates in the current working directory

* Allow using a custom template for aliases

* Turned get_shell_path to a property

Co-authored-by: Matthieu Muffato <mm49@sanger.ac.uk>

* Allow defining the alternative template script in a long form option rather than hijacking the singularity_scripts section

* Ensure that the wrapper is always defined
* Extracted a function that checks the wrapper exists
and returns where to find it

* Updated the docs to reflect the current wait templates are rendered
* Not used anywhere, so no need to make it a class variable
* Reinstated wrapper_template as a (mandatory) constructor argument
* Further refactoring to split the function that establishes the search path, from the one that finds the template file
* Added a test for the two new methods of WrapperScript
* Fixed the comment
* Pass the config as a kwarg so that we don't need to pass None for the container
* Applied black</small>

<a href='https://github.com/singularityhub/singularity-hpc/commit/d1d1f74a42f711938f44b9a9ccd54bd07dc1fe51' target='_blank'>View Commit</a>