# debian-config

Ansible to setup up working environment on Ubuntu/Debian/...
Even though the repo is named "debian-config" I'll be mostly targeting Ubuntu
This repo exists, because some companies are particular about which distribution they allow and Ubuntu happens to make the list quite often.

## Prerequisites

- git
- ansible >=2.6.3
- python2 >=2.7.13 (required by ansible)

### Prerequisites installation (with apt)

```
sudo apt-get update
sudo apt install -y git python ansible sudo
```

## Installation

```sh
git clone https://github.com/allgreed/debian-config.git ~/debian-config
~/debian-config/run
```
