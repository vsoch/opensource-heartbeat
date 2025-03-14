---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2025-03-13
repo_name: pydicom/deid
html_url: https://github.com/pydicom/deid/issues/274
repo_url: https://github.com/pydicom/deid
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/pydicom/deid/issues/274' target='_blank'>pydicom/deid#274</a>.

<small>Yes! Generally speaking you'd want to have a regular expression that matches that case here: https://github.com/pydicom/deid/blob/14d1e4eb70f2c9fda43fca411794be9d8a5a8516/deid/utils/actions.py#L32 and then throw an error when the particular name for the function is missing, or if the name is not found in "item." I'd be happy to review a PR for that, and a test could go [here](https://github.com/pydicom/deid/blob/14d1e4eb70f2c9fda43fca411794be9d8a5a8516/deid/tests/test_dicom_funcs.py)....</small>

<a href='https://github.com/pydicom/deid/issues/274' target='_blank'>View Comment</a>