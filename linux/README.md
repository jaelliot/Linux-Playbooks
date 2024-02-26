# Windows Playbooks

This repository contains a collection of Ansible playbooks for automating the configuration and management of Windows environments. These playbooks are designed to streamline the setup of Windows 10 systems, manage privacy settings, install software packages, and configure WSL-2, among other tasks.

## Getting Started

To use these playbooks, Ansible must be installed and configured for managing Windows hosts. See the [Ansible documentation](https://docs.ansible.com/ansible/latest/user_guide/windows_setup.html) for detailed instructions on setting up Ansible for Windows.

### Prerequisites

- Ansible 2.9 or later
- Windows 10 or Windows Server 2016/2019 targets
- SSH or WinRM access to your Windows machines

### Clone the Repository

To get started with these playbooks, clone the repository to your local machine or Ansible control node:

```bash
git clone git@github.com:jaelliot/Windows-Playbooks.git
```

### Usage

To run a playbook, navigate to the repository directory and execute the following command, replacing <playbook_name>.yml with the name of the playbook you wish to run:

```
ansible-playbook playbooks/<playbook_name>.yml -i inventory
```

Make sure to adjust the inventory file according to your environment's specifications.

### Contributing

Contributions to the Windows-Playbooks repository are welcome. To contribute, please fork the repository, make your changes, and submit a pull request.

### License
This project is licensed under the BSD-2 License - see the LICENSE file for details.