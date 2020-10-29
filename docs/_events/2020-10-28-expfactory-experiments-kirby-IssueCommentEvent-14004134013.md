---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2020-10-28
repo_name: expfactory-experiments/kirby
html_url: https://github.com/expfactory-experiments/kirby/issues/1
repo_url: https://github.com/expfactory-experiments/kirby
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/expfactory-experiments/kirby/issues/1' target='_blank'>expfactory-experiments/kirby#1</a>.

<small>Hey @tfeige91 ! Let's start with the issue in the browser. I tested for Firefox (no errors in the console) and then Chrome (I reproduced your issues) and for the latter, regardless of the error it seemed to function without issue. So, a first option is just to use Firefox, or be okay with having the messages in the console with Chrome. If you want to take a shot at fixing chrome, likely we just need to try following the instructions and reloading the audio context (see here https://developers.google.com/web/updates/2017/09/autoplay-policy-changes#webaudio) but then you'd need to check for the browser being used and make sure it's chrome. The last errors appear to be missing .map files, which could easily be added to the repository! Do you want to try some of these out and do a PR to the repository? I'd be happy to add any fixes....</small>

<a href='https://github.com/expfactory-experiments/kirby/issues/1' target='_blank'>View Comment</a>