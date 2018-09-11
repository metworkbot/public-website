# Contributing guide

## Code of Conduct

This project and everyone participating in it is governed by the [MetWork Code of Conduct](https://github.com/metwork-framework/resources/blob/master/documents/CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to [fixme@metwork-framework.org](mailto:fixme@metwork-framework.org).

## Branch management

In this repository:

- `master` branch is automatically deployed to production on [MetWork public website](http://www.metwork-framework.org).
- `integration` branch is automatically deployed to staging environnement on [MetWork staging website](http://www.metwork-framework.org/staging).
- the `master` branch is "protected" (including for administrators), you can't commit directly on it, you have to make a pull-request and got an external review.

We keep `integration` and `master` branch very close. And frequently, repository administrators copy `integration` branch to `master` (with some pull-requests).

We only integrate changes to `master` from `integration` branch (we are searching a way to enforce that on github).

## Submitting a change

So, the recommended way to submit a change is to make a pull-request on `integration` branch. When the pull-request will be accepted 
(so when your code will be on `integration` branch), your change will be visible on staging environnement.

Frequently, repository administrators will copy staging to production (through an explicit pull-request).
