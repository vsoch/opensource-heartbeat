---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2021-01-13
repo_name: singularityhub/sregistry
html_url: https://github.com/singularityhub/sregistry/issues/329
repo_url: https://github.com/singularityhub/sregistry
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/singularityhub/sregistry/issues/329' target='_blank'>singularityhub/sregistry#329</a>.

<small>I mean to shell into the uwsgi container, and then get an interactive python shell (`python manage.py shell`) and use the [minio.py](https://github.com/singularityhub/sregistry/blob/master/shub/apps/library/views/minio.py) file to create connections to the server (the minioClient and minioExternalClient) and then test different uses of it manually from the [images.py](https://github.com/singularityhub/sregistry/blob/master/shub/apps/library/views/images.py) file. You will likely trigger that same error, and you should debug from there. But first you should test the basic networking, because if it's an issue with docker-compose not allowing the containers to see one another, that's one level up and should be addressed first. I'm telling you exactly how I would debug this if it was sitting in front of me....</small>

<a href='https://github.com/singularityhub/sregistry/issues/329' target='_blank'>View Comment</a>