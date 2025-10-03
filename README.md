# GitHub Workflows

This repository contains reusable GitHub Actions workflows that can be referenced in your own repositories.

## How to Use

To use a reusable workflow from this repository, reference it in your workflow file using the following syntax:

```yaml
name: My Workflow

on:
  push:
    branches: [main]

jobs:
  call-reusable-workflow:
    uses: driesvints/github-workflows/.github/workflows/WORKFLOW_NAME.yml@main
```

Replace `WORKFLOW_NAME.yml` with the name of a workflow from below, and optionally replace `@main` with a specific tag or commit SHA for more stability.

## Available Workflows

Workflows will be added here as they become available.
