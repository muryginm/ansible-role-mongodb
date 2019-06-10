# Ansible Role Mongodb

Role to setup mongodb

## Getting Started

1. Install ansible requirements
    ```bash
    virtualenv .venv
    source .venv/bin/activate
    pip install -r requirements.txt
    ```

## Test
```bash
molecule create
molecule converge
molecule verify
```

## Cleanup
```bash
molecule destroy
```
