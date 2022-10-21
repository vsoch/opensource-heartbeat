---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2022-10-20
repo_name: buildsi/splice-experiment-results
html_url: https://github.com/buildsi/splice-experiment-results/commit/3aee7ce28fbd897f89247d25cff54b902b3fd177
repo_url: https://github.com/buildsi/splice-experiment-results
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/buildsi/splice-experiment-results' target='_blank'>buildsi/splice-experiment-results</a>

<small>Scripts for making paper numbers (#11)

* Match 'first|second' exactly
* Add notes
* Ignore more files
* Remove unused parts of 'fedora_analysis.py'
* Rename fedora_analysis.py to make_csv.py
* Add script for getting counts
* stuff
* Remove by-analysis breakdown
It was broken. The joins weren't unique.
* Don't parse 'symbol-exports'
* Ignore generated files
* Update notes on count breakdowns
* Include missing 3-pred case to counts
* Redo count parsing
* Move counts from notes to messages.summary
* Skip predictor output when prediction is True
abi lab does this.
* Include all error messages
This previously excluded cases where all of the predictors returned
False.
* Exclude missing-previously-found-exports from counts
We aren't using this predictor any more.
* Add fraction calculations for counts
* big refactor of parse_messages.pl
* Add sql script to create database
* Split out libraries by predictor
* Split out predictor breakages
* Split out 3-predictor missing
* Add description/instructions for generating results
* adding more notes to analysis
adding automated build environment (docker) and package
alongside repository, a run.sh script, consolidating
database generation into one file, and moving old
files into separate folder.
Signed-off-by: vsoch <vsoch@users.noreply.github.com>
* update true ==1 and false ==0
Signed-off-by: vsoch <vsoch@users.noreply.github.com>
* Add statists to agreement calc
Signed-off-by: vsoch <vsoch@users.noreply.github.com>
Co-authored-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/buildsi/splice-experiment-results/commit/3aee7ce28fbd897f89247d25cff54b902b3fd177' target='_blank'>View Commit</a>