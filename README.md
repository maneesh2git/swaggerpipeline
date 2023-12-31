# Connect 2020

This repository shows a possible workflow for working with SwaggerHub, CI/CD, and the SwaggerHub Registry API.

We're using GitHub Actions for the pipeline. We're using Node.js for the API and testing.

## Workflow

Here are the steps we'll take to look at this workflow.

1. Create a new version of our Book API in SwaggerHub
1. Save and push changes to a version-specific branch in GitHub
1. See failing tests, then build functionality
1. See passing tests, then open Pull Request
1. Merge to master
1. Publish and mark new version as default