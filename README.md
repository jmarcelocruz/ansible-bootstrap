# ansible-bootstrap

Bootstrap fresh installations with a consistent baseline.

## Usage

1. Add your hosts to the proper group in the inventory file `inventory/hosts.yaml`.

2. Run the desired playbook from `playbooks/` with `ansible-playbook -i inventory/hosts.yaml playbooks/<playbook>.yaml`
