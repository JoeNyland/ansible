# Ansible playbook for my home server

Configuration management for my home server.

## Setup

```bash
python3 -m venv --upgrade-deps venv
source venv/bin/activate
pip install -r requirements.txt
```

## Usage

```bash
ansible-playbook playbooks/main.yml
```
