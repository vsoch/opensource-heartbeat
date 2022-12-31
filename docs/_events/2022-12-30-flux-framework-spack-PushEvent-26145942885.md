---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2022-12-30
repo_name: flux-framework/spack
html_url: https://github.com/flux-framework/spack/commit/3a0db729c7fc0def2ac58c7c487cd43d5578ba78
repo_url: https://github.com/flux-framework/spack
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/flux-framework/spack' target='_blank'>flux-framework/spack</a>

<small>docs: avoid errors by using type hints instead of doc types (#34707)

There are a number of places in our docstrings where we write "list of X" as the type, even though napoleon doesn't actually support this. It ends up causing warnings when generating docs.

Now that we require Python 3, we don't have to rely on type hints in docs -- we can just use Python type hints and omit the types of args and return values from docstrings.

We should probably do this for all types in docstrings eventually, but this PR focuses on the ones that generate warnings during doc builds.

Some `mypy` annoyances we should consider in the future:
1. Adding some of these type annotations gets you:
    ```
    note: By default the bodies of untyped functions are not checked, consider using --check-untyped-defs  [annotation-unchecked]
    ```
   because they are in unannotated functions (like constructors where we don't really need any annotations).
   You can silence these with `disable_error_code = "annotation-unchecked"` in `pyproject.toml`
2. Right now we support running `mypy` in Python `3.6`.  That means we have to support `mypy` `.971`, which does not support `disable_error_code = "annotation-unchecked"`, so I just filter `[annotation-unchecked]` lines out in `spack style`.
3. I would rather just turn on `check_untyped_defs` and get more `mypy` coverage everywhere, but that will require about 1,000 fixes.  We should probably do that eventually.
4. We could also consider only running `mypy` on newer python versions.  This is not easy to do while supporting `3.6`, because you have to use `if TYPE_CHECKING` for a lot of things to ensure that 3.6 still parses correctly.  If we only supported `3.7` and above we could use [`from __future__ import annotations`](https://mypy.readthedocs.io/en/stable/runtime_troubles.html#future-annotations-import-pep-563), but we have to support 3.6 for now. Sigh.

- [x] Convert a number of docstring types to Python type hints
- [x] Get rid of "list of" wherever it appears</small>

<a href='https://github.com/flux-framework/spack/commit/3a0db729c7fc0def2ac58c7c487cd43d5578ba78' target='_blank'>View Commit</a>