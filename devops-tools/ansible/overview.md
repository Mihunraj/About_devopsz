# Ansible Overview

## What is Ansible?

Ansible is an open-source automation tool that simplifies the process of managing and configuring systems, deploying applications, and orchestrating complex workflows. It uses a declarative language to describe system configurations and automates tasks across multiple machines.

### Key Features of Ansible

- **Agentless**: Ansible does not require any agent to be installed on the target machines; it uses SSH for communication.
- **Idempotent**: Ansible ensures that the desired state is achieved without making unnecessary changes.
- **Playbooks**: Ansible uses YAML files called playbooks to define automation tasks.

## Key Concepts

- **Playbook**: A YAML file that contains a list of tasks to be executed on specified hosts.
- **Inventory**: A file that lists the hosts and groups of hosts on which Ansible will operate.
- **Module**: A reusable script that Ansible uses to perform specific tasks (e.g., installing packages, copying files).
