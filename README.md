# GitHub Achievement Sandbox

This repository records a small, public experiment for GitHub profile achievements.

The goal is to document which achievements can be earned through normal GitHub actions in a repository you control, what thresholds are commonly reported by the community, and what actions were used in this sandbox.

GitHub does not publish every achievement threshold as a stable contract, and the feature is still described by GitHub as a public preview. Treat the numbers below as practical community knowledge, not as an official API guarantee.

## What This Repository Demonstrates

| Achievement | Practical trigger | Demonstrated here |
| --- | --- | --- |
| Quickdraw | Close an issue or pull request within 5 minutes of opening it | Issue #1 was opened and closed immediately |
| YOLO | Merge your own pull request without review | PR #2 was merged without review |
| Pull Shark | Have pull requests merged | PR #2 through PR #17 were merged |
| Pull Shark x2 | Community-reported threshold: 16 merged pull requests | 16 merged pull requests were created |
| Pair Extraordinaire | Merge a pull request with a co-authored commit | PR #3 and later marker PRs used `Co-authored-by` |
| Pair Extraordinaire x2 | Community-reported threshold: 10 co-authored merged pull requests | 10 co-authored merged pull requests were created |

## Experiment Log

The repository intentionally contains small marker files under [`achievements/`](achievements/). Each file corresponds to one pull request used to trigger or count toward an achievement threshold.

Key events:

- Issue #1: opened and closed quickly for Quickdraw.
- PR #2: first no-review merge for YOLO and Pull Shark.
- PR #3: first co-authored merged pull request for Pair Extraordinaire.
- PR #4 to PR #12: additional co-authored merged pull requests to reach the commonly reported Pair Extraordinaire x2 threshold.
- PR #13 to PR #17: additional merged pull requests to reach the commonly reported Pull Shark x2 threshold.

## Notes On Other Achievements

Some GitHub achievements are not practical to complete alone in a clean way:

- Starstruck depends on stars from other users.
- Galaxy Brain depends on accepted answers in GitHub Discussions.
- Public Sponsor requires sponsoring someone through GitHub Sponsors.
- Arctic Code Vault Contributor and Mars 2020 Contributor are historical achievements and are no longer earnable.

## References

- [GitHub profile reference](https://docs.github.com/en/account-and-profile/reference/profile-reference)
- [Schweinepriester/github-profile-achievements](https://github.com/Schweinepriester/github-profile-achievements)

## Repository Purpose

This is not an application or library. It is a transparent record of the steps used to test GitHub profile achievements, so other people can understand the mechanics without guessing from screenshots or scattered posts.
