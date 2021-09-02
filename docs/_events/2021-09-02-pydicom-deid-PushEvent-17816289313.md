---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2021-09-02
repo_name: pydicom/deid
html_url: https://github.com/pydicom/deid/commit/39d8e019c1d3c85047a2c5a20b514d141d6e8535
repo_url: https://github.com/pydicom/deid
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/pydicom/deid' target='_blank'>pydicom/deid</a>

<small>This will add support to read and manipulate file meta

Remaining questions:
1. Do file meta fields overlap with fields in the dicom? If so, we need to be checking each field if it is a filemeta or not before replace. As implemented now, the fields are parsing over equivalently and it is assumed that file meta fields do not appear in the dicom and vice versa.
2. Do we need to make any special changes to the file meta, e.g., perhaps the size? I have never manipulated it before, and I am hoping that pydicom save handles these changes, but if not we should do it manually.

Signed-off-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/pydicom/deid/commit/39d8e019c1d3c85047a2c5a20b514d141d6e8535' target='_blank'>View Commit</a>