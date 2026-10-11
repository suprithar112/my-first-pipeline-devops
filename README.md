# Hello World CI Pipeline

A beginner-friendly DevOps project using GitHub Actions.

## Run the script

    bash hello.sh

## CI Pipeline

The workflow is located at .github/workflows/ci.yaml.

It runs when a pull request targets the main branch.

Pipeline jobs:
1. Build - Prints a build message.
2. Test - Runs after Build succeeds.
3. Deploy - Runs after Test succeeds.

This is a demonstration pipeline; the jobs print messages rather than deploying a real application.
