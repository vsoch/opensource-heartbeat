---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2025-05-03
repo_name: rseng/zenodo-release
html_url: https://github.com/rseng/zenodo-release/commit/a9c88701a0176df755015f8ca4cf8cc754162f27
repo_url: https://github.com/rseng/zenodo-release
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/rseng/zenodo-release' target='_blank'>rseng/zenodo-release</a>

<small>Fix missing command arguments (#17)

* add title and description support + do not override related_identifiers if some exists
* fix invalid format args
* pass down title/description to command
* add quotes around action parameters
* undo quotes for zenodo json param
* undo quotes for doi param
* provide '--description-file' alternative parameter for zenodo record description
* add missing 'description_file' forwarding
* replace single quotes by escaped double quotes to avoid unresolved file path with literal quote in string parameter + use argparse.FileType to raise unresolved file immediately

* adjust commands to avoid weird literal single/double quotes parsing</small>

<a href='https://github.com/rseng/zenodo-release/commit/a9c88701a0176df755015f8ca4cf8cc754162f27' target='_blank'>View Commit</a>