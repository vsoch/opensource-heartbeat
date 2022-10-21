---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2022-10-20
repo_name: expfactory/expfactory
html_url: https://github.com/expfactory/expfactory/pull/171
repo_url: https://github.com/expfactory/expfactory
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/expfactory/expfactory/pull/171' target='_blank'>expfactory/expfactory#171</a>.

<small>Gotcha. So doing a universal "os.path.abspath" across every path in the project isn't an ideal solution, especially when it's a random set of changes you haven't tested. Let's start with a fix just to the file where the issue is, and then I'd also suggest changing the hard coded paths in the client install.py to be os.path.join instead of forcing to be a slash, and then we can go from there! Also please bump the patch version and add a corresponding note in the CHANGELOG. Thanks!...</small>

<a href='https://github.com/expfactory/expfactory/pull/171' target='_blank'>View Comment</a>