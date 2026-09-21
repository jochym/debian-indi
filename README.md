# debian-indi

Debian and Ubuntu packaging for INDI libraries and drivers.

This repository contains Debian/Ubuntu packaging files and automated build workflows for
[INDI](https://indilib.org) (Instrument Neutral Distributed Interface) libraries
and drivers, producing APT repositories for Debian and Ubuntu systems.

For repository setup and installation instructions, visit: **https://jochym.github.io/debian-indi**

## Supported Distributions & Architectures

| Distribution | Codename | Architectures |
|---|---|---|
| **Debian 12** (Bookworm) | `bookworm` | `amd64`, `arm64` |
| **Debian 13** (Trixie / Testing / Stable) | `trixie`, `stable` | `amd64`, `arm64` |
| **Ubuntu 24.04 LTS** (Noble Numbat) | `noble` | `amd64`, `arm64` |
| **Ubuntu 26.04 LTS** (Resolute) | `resolute` | `amd64`, `arm64` |

## Objective

Provide automated, up-to-date INDI builds for Debian and Ubuntu in an easy-to-use APT repository format.

## Background

This repository was created for use in astronomy setups (e.g. Raspberry Pi / Orange Pi / PC) as an alternative and automated source for INDI packages, tracking upstream releases at [indilib/indi](https://github.com/indilib/indi) and [indilib/indi-3rdparty](https://github.com/indilib/indi-3rdparty).
