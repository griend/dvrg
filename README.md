# dvrg / divergent

`ansible-pull` playbook to configure my private desktop.

Inspired by: https://github.com/LearnLinuxTV/personal_ansible_desktop_configs

## Usage

```shell
$ sudo apt install -y ansible git
$ ansible-pull --url https://github.com/griend/dvrg.git [--ask-become-pass] [-e "dvrg_user=cees"] 
...
```
