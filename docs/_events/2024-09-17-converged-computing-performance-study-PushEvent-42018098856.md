---
event_type: PushEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2024-09-17
repo_name: converged-computing/performance-study
html_url: https://github.com/converged-computing/performance-study/commit/79e8f1bad3aef50c0b7d97c1c468cc2b6538597f
repo_url: https://github.com/converged-computing/performance-study
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> pushed to <a href='https://github.com/converged-computing/performance-study' target='_blank'>converged-computing/performance-study</a>

<small>Merge pull request #51 from converged-computing/catalog-mixbench

* analysis: catalog for mixbench

Every environment was run slightly differently,
with very little overlap. I am not sure how we can
use this data.

* debug: mixbench

Here I am adding the actual run statements across the mixbench
configurations so they can be visually compared.

Signed-off-by: vsoch <vsoch@users.noreply.github.com>

* analysis: mixbench, parsed data

This changeset includes parsed data for GPU runs. I want to look
at these more closely to decide what to further parse and plot. The
CSVs are compiled from each experiment environment, and that includes
interleaving. I think we might still combine regardless to make a line
plot based on the index/iteration.

Signed-off-by: vsoch <vsoch@users.noreply.github.com>

* gpu analysis: add summary for similar/different

Here we see that there are differences in memory size, notably for Google
(only 16GB) and then the other clouds. On the other clouds (32GB) the actual
values are still a little different. The weirdest finding is the error correction
seems to be set at a mixture of yes/no for Azure GPUs

Signed-off-by: vsoch <vsoch@users.noreply.github.com>

---------

Signed-off-by: vsoch <vsoch@users.noreply.github.com>
Co-authored-by: vsoch <vsoch@users.noreply.github.com></small>

<a href='https://github.com/converged-computing/performance-study/commit/79e8f1bad3aef50c0b7d97c1c468cc2b6538597f' target='_blank'>View Commit</a>