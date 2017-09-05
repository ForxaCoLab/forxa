Forxa Co-Lab. Software baseado en [Gogs](https://github.com/gogits/gogs):
==========================================================================

## Purpose

The goal of this project is to make the easiest, fastest, and most painless way of setting up a self-hosted Git service. With Go, this can be done with an independent binary distribution across **ALL platforms** that Go supports, including Linux, Mac OS X, Windows and ARM.

## Overview

- Please see the [Documentation](https://gogs.io/docs/intro) for common usages and change log.
- See the [Trello Board](https://trello.com/b/uxAoeLUl/gogs-go-git-service) to follow the develop team.
- Want to try it before doing anything else? Do it [online](https://try.gogs.io/gogs/gogs)!
- Having trouble? Get help with [Troubleshooting](https://gogs.io/docs/intro/troubleshooting.html) or [User Forum](https://discuss.gogs.io/).
- Want to help with localization? Check out the [guide](https://gogs.io/docs/features/i18n.html)!

## Features

- Activity timeline
- SSH and HTTP/HTTPS protocols
- SMTP/LDAP/Reverse proxy authentication
- Reverse proxy with sub-path
- Account/Organization/Repository management
- Add/Remove repository collaborators
- Repository/Organization webhooks (including Slack)
- Repository Git hooks/deploy keys
- Repository issues, pull requests and wiki
- Migrate and mirror repository and its wiki
- Web editor for repository files and wiki
- Gravatar and Federated avatar with custom source
- Mail service
- Administration panel
- Supports MySQL, PostgreSQL, SQLite3 and [TiDB](https://github.com/pingcap/tidb) (experimental)
- Multi-language support ([19 languages](https://crowdin.com/project/gogs))

## System Requirements

- A cheap Raspberry Pi is powerful enough for basic functionality.
- 2 CPU cores and 1GB RAM would be the baseline for teamwork.

## Installation

Installation can be done with 'one-click' using [docker-compose](https://github.com/ForxaCoLab/forxacolab/blob/master/docker-compose.yml) or following these methods:

Make sure you install the [prerequisites](https://gogs.io/docs/installation) first.

There are 5 ways to install Gogs:

- [Install from binary](https://gogs.io/docs/installation/install_from_binary.html)
- [Install from source](https://gogs.io/docs/installation/install_from_source.html)
- [Install from packages](https://gogs.io/docs/installation/install_from_packages.html)
- [Ship with Docker](https://github.com/gogits/gogs/tree/master/docker)
- [Install with Vagrant](https://github.com/geerlingguy/ansible-vagrant-examples/tree/master/gogs)


## Contributors

- Co-Lab developers team, led by [@dalareo](https://github.com/dalareo).

## License

This project is under the MIT License. See the [LICENSE](https://github.com/gogits/gogs/blob/master/LICENSE) file for the full license text.
