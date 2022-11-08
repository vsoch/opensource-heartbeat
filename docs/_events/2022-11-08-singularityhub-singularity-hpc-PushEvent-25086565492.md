---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2022-11-08
repo_name: singularityhub/singularity-hpc
html_url: https://github.com/singularityhub/singularity-hpc/commit/d059bf9e34744497d42a16f5139becbd341ec8a6
repo_url: https://github.com/singularityhub/singularity-hpc
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/singularityhub/singularity-hpc' target='_blank'>singularityhub/singularity-hpc</a>

<small>Support accessing remote registries via ssh (#589)

* Support accessing remote registries via ssh
* Factored out a function that tells whether a registry path is local
* Make sure the URL is used, not self.source which could be a local path

The URL has to be given as "ssh://[user@]host.xz[:port]/path/to/repo.git"
rather than the shorter version "[user@]host.xz:path/to/repo.git"

* Make self.source include the subdir from the start. Allows implementing iter_modules in the base class
* The check already happens in _update_cache()
* Moved is_path_local to shpc.utils
* Added a safeguard to prevent cloning multiple times
* clone() is actually only supported by VersionControl
* No need to yield self.source in iter_modules since it's constant and accessible from outside (and not all callers want it !)
* It's more practical to yield the the registry object (provider) rather than using the "source" path (which is undefined for remote registries anyway)
* Optimised the "update all" mode by directly using Result objects from the registries. Otherwise, it wastes time finding modules that we know are there
* Clones only ever exist within a function
* Optimised iter_modules method for remote registries (using the cache)
* Moved back iter_modules to Filesystem since VersionControl has its own, optimised, version
* Stopped using self.source in VersionControl, to avoid confusion with Filesystem
* url, not source, is to be used for remote registries
* Cannot do these heuristics as we need to report unexisting local paths
* str.split can limit the number of splits
* The main Registry object, not the settings, should decide whether there is a local registry or not
* To avoid duplicating the code that assesses whether a path or local or not, check which sub-class of Provider is used
* The parent class shouldn't know that much about the subclasses
* Restored back the automatic addition of https://
* Restructured to avoid an unnecessary else
* shpc convention: no else when the then ends with a return
* Unnecessary due to operator precedence rule
* Added a cache in `library_url`
* Fixed the implementation of the cache in VersionControl.exists
* exists has its own implementation in VersionControl, so this implementation is in fact specific to Filesystem
* iter_registry is basically iter_modules with an extra filter
* Yield relative paths rather than full paths since *all* consumers need relative paths
* Proper method to cleanup a clone
* Removed a cleanup() call that was expected to do nothing
* Increased the symmetry to simplify the maintainability
* NotImplementedError is more useful than pass
* The tuplized version is not the preference here
* Easier to understand
* Made the clone return a Filesystem object independent from VersionControl
* Extra comment
* Back to a subclass of VersionControl for each forge
* Pre-parse the URL
* VersionControl should not be directly used
* Renamed the variable for clarity
* Removing yaml because it's the only file we have for a container
* Defensive programming: local could still be None
* bugfix: iter_modules needs to yield paths to container.yaml
* Moved the cleanup call up to _sync()
* bugfix: iter_modules now returns path to the container.yaml
* Need to check here too that the clone still exists
* Also need to reset self._clone if the directory is gone
* More checks on local and remote
* The temp directory may have been deleted in the meantime
* It makes more sense to cleanup tmplocal than self, and it works because self expects the cleanup may happen
* Moved this to the parent class
* Another implementation that doesn't make it too obvious the base-class knows about GitHub and GitLab
* Silly typo: self._clone is a Filesystem object, not a string
* No colon
* You shall use American spelling
* Added a test to showcase ssh

* Revert "bugfix: iter_modules needs to yield paths to container.yaml"

This reverts commit f069f4814454f6b6d5463faec06d373dbeb1124f.

* Revert "bugfix: iter_modules now returns path to the container.yaml"

This reverts commit c5b4cb99464784827477a927f1cd168d2af9b900.</small>

<a href='https://github.com/singularityhub/singularity-hpc/commit/d059bf9e34744497d42a16f5139becbd341ec8a6' target='_blank'>View Commit</a>