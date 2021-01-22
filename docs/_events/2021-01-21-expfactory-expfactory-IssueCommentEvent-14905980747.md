---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2021-01-21
repo_name: expfactory/expfactory
html_url: https://github.com/expfactory/expfactory/issues/136
repo_url: https://github.com/expfactory/expfactory
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/expfactory/expfactory/issues/136' target='_blank'>expfactory/expfactory#136</a>.

<small>Hmm, so the way that it works is that when you build your experiment container, internally everything is being served via [port 5000](https://github.com/expfactory/expfactory/blob/master/expfactory/templates/build/docker/Dockerfile.template#L41), which is then proxy-ed to [port 80](https://github.com/expfactory/expfactory/blob/4744a05232bc3dd2050e6b9de2bc82b3e11d961e/script/nginx.gunicorn.conf) (or the same for [https](https://github.com/expfactory/expfactory/blob/4744a05232bc3dd2050e6b9de2bc82b3e11d961e/script/nginx.https.conf)). So I suspect that if you want a different port used instead of 80, you'd need to change the nginx configuration there. It might be easiest to add a step to your Dockerfile to add a custom one [e.g., see this step](https://github.com/expfactory/expfactory/blob/25468f7ff1615144213909248ac8cd54ae5405a3/expfactory/templates/build/docker/Dockerfile.template#L21) and then make sure that you expose the port, and definitely keep all your files in version control so you can reproduce your build....</small>

<a href='https://github.com/expfactory/expfactory/issues/136' target='_blank'>View Comment</a>