# Hooks README

This repo is configured to validate Github Pull Requests into the `master` and
`dev` branches.  See the `.github/workflows` directory for configurations.  

These validations are used: 

- commit messages comply with the Conventional Commits standard
- all code is formatted (with `mix format`) 
- all tests must pass 

Here are options for developers who find it helpful to perform checks locally
before making a commit.  

1. This directory contains the pre-commit script `commit-msg`, and the setup
   script `SetupGitHooks.sh`.

2. Use the tooling found in [pre-commit.com](https://pre-commit.com).

| Resource             | URL                                                             |
|----------------------|-----------------------------------------------------------------|
| Conventional Commits | https://www.conventionalcommits.org/en/v1.0.0/#summary
| ConvCom Cheatsheet   | https://gist.github.com/qoomon/5dfcdf8eec66a051ecd85625518cfd13
| Githooks             | https://git-scm.com/docs/githooks                               |
