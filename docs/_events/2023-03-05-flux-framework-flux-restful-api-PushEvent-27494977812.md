---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2023-03-05
repo_name: flux-framework/flux-restful-api
html_url: https://github.com/flux-framework/flux-restful-api/commit/b1f280d47865149159399b4860d763453eaec521
repo_url: https://github.com/flux-framework/flux-restful-api
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/flux-framework/flux-restful-api' target='_blank'>flux-framework/flux-restful-api</a>

<small>total refactor to use database

I am not happy with the current multi-user setup that tries to use pam,
and still is not using good practices like oauth2/jwt tokens. I also
do not like the idea of maintaining two modes of operation - one through
a flux user and one via sudo running the server and launching jobs as the
user. Instead, I think the flux restful server should be in charge of
authenticating users, and using a local database that can be created
by an entity like the flux operator, and then a secret to encrypt all
communication. I have a lot of work to update tests, examples, and docs,
and then I need to test with the flux operator, but this should at least
be the start of the crux of work. Next I will work on fixing up the
Python client to do the proper back and forth for an oauth2 token.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/flux-framework/flux-restful-api/commit/b1f280d47865149159399b4860d763453eaec521' target='_blank'>View Commit</a>