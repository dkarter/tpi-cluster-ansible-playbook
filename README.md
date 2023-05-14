# Turing Pi 2 Cluster Playbooks

## Setup

Requires 1Password CLI to inject secrets into the playbook environment

```bash
op run --env-file="env" --no-masking -- ansible-playbook -i inventory main.yml
```

## Uninstall

```bash
ansible-playbook -i inventory uninstall-k3s.yml
```
