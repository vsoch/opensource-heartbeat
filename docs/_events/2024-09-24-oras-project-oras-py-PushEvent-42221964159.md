---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-09-24
repo_name: oras-project/oras-py
html_url: https://github.com/oras-project/oras-py/commit/81c4b04f7b1993602771946ef31f33a34a3e86e8
repo_url: https://github.com/oras-project/oras-py
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/oras-project/oras-py' target='_blank'>oras-project/oras-py</a>

<small>core: improve anon/auth token logic (#148)

* core: TokenAuth request_token fix missing auth

the method is intended to request authenticated
token, per pydocs, but was passing an headers
which was always missing Authorization.

* core: use token in auth in subsequent requests

if a token was saved in auth,
it shall be used in subsequent requests.

This avoid a situation where:
to upload a blob, first is done anonymously, then
retry with token
then upload a manifest, avoid the attempt to upload
anonymously if a token was present in the previous
flow

* core: if 401 on 2nd attempt, avoid anon tokens

in the first flow using auth backend for token:
1. try do_request with no auths at all
2. the attempt to gain an anon token is success,
but then the request fails with 401
3. at this point, in the third attempt, give
chance to the flow to request a token but avoid
any anon tokens.

Please note: this happens effectively only on the
first run of the flow. Subsequent do_request flow
invocations should just succeed now on the 1st
request by re-using the token --simplified
behaviour introduced with this proposal

* guard as headers is Optional
* implement review request

* Revert "implement review request"

This reverts commit 102381c5c4ae0fdf45c8a4dd26ae1765eae9b029.
This reverts commit 1e891d2bfebe4b6520a1fe6902159198c8799d62.
This reverts commit 6e226672c60184cd43b6532f5a910acbf9d064ea.

this was taken care in https://github.com/oras-project/oras-py/pull/153

This reverts commit 10e010b365e56488963ca14b6e9e08b1ea7e4a7a.

* implement review comment about anon/req token

from: https://github.com/oras-project/oras-py/pull/148#discussion_r1677018164

> And if the basic auth is there, skip over asking for an anon token

as it stands, in case the basic auth are present,
these are exchanged for the request token.

Signed-off-by: tarilabs <matteo.mortari@gmail.com>

---------

Signed-off-by: tarilabs <matteo.mortari@gmail.com></small>

<a href='https://github.com/oras-project/oras-py/commit/81c4b04f7b1993602771946ef31f33a34a3e86e8' target='_blank'>View Commit</a>