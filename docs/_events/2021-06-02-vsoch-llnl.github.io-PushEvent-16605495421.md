---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2021-06-02
repo_name: vsoch/llnl.github.io
html_url: https://github.com/vsoch/llnl.github.io/commit/184da5f398f8115de8a88cb06f626ddf0dc72ebb
repo_url: https://github.com/vsoch/llnl.github.io
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/vsoch/llnl.github.io' target='_blank'>vsoch/llnl.github.io</a>

<small>updating organization and navigation of site

**pages** are now all represented under the "pages" directory. Browsing the site as a new developer, it was a bit confusing to try and distinguish data from collections from other content. By placing all website pages under pages, I know where to look for it, and the organization reflects nesting on the site.

**search/explore vs. visualize** The current "explore" button threw me off because I always expected the browser / search view. I have changed this link to be Visualize, and the search view at the top is "browse projects," which I suspect some people will jump to immediately.

**RADIUSS** is really about policy and guidelines. It was presented on the site as a heading, and I do not think a visitor to the site that is not familiar with the lab will really understand what it is, and why it is there. I also found that showing another "search" or "browse" interface under RADIUSS was confusing. What made sense was to remove this redundant view, and then move radius to be under about, and specifically under the heading of "Policy and Guidelines." That is exactly what RADIUSS is to some of these projects, and it makes sense to put it there in context of the site. Now if there does need to be someting to distinguish radiuss from non RADIUSS projects we could do a badge or something. but with this refactor, it is not confusing to have more than one search view, and RADIUSS is better understood in context of the site.

**spelling** I am loving this action to check spelling on PRs - it shows the developer any spelling errors to fix! It can be run locally like a linted to fix spelling errors too. I have added notes to the READMe about using it.

**preview** we need a good way to preview the site when there are changes! I have added a Circle build that has worked well for me across many sites, someone with super admin powers will need to connect the repository!

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/vsoch/llnl.github.io/commit/184da5f398f8115de8a88cb06f626ddf0dc72ebb' target='_blank'>View Commit</a>