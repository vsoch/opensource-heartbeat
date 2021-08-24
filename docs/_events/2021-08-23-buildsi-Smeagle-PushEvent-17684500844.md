---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2021-08-23
repo_name: buildsi/Smeagle
html_url: https://github.com/buildsi/Smeagle/commit/7110eb115019733cd562de1ad8014bd2dbe6ec49
repo_url: https://github.com/buildsi/Smeagle
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/buildsi/Smeagle' target='_blank'>buildsi/Smeagle</a>

<small>Start of work to check for pointer in makeJson. (#64)

* start of work to check for pointer in makeJson.
There is one bug about not finding the correct function in the namespace to discuss!
* adding changes
* adding pointers (but now json seems to not be loadable file is so big? process was killed
* Make struct_t::toJson(std::ostream, int, recursive_t) const
This should always have been the case. Mea culpa!
* Make pointer_t::toJson variadic
This allows us to pass the underlying_type's respective recursive_t
through.
* In makeJson, pass resuriveness through for struct_t
* Make union_t::toJson(std::ostream,int,recursive_t) const
* FIX: In makeJson, pass resuriveness through for union_t
* quick formatting, works!

Signed-off-by: vsoch <vsoch@users.noreply.github.com>

Co-authored-by: vsoch <vsoch@users.noreply.github.com>
Co-authored-by: Tim Haines <thaines@cs.wisc.edu></small>

<a href='https://github.com/buildsi/Smeagle/commit/7110eb115019733cd562de1ad8014bd2dbe6ec49' target='_blank'>View Commit</a>