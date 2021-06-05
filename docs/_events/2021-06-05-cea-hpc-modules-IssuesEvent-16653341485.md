---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2021-06-05
repo_name: cea-hpc/modules
html_url: https://github.com/cea-hpc/modules/issues/400
repo_url: https://github.com/cea-hpc/modules
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> open issue <a href='https://github.com/cea-hpc/modules/issues/400' target='_blank'>cea-hpc/modules#400</a>.

<p>Module alias not found in GitHub Workflow</p><small>Hi modules team! I hope it's okay I'm posting here, I'd like to be able to link to a GitHub issue here and have it tracked in the PR. Basically, I have a PR: https://github.com/singularityhub/singularity-hpc/pull/373 that adds a test suite that installs and loads a module, and then uses one of the aliases. For some reason, I am always getting [command not found](https://github.com/singularityhub/singularity-hpc/pull/373/checks?check_run_id=2751238754). When I test the same series of commands in an actual cluster environment it works as expected, so I'm thinking that I'm perhaps forgetting to set some environment variable or similar so that the aliases are found? Note that I have two jobs that are failing in this manner - one that installs a singularity container module, and the other that installs a podman container module. I tried changing the syntax of the set-alias commands between the two just for testing, e.g.,...</small><a href='https://github.com/cea-hpc/modules/issues/400' target='_blank'>View Comment</a>