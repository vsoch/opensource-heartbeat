---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2022-12-22
repo_name: flux-framework/flux-operator
html_url: https://github.com/flux-framework/flux-operator/commit/073b4efe9bf02472b17fc8c891d642c1231cdcfd
repo_url: https://github.com/flux-framework/flux-operator
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/flux-framework/flux-operator' target='_blank'>flux-framework/flux-operator</a>

<small>add support for flux option flags (#49)

* First testing workflows added for unit tests (not fully written yet) and headless workflow tests.
  A headless workflow test means that we can add a file to examples/tests and then automate
  running it with a simple script. The GitHub CI can now start the minicluster, install the operator,
  and then manage apply the configs to it and shutting down.
* testing workflows include laamps, hello-world, and a pokemon workflow
* template wait.sh now is properly rendered with named variables instead of string formatting
* testing workflow attempts to cache go deps to (hopefully) not go over ratelimits. We might need
  additional caching - TBA.
* Addition of TestMode, SleepTime, and FluxRestful.Branch to CRD. The test mode silences all
  output except for the job, SleepTime allows the user to control that, and branch is for the
  Flux Restful API (if being used).
* Support for PreCommand in the CRD! This is huge because it allows for more fined tuning of
  running logic in the wait.sh script. E.g., to source an environment or modify the command to
  run things as the flux user with sudo.
* wait script and associated logic is moved to the level of the container. The reason is because we
  eventually might want custom logic associated with each container, and this means rendering from
  different sources.
* clear definition of rules needed for a valid running container in the docs here, and we now require
  sudo to be installed along with flux, and better control creating the flux user, and using the correct
  id if the user is already created.
* add support for flux option flags
* ensure we do not erase existing flags in the container
* entire addition of examples/flux-restful and examples/tests folders that we can provide to the user base, and
  ensure they continue working with tests. I'd like to eventually turn this into a gallery
* entire new docs section that explain running these examples, and the tests.
* testing scripts associated with the above to clean the namespace, run the operator, apply the example,
   wait for output, compare output with expected, and check return codes of the job containers.

this adds support for fluxOptionFlags to be defined on the level
of the cluster. We check if the variable is defined, and if not,
we do not attempt to export in the environment, as the base container
might already specify a preference. To test this fully I am waiting
for the osu benchmarks container to build, and then I can test it
here with an example workflow.

* updates so precommand and flux option args are on the level of the container

this has been tested with and without option args and seems
to work for both! We are also using more proper templating
in go instead of what I was doing before. Next I need to be
able to write tests to ensure these workflos do not break.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/flux-framework/flux-operator/commit/073b4efe9bf02472b17fc8c891d642c1231cdcfd' target='_blank'>View Commit</a>