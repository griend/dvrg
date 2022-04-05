# dvrg / divergent

`ansible-pull` playbook to configure my private desktop.

Inspired by: https://github.com/LearnLinuxTV/personal_ansible_desktop_configs

## Usage

```shell
$ sudo ansible-pull --url https://github.com/griend/dvrg.git
...
```

## Ansible service

A systemd service: `ansible.service` will be installed and this will be triggered by a `ansible.timer`.
