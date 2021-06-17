# code-qa-demo

A Codeing Quality Assurance Demonstration

One of the main goals of quality assurance is making the process as automatic
as possible.

This repository demonstrates how quality assurance measure like
enforcing coding conventions, testing, validating models, etc can be defined as
proccesses _in code_ and enforced by software automatically on every commit to
a code repo or project.

## Getting Started Locally

Clone this repo and install the QA tool `pre-commit` locally with `pipenv` as follows:

`pipenv install && pre-commit install`

1. Make and commit a change to the jupyter notebook
2. Observe pre-commit enforce quality-assurance rules on the changes.
3. Fix any violations, and finally complete the commit.

## Enforcing Q/A centrally via github/gitlab/bitbucket pipelines/actions

4. Create a bitbucket or github or (not yet supported here) gitlab repo
5. Push to that repo
6. Observe the pipeline executing the respective QA processes
