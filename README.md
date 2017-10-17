# Provision a Development Machine using Ansible

Ansible playbooks for provisioning macOS and Linux development machines.

The name `ansiblerc` is an allusion to scripts such as `.bashrc` in Linux.

## macOS

First of all, install [Ansible](http://docs.ansible.com/ansible/latest/index.html)
any way you like. Examples:

- `brew install ansible`
- `pip install ansible`

You may also need to install Xcode Command Line Tools:

```
xcode-select --install
```

Finally, run the macOS playbook:

```bash
ansible-playbook -i localhost macos.yml
```

## Ubuntu

Coming soon ...
