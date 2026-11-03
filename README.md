# SIS №9 — GitHub Actions CI Workflow

## Overview

This repository was created for SIS №9: **Automating Your First Quality Check**, as part of the *Introduction to Open Source Development* course.

## GitHub Actions Workflow

The repository contains a simple CI workflow located at:

`.github/workflows/main.yml`

The workflow automatically runs whenever new changes are pushed to the repository.

### Workflow Steps

1. A developer pushes changes to the repository.
2. GitHub Actions triggers the CI workflow.
3. The workflow runs on an Ubuntu virtual machine.
4. A simple script prints the following message:

   `Hello, world from my first CI pipeline!`

## Security Scanning Tool

**CodeQL** is a code analysis tool that helps developers identify potential security vulnerabilities and coding errors in their source code.
