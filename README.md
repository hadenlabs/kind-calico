<!--


  ** DO NOT EDIT THIS FILE
  **
  ** 1) Make all changes to `provision/generator/README.yaml`
  ** 2) Run`task readme` to rebuild this file.
  **
  ** (We maintain HUNDREDS of open source projects. This is how we maintain our sanity.)
  **


  -->

[![Latest Release](https://img.shields.io/github/release/hadenlabs/kind-calico)](https://github.com/hadenlabs/kind-calico/releases) [![Lint](https://img.shields.io/github/workflow/status/hadenlabs/kind-calico/lint-code)](https://github.com/hadenlabs/kind-calico/actions?workflow=lint-code) [![CI](https://img.shields.io/github/workflow/status/hadenlabs/kind-calico/ci)](https://github.com/hadenlabs/kind-calico/actions?workflow=ci) [![Test](https://img.shields.io/github/workflow/status/hadenlabs/kind-calico/test)](https://github.com/hadenlabs/kind-calico/actions?workflow=test) [![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white)](https://github.com/pre-commit/pre-commit) [![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow)](https://conventionalcommits.org) [![KeepAChangelog](https://img.shields.io/badge/changelog-Keep%20a%20Changelog%20v1.0.0-orange)](https://keepachangelog.com)

# kind-calico

cluster with calico

## Requirements

This is a list of plugins that need to be installed previously to enjoy all the goodies of this configuration:

- [gomplate](https://github.com/hairyhenderson/gomplate)
- [Docker](https://www.docker.com)
- [taskfile](https://github.com/go-task/task)
- [kind](https://kind.sigs.k8s.io)

## Usage

# How to use this project

## Start Project

```bash
task environment
```

```bash
task setup
```

- See [Kind](/docs/usage/kind.md)
- See [System](/docs/usage/system.md)
- See [Ingress Controller](/docs/usage/ingress-controller.md)
- See [Databases](/docs/usage/databases.md)
- See [apps](/docs/usage/apps.md)

## Examples

<!-- Space: Projects -->
<!-- Parent: KindCalico -->
<!-- Title: Examples KindCalico -->
<!-- Label: Examples -->
<!-- Include: ./../disclaimer.md -->
<!-- Include: ac:toc -->

## Common

### Install Dependencies

```bash
task setup
```

## Help

**Got a question?**

File a GitHub [issue](https://github.com/hadenlabs/kind-calico/issues).

## Contributing

See [Contributing](./docs/contributing.md).

## Module Versioning

This Module follows the principles of [Semantic Versioning (SemVer)](https://semver.org/).

Using the given version number of `MAJOR.MINOR.PATCH`, we apply the following constructs:

1. Use the `MAJOR` version for incompatible changes.
1. Use the `MINOR` version when adding functionality in a backwards compatible manner.
1. Use the `PATCH` version when introducing backwards compatible bug fixes.

### Backwards compatibility in `0.0.z` and `0.y.z` version

- In the context of initial development, backwards compatibility in versions `0.0.z` is **not guaranteed** when `z` is increased. (Initial development)
- In the context of pre-release, backwards compatibility in versions `0.y.z` is **not guaranteed** when `y` is increased. (Pre-release)

## Copyright

Copyright © 2018-2025 [Hadenlabs](https://hadenlabs.com)

## Trademarks

All other trademarks referenced herein are the property of their respective owners.

## License

The code and styles are licensed under the LGPL-3.0 license [See project license.](LICENSE).

## Don't forget to 🌟 Star 🌟 the repo if you like kind-calico

[Your feedback is appreciated](https://github.com/hadenlabs/kind-calico/issues)
