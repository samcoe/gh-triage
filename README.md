# `gh triage` GitHub CLI extension

A small [gh](https://github.com/cli/cli) extension for finding issues to be triaged in a GitHub repository.

## Installation
 ```
 gh extension install samcoe/gh-triage
 ```

## Usage
 ```
 gh triage [flags]
 ```

### Flags

Supports all options that `gh issue list` supports, except for `--json`, `--jq`, and `--template` which are being utilized by this extension.

### Details

This extensions will list any open issues that are not labeled with any of the following labels:
- p1
- p2
- p3
- core
- help wanted
- tracking issue
- needs-design
- blocked
- needs-user-input

## Author

@samcoe
