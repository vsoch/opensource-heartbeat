---
event_type: IssuesEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2020-11-03
repo_name: opencontainers/distribution-spec
html_url: https://github.com/opencontainers/distribution-spec/issues/210
repo_url: https://github.com/opencontainers/distribution-spec
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> open issue <a href='https://github.com/opencontainers/distribution-spec/issues/210' target='_blank'>opencontainers/distribution-spec#210</a>.

<p>Wrapper around s3 multipart upload protocol</p><small>Has anyone given thought for how OCI could (easily? with some work?) be implemented to work alongside an s3 multipart upload compatible storage? For example, Minio is a good testing ground https://github.com/minio/minio/issues/10813. The creation of the request is fairly straight forward, but then the request to upload a part (akin to the PATCH for a chunk) is quite different. https://awscli.amazonaws.com/v2/documentation/api/latest/reference/s3api/upload-part.html. I was thinking that it would be really useful to be able to implement the distribution spec alongside this one, but the challenge of course are the differences. The server could act as some receiver of the requests, parsing them and forwarding then to Minio (or the s3 compatible storage) but this is problematic in that it puts huge load on that server, which we don't want to do....</small><a href='https://github.com/opencontainers/distribution-spec/issues/210' target='_blank'>View Comment</a>