# Ansible playbook for flashing your ZSH coordinator

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/Marck/flash-zsh-coordinator/graphs/commit-activity)
[![Donate](https://img.shields.io/badge/Donate-coffee-1abc9c.svg)](https://www.buymeacoffee.com/marcked)

This playbook is based on the steps mentioned on the [Electrolama docs](https://electrolama.com/radio-docs/#step-2-download-the-correct-firmware-for-your-stick).

## How to use it

> Note: at the moment, the playbook is using a lot of hardcopy values. This is something to improve later on.

### Prerequisites

To start using this playbook, make sure you have the following prerequisites:

1. ansible, python3 and pip3 installed
2. change the following variables in `group_vars/all.yaml`:
    - `work_dir`
    - `firmware_version`

## Support

If you want to buy me a cup of coffee (or join my monthly club), that would be highly appreciated.
You can do so [by clicking here](https://www.buymeacoffee.com/marcked).

Thanks again!

## Disclaimer

In no way I am affliated with Electrolama, nor do I work for them. They just make awesome stuff.
This repository is provided as is and free to use. Feel free to create a pull request or file a bug.
