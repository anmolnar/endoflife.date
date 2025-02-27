---
title: Vault
permalink: /hashicorp-vault
alternate_urls:
-   /vault
category: server-app
iconSlug: vault
releasePolicyLink: https://support.hashicorp.com/hc/articles/360021185113
sortReleasesBy: releaseDate
changelogTemplate: https://github.com/hashicorp/vault/blob/v__LATEST__/CHANGELOG.md
auto:
-   git: https://github.com/hashicorp/vault.git
activeSupportColumn: false
releaseDateColumn: true
versionCommand: vault --version

releases:
-   releaseCycle: "1.11"
    eol: false
    latest: "1.11.1"
    latestReleaseDate: 2022-07-21
    releaseDate: 2022-07-21
-   releaseCycle: "1.10"
    eol: false
    latest: "1.10.5"
    latestReleaseDate: 2022-07-21
    releaseDate: 2022-03-23
-   releaseCycle: "1.9"
    eol: false
    latest: "1.9.8"
    latestReleaseDate: 2022-07-21
    releaseDate: 2021-11-17

---

> [Hashicorp Vault](https://www.vaultproject.io/) is a tool for securely accessing secrets. It provides a unified interface to any secret, while providing tight access control and recording a detailed audit log.

Generally Available (GA) releases of active products are supported for up to two (2) years. Eligible code-fixes and hot-fixes are provided via a new minor release (Z) on top of the latest "major release" branch, for up to two (2) releases from the most current major release. 

A major release is identified by a change in the first (X) or second (Y) digit in the following versioning nomenclature: `Version X.Y.Z.`

Hashicorp uses the same support period and EoL Policy for all its products.
