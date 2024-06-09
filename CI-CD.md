# CI/CD in the Underthesea Project

This article outlines the CI/CD process in the Underthesea project, emphasizing our use of GitHub Actions.

## Overview

Our CI/CD pipeline is built using [GitHub Actions](https://docs.github.com/en/actions), which ensures seamless integration and deployment.


## Main Workflow

The main build workflow is triggered on every merge request. This ensures that all changes are automatically built and tested before being merged.

[View the build workflow](https://github.com/undertheseanlp/underthesea/blob/main/.github/workflows/build.yml)

**Relevant PRs:**
- [PR #716](https://github.com/undertheseanlp/underthesea/pull/716)
- [PR #701](https://github.com/undertheseanlp/underthesea/pull/701)

## Specific Workflows

For special and heavy load workflows, we don't run these on every PR. Instead, specific labels are assigned to PRs to trigger these workflows. This approach optimizes resource usage and ensures that only relevant PRs trigger resource-intensive processes.

[View the custom workflow](https://github.com/undertheseanlp/underthesea/blob/main/.github/workflows/ci-pipe-langdetect.yml)

**Relevant PRs:**
- [PR #736](https://github.com/undertheseanlp/underthesea/pull/736)
