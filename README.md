<div align="center">

<img src="https://steerspec.dev/assets/logo.svg" alt="SteerSpec logo" width="72" height="72">

# SteerSpec Hub community health files

**Org-wide defaults and the public profile for the [steerspec-hub](https://github.com/steerspec-hub) organization.**

[![CI](https://github.com/steerspec-hub/.github/actions/workflows/ci.yml/badge.svg)](https://github.com/steerspec-hub/.github/actions/workflows/ci.yml)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)

[Contents](#contents) · [How defaults apply](#how-defaults-apply) · [Contributing](#contributing)

</div>

This repository holds the community health files GitHub uses as defaults for SteerSpec Hub
repositories that don't define their own, plus the README rendered on the organization page. For the hub itself,
visit [steerspec-hub.com](https://steerspec-hub.com); for SteerSpec, [steerspec.dev](https://steerspec.dev).

## Contents

| File | Purpose |
| ---- | ------- |
| [`profile/README.md`](profile/README.md) | The public organization profile |
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | How to propose changes |
| [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) | Community standards |
| [`SECURITY.md`](SECURITY.md) | How to report a vulnerability |
| [`LICENSE`](LICENSE) | Apache 2.0 |
| [`.github/workflows/`](.github/workflows) | CI: actionlint, markdown lint, relative-link integrity |

## How defaults apply

GitHub uses only the community health files as org-wide defaults: `CONTRIBUTING.md`,
`CODE_OF_CONDUCT.md` and `SECURITY.md`. A repository that has none of its own shows these. A repo's
own file always wins, so override per repo whenever the org default doesn't fit.

`profile/README.md` renders on the organization page. The README, `LICENSE`, the markdownlint
configuration and the CI workflow apply to this repository only; GitHub copies none of them into
other repositories.

## Contributing

Changes to the community health files and the profile affect every repository in the org, so keep
them small and open a pull request. See
[`CONTRIBUTING.md`](CONTRIBUTING.md).
