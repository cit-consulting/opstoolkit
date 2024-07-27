# Operators toolkit

Set of handful container image, script and Kubernetes configs for daily usage by system administrator.

## Building

When build image please set git-commit label. Example:

`docker build disk-tools --label "git-commit=$(git rev-parse HEAD)" --tag ghcr.io/cit-consulting/disk-tools:1`
