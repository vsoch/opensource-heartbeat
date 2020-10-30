---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2020-10-29
repo_name: hpcng/singularity
html_url: https://github.com/hpcng/singularity/issues/3866
repo_url: https://github.com/hpcng/singularity
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/hpcng/singularity/issues/3866' target='_blank'>hpcng/singularity#3866</a>.

<small>Back in the day after the rate limits were added I had proposed creating user-specific tokens to more finely control access with @ArangoGutierrez, but I don't think there was a solid response from Sylabs so it was dropped. At this point I couldn't make the justification for the time, but my suggestion would be to make a repository on there just for Sylabs, make a bunch of busybox images, and then spread them over your testing so that it doesn't go over the weekly pull limit. You might consider just running the test on a merge to master so it's not frequent, and disabling in the PR tests....</small>

<a href='https://github.com/hpcng/singularity/issues/3866' target='_blank'>View Comment</a>