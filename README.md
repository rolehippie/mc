# mc

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&amp;logoColor=white)](https://github.com/rolehippie/mc)
[![General Workflow](https://github.com/rolehippie/mc/actions/workflows/general.yml/badge.svg)](https://github.com/rolehippie/mc/actions/workflows/general.yml)
[![Readme Workflow](https://github.com/rolehippie/mc/actions/workflows/readme.yml/badge.svg)](https://github.com/rolehippie/mc/actions/workflows/readme.yml)
[![Galaxy Workflow](https://github.com/rolehippie/mc/actions/workflows/galaxy.yml/badge.svg)](https://github.com/rolehippie/mc/actions/workflows/galaxy.yml)
[![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/mc)](https://github.com/rolehippie/mc/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/role-rolehippie.mc-blue)](https://galaxy.ansible.com/rolehippie/mc)

Ansible role to install and configure mc cli client for Minio.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [mc_download](#mc_download)
  - [mc_version](#mc_version)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.10`


## Default Variables

### mc_download

URL to the archive of the release to install

#### Default value

```YAML
mc_download: https://dl.minio.io/client/mc/release/linux-amd64/archive/mc.{{ mc_version
  }}
```

### mc_version

Version for the binary

#### Default value

```YAML
mc_version: RELEASE.2023-04-06T16-51-10Z
```

## Discovered Tags

**_mc_**


## Dependencies

- None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
