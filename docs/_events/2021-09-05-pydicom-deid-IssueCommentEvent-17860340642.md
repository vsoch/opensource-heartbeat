---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2021-09-05
repo_name: pydicom/deid
html_url: https://github.com/pydicom/deid/pull/184
repo_url: https://github.com/pydicom/deid
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/pydicom/deid/pull/184' target='_blank'>pydicom/deid#184</a>.

<small>hey @adildahlan so I figured it out! What was happening is that for any action that uses the `add` functionality, the assumption was adding to the dicom directly as a field. Of course with file meta this is problematic because we need to save to the filemeta instead. So the fix was to restore preserving the boolean if something was file meta, and then taking a different action in the parser depending on if it was file meta or not. Take a look at the changes here: https://github.com/pydicom/deid/pull/184/commits/a7f3f2012a16bf193e85a0e8207fe63f5ce03fc0 and when tests pass give the updated branch a try....</small>

<a href='https://github.com/pydicom/deid/pull/184' target='_blank'>View Comment</a>