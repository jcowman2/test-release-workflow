# Test-Release-Workflow

[![Build Status](https://travis-ci.org/jcowman2/test-release-workflow.svg?branch=master)](https://travis-ci.org/jcowman2/test-release-workflow)

This repository serves as a playground for me to test my JavaScript release workflow.

## Features

* Provides a standard for commit messages.
* Automatically deploys project to npm and GitHub.
* Updates `CHANGELOG.md` and `package.json`.
* Pushes the updates to GitHub.

## Tools

* Commitizen
* Semantic-release

## Instructions

1. Install Dependencies
    1. `npm install`
    2. `npm install -g commitizen`

2. Make changes

3. Commit with `git cz`

4. Release with `npx semantic-release`