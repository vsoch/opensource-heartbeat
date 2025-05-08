---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2025-05-07
repo_name: flux-framework/spack
html_url: https://github.com/flux-framework/spack/commit/2c05ce3607bb346897c24a7d0486c08de1f7fea9
repo_url: https://github.com/flux-framework/spack
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/flux-framework/spack' target='_blank'>flux-framework/spack</a>

<small>binary_distribution: content addressable tarballs (#48713)

binary_distribution: content addressable url buildcache

Change how binary mirrors are laid out, adopting content addressing for every
piece of data spack stores in a binary mirror. Items (e.g. tarballs, specfiles, public
keys, indices, etc) are now discoverable via manifest files which give the size,
checksum, compression type, etc of the the stored item. The information in the
manifest, in turn, is used to find the actual data, which is stored by its content
address in the blobs directory. Additionally, signing is now applied to the manifest
files, rather than to the spec files themselves.</small>

<a href='https://github.com/flux-framework/spack/commit/2c05ce3607bb346897c24a7d0486c08de1f7fea9' target='_blank'>View Commit</a>