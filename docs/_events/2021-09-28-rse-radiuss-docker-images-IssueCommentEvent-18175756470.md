---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2021-09-28
repo_name: rse-radiuss/docker-images
html_url: https://github.com/rse-radiuss/docker-images/pull/27
repo_url: https://github.com/rse-radiuss/docker-images
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/rse-radiuss/docker-images/pull/27' target='_blank'>rse-radiuss/docker-images#27</a>.

<small>So there is a subtle distinction that I don't want to lose - right now having a pre-determined matrix and letting uptodate generate it are mutually exclusive - you can only have one or the other. This is done because if the user provides "matrix" - we can still have build args, but we filter them down to only include those in the matrix. and we don't run the function to generate the permutations-based one. And if there is no matrix, then there is not filter and we run that function. So I don't see an easy way to maintain that AND allow "merge" of matrices. The most straight forward thing to do is add a (sort of redundant) includes section for extra build args, and it would only be parsed in context of not having a matrix. Is there something we could call that to make it clear? If you are interested in the function it's here (and you can see how it's one or the other) https://github.com/vsoch/uptodate/blob/badb065ccad7d797c153c0fb9e33d79951db655e/parsers/docker/build.go#L276...</small>

<a href='https://github.com/rse-radiuss/docker-images/pull/27' target='_blank'>View Comment</a>