---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2021-02-22
repo_name: singularityhub/sregistry
html_url: https://github.com/singularityhub/sregistry/pull/349
repo_url: https://github.com/singularityhub/sregistry
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/singularityhub/sregistry/pull/349' target='_blank'>singularityhub/sregistry#349</a>.

<small>Let's step back here for a second. You're asking to add an endpoint to Singularity Registry Server that doesn't actually work as expected - and only so you don't have to modify your current scripts. I'm not sure this is a reasonable request, and I'd suggest that we step back and look at the information that you need, which seems to be data for a collection. My suggestion is to add a try/except to your script, that on a 404 (or other) response to create the container, you instead do a request to get metadata about the collection (which seems to be what you are looking for). I'm happy to help you think through this....</small>

<a href='https://github.com/singularityhub/sregistry/pull/349' target='_blank'>View Comment</a>