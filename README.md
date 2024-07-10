# setup-microshift-multinode-cluster

This Ansible playbook automates the setup of a MicroShift multi-node cluster. It's designed to quickly and easily provision a functional cluster for testing or development purposes.

## Prerequisites

* **Ansible:** Ensure Ansible is installed on your control node.
* **Target Nodes:** Prepare the IP addresses and SSH credentials for your target nodes (see "Adjusting Inventory" section).
* **Pull Secret:** Place the `openshift-pull-secret` file in the `/setup-microshift-multinode-cluster/roles/install_microshift/files` directory.
* **OpenShift Client:** Download the appropriate version of `openshift-client.rpm` into the same directory.

## Adjusting Inventory

Modify the `inventory` file to match your environment.



