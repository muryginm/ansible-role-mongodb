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
1. Install vargrant plugin to run molecule
    ```bash
    vagrant plugin install vagrant-vbguest
    ```

1. Run tests
    ```bash
    molecule test
    ```
