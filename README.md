# Default (root) GitHub project

[![Linting][img-gh-action-lint-badge]][gh-action-lint]
[![Code Vulnerability Scanning][img-gh-action-cvs-badge]][gh-action-cvs]

GitHub supports a repository (named `.github`) with files that are inherited by all other projects.
These "default" files will be used for any repository owned by the account that does not contain its own file of that type.

For more information, please see [Creating a default community health file][gh-creating-default-comm-health-file].

## Issue Templates

This repo uses GitHub Issue Forms for standardized issue creation across repositories in this organization.

### Included Issue Templates

- 🐛 Bug Report
  - For reporting bugs or defects.
- 📦 Epic
  - For tracking larger bodies of work that can be broken down into features, user stories, and tasks.
- 🚀 Feature Request
  - For requesting new features or enhancements.
- 📖 User Story
  - For user-focused stories describing a capability and its acceptance criteria.

## Organization Profile

This special repository also contains a special file `./profile/README.md` that will appear on the organizations profile.

<!-- reference urls -->

[gh-action-cvs]: https://github.com/plantemoran-appdev/.github/actions/workflows/code-analysis.yml
[gh-action-lint]: https://github.com/plantemoran-appdev/.github/actions/workflows/linting.yml
[gh-creating-default-comm-health-file]: https://help.github.com/en/github/building-a-strong-community/creating-a-default-community-health-file
[img-gh-action-cvs-badge]: https://github.com/plantemoran-appdev/.github/actions/workflows/code-analysis.yml/badge.svg
[img-gh-action-lint-badge]: https://github.com/plantemoran-appdev/.github/actions/workflows/linting.yml/badge.svg
