---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2025-05-12
repo_name: DLR-AMR/t8code
html_url: https://github.com/DLR-AMR/t8code/issues/1615
repo_url: https://github.com/DLR-AMR/t8code
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/DLR-AMR/t8code/issues/1615' target='_blank'>DLR-AMR/t8code#1615</a>.

<small>Thanks @Davknapp ! I can definitely try again, although I don't have many ideas, at least at the moment. We run these with the flux operator, which is deploying flux framework (an HPC workload manager and scheduler) within a closed space of pods in a Kubernetes cluster, so that means (depending on the cloud) we can use networks like Infiniband (Azure) and EFA (AWS), and the performance isn't bad. For this set of tests we are in Google Cloud, which unfortunately is just optimized ethernet (they call it "Titanium" and the details aren't revealed), but I've run over 25 applications and (at least for small sizes) they scale generally OK up until about 64 nodes. ...</small>

<a href='https://github.com/DLR-AMR/t8code/issues/1615' target='_blank'>View Comment</a>