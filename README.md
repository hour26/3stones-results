# 3stones public results

Published round files for independent recounting of 3stones votes.

Production rounds belong under `rounds/<lunation>/`. No production results have been published yet.
Test rounds belong under `staging/rounds/<round>/`. They are test data and do not represent a public vote.

The staging result and receipt pages use https://3stones-staging.26hours.xyz. The production target is https://3stones.xyz.

Each exported round contains `results.json`, public `ballots.json` lists and available OpenTimestamps files.
Ballot lists contain only leaf hashes and answers. They contain no account identifiers, receipt secrets or individual demographics.

An export is checked against its published tallies and Merkle roots before it is written.
A matching recount does not independently establish the authenticity of every disclosed answer or prove a unique human per account.
Calendar acceptance of a timestamp is separate from a Bitcoin-confirmed timestamp.

The exporter is in the 3stones source repository. Commits preserve published snapshots for comparison.
