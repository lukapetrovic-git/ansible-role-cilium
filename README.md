# ansible-role-cilium
Ansible role to install/upgrade/downgrade/change Cillium (config) on k8s cluster.

# Requirements
- Ansible 2.10 or later
- Kubernetes cluster with no CNI or Cilium installed

# Tested on
- Ubuntu 20.04 LTS
- Ubuntu 22.04 LTS

  NOTE: Should work on all Linux/k8s distributions

# Role Variables
All settable variables with explanations and links are located in the defaults/main.yml

## TODO
- Create Action to publish to Ansible Galaxy
- Write Molecule tests
- Create Action to run Molecule tests
- Create CI
- Add examples to readme