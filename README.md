# env_test README

env_test is a demo repo for using multiple Environments with GitHub Actions.

It makes use of three environments:

1. test
2. staging
3. prod

Each of those has a secret `ENV_NAME` which is set to the respective
environment name for demo purposes.

## Who is this for?

This is for people making use of GitHub Actions who want to see how multiple
environments work.

## Why, What, How?

### Why?

Show how environments are used by Actions.

### What?

Three environments are configured along with Actions that use them.

### How?

Each Action echoes a double ROT13 version of `ENV_NAME` to the logs.
Rot13 is needed because GitHub wisely masks secrets, but in this case the
secrets need to be shown to demonstrate.

### LICENSE

Apache 2.0 [LICENSE](LICENSE)

## Maintainers

Created by [@cpswan](https://github.com/cpswan)