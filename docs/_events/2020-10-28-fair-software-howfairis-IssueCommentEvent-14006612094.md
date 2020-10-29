---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2020-10-28
repo_name: fair-software/howfairis
html_url: https://github.com/fair-software/howfairis/issues/47
repo_url: https://github.com/fair-software/howfairis
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/fair-software/howfairis/issues/47' target='_blank'>fair-software/howfairis#47</a>.

<small>The use case that I have in mind is this one https://rseng.github.io/rseng/software/howfairis#why-is-it-useful, or any general need to import and run the function (and the sys.exit is unexpected). If you need the client to exit for [these tests](https://github.com/fair-software/howfairis/blob/master/clitests/script.sh). For the non zero exits, it would be okay to exit there (some raise errors and pass up to calling function, but an exit isn't a crazy idea). But for [this exit](https://github.com/fair-software/howfairis/blob/master/howfairis/cli.py#L46) where the client is successful, it would kill two birds with one stone to put it [here](https://github.com/fair-software/howfairis/blob/master/howfairis/cli.py#L107), that way the exit happens for the client but the function is usable outside of it....</small>

<a href='https://github.com/fair-software/howfairis/issues/47' target='_blank'>View Comment</a>