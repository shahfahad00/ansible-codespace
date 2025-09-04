
# Lab 4 — CI/CD with Ansible (GitHub Codespaces + Actions)

This repo contains:
- `inventory` pointing to localhost
- `playbooks/hello.yml` that prints a message
- `.github/workflows/ansible.yml` to run the playbook in CI
- `.devcontainer/devcontainer.json` to preinstall Ansible in Codespaces

## Local quick test in Codespaces
```bash
ansible --version
ansible-playbook -i inventory playbooks/hello.yml
```
