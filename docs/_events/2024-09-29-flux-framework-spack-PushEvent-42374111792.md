---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-09-29
repo_name: flux-framework/spack
html_url: https://github.com/flux-framework/spack/commit/2613a14c43b11ab92181bdd7ba57cd5b99f128a8
repo_url: https://github.com/flux-framework/spack
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/flux-framework/spack' target='_blank'>flux-framework/spack</a>

<small>`cc`: ensure that RPATHs passed to linker are unique

macOS Sequoia's linker will complain if RPATHs on the CLI are specified more than once.
To avoid errors due to this, make `cc` only append unique RPATHs to the final args list.

This required a few improvements to the logic in `cc`:

1. List functions in `cc` didn't have any way to append unique elements to a list. Add a
   `contains()` shell function that works like our other list functions. Use it to implement
   an optional `"unique"` argument to `append()` and an `extend_unique()`. Use that to add
   RPATHs to the `args_list`.

2. In the pure `ld` case, we weren't actually parsing `RPATH` arguments separately as we
   do for `ccld`. Fix this by adding *another* nested case statement for raw `RPATH`
   parsing. There are now 3 places where we deal with `-rpath` and friends, but I don't
   see a great way to unify them, as `-Wl,`, `-Xlinker`, and raw `-rpath` arguments are
   all ever so slightly different.

3. Fix ordering of assertions to make `pytest` diffs more intelligible. The meaning of
   `+` and `-` in diffs changed in `pytest` 6.0 and the "preferred" order for assertions
   became `assert actual == expected` instead of the other way around.

Signed-off-by: Todd Gamblin <tgamblin@llnl.gov></small>

<a href='https://github.com/flux-framework/spack/commit/2613a14c43b11ab92181bdd7ba57cd5b99f128a8' target='_blank'>View Commit</a>