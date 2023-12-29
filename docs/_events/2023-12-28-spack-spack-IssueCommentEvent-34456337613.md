---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-12-28
repo_name: spack/spack
html_url: https://github.com/spack/spack/issues/38037
repo_url: https://github.com/spack/spack
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/spack/spack/issues/38037' target='_blank'>spack/spack#38037</a>.

<small>I didn't ever figure out specific details - with spack things mysteriously break and then resolve later and that's what happened for this case. The only suggestion I can make is to look at libarchive (e.g., commit from May that mentions iconv, maybe that's when it showed up https://github.com/spack/spack/commits/develop/var/spack/repos/builtin/packages/libarchive) and then check your package.py for flux-core - do you have at least this one? https://github.com/spack/spack/commit/10999c02836fa6a510871d24ad6548d12d2b72ae....</small>

<a href='https://github.com/spack/spack/issues/38037' target='_blank'>View Comment</a>