---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2022-12-29
repo_name: flux-framework/spack
html_url: https://github.com/flux-framework/spack/commit/e28738a01e3ae15ade768514c15a433538d69f2a
repo_url: https://github.com/flux-framework/spack
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/flux-framework/spack' target='_blank'>flux-framework/spack</a>

<small>bugfix: make texinfo build properly with gettext (#34312)

`texinfo` depends on `gettext`, and it builds a perl module that uses gettext via XS
module FFI. Unfortunately, the XS modules build asks perl to tell it what compiler to
use instead of respecting the one passed to configure.

Without this change, the build fails with this error:

```
parsetexi/api.c:33:10: fatal error: 'libintl.h' file not found
         ^~~~~~~~~~~
```

We need the gettext dependency and the spack wrappers to ensure XS builds properly.

- [x] Add needed `gettext` dependency to `texinfo`
- [x] Override XS compiler with `PERL_EXT_CC`

Co-authored-by: Paul Kuberry <pakuber@sandia.gov></small>

<a href='https://github.com/flux-framework/spack/commit/e28738a01e3ae15ade768514c15a433538d69f2a' target='_blank'>View Commit</a>