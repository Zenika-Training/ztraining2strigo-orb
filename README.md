# Orb Project Template

[![CircleCI Build Status](https://circleci.com/gh/Zenika-Training/ztraining2strigo-orb.svg?style=shield "CircleCI Build Status")](https://circleci.com/gh/Zenika-Training/ztraining2strigo-orb) [![CircleCI Orb Version](https://badges.circleci.com/orbs/zenika-training/ztraining2strigo.svg)](https://circleci.com/orbs/registry/orb/zenika-training/ztraining2strigo) [![GitHub License](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/Zenika-Training/ztraining2strigo-orb/master/LICENSE)

Update Strigo class from Zenika training.

## Resources

[CircleCI Orb Registry Page](https://circleci.com/orbs/registry/orb/zenika-training/ztraining2strigo) - The official registry page of this orb for all versions, executors, commands, and jobs described.

### How to Contribute

We welcome [issues](https://github.com/Zenika-Training/ztraining2strigo-orb/issues) to and [pull requests](https://github.com/Zenika-Training/ztraining2strigo-orb/pulls) against this repository!

### How to Publish

* Create and push a branch with your new features.
* When ready to publish a new production version, create a Pull Request from _feature branch_ to `master`.
* The title of the pull request must contain a special semver tag: `[semver:<segment>]` where `<segment>` is replaced by one of the following values.

| Increment | Description|
| ----------| -----------|
| major     | Issue a 1.0.0 incremented release|
| minor     | Issue a x.1.0 incremented release|
| patch     | Issue a x.x.1 incremented release|
| skip      | Do not issue a release|

Example: `[semver:major]`

* Squash and merge. Ensure the semver tag is preserved and entered as a part of the commit message.
* On merge, after manual approval, the orb will automatically be published to the Orb Registry.
