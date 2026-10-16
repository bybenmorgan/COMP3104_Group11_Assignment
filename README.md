# COMP3104_Group11_Assignment

## Project Description

This is Group 11's assignment for COMP3104 DevOps. Each member uses their own branch to add information about George Brown College, the DevOps course and DevOps in the software development lifecycle (SDLC). Changes are merged into `main` with PRs.

## Group Members

| Name | Student ID | GitHub |
|------|------------|--------|
| Ben Morgan | 101579211 | [bybenmorgan](https://github.com/bybenmorgan) |
| Hannah Bravo| 101127115 | [hannahovarb](https://github.com/hannahovarb) |


## Setup Instructions

Clone the repository and open its folder:

```bash
git clone https://github.com/bybenmorgan/COMP3104_Group11_Assignment.git
cd COMP3104_Group11_Assignment
```

Create a personal branch. Replace `STUDENTID-Name` with your student ID and first name:

```bash
git switch -c STUDENTID-Name
git push -u origin STUDENTID-Name
```

If your branch already exists on GitHub, switch to it after cloning using `git switch STUDENTID-Name`.

## CI/CD Setup

We used GitHub Actions for our CI. The workflow is stored in `.github/workflows/ci.yml` and runs on pushes and PRs.

The `repository-check` job runs on `ubuntu-latest`. It checks out the repository, prints a confirmation message and lists all the files. Run status and logs are available in the repository's Actions tab.

## Branching Strategy

Each member works on a branch called `STUDENTID-Name`. For example, my name is Ben and my student ID is 101579211, so my branch is `101579211-Ben`.

All file changes and commits are made locally. The team members sync their branches with `main` and fix any issues before merging their work with a PR. We keep the branches after merging so they are still able to be reviewed.