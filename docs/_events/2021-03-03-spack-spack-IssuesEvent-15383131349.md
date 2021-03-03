---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2021-03-03
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/22052
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> open issue <a href='https://github.com/spack/spack/issues/22052' target='_blank'>spack/spack#22052</a>.

<p>Proposal: add release: key to spack.yaml</p><small>I'm having discussion with @alecbcs,  and we think it would be really useful to have a release key (or support for custom metadata) in a spack.yaml file. You can follow our discussion [here](https://github.com/autamus/spacktainer-registry/pull/2#issuecomment-789367605), but basically if we are building containers from spack.yaml files, we'd want to bump the version in the spack.yaml file. We could easily add the key (and likely there wouldn't be an issue if spack doesn't validate the structure and not allow extra keys, I know spack uses jsonschema which is why I'm asking specifically) but in the case that it could be useful to other users, I thought I'd open it up here....</small><a href='https://github.com/spack/spack/issues/22052' target='_blank'>View Comment</a>