# Kubernetes Installation Script for CentOS 9

This repository contains a script for automating the installation and configuration of Kubernetes on a CentOS 9 machine. The script streamlines the process of setting up Kubernetes components on a master node.

**Note:** Before using this script, please be aware of the following:

- The script is intended for CentOS 9.
- Manual steps such as adding master node information and understanding the changes made are necessary.

## Prerequisites

- A CentOS 9 machine with root or sudo access.
- Internet connectivity for package downloads during installation.
- Adding Master Node Entry to /etc/hosts
To ensure proper communication within the Kubernetes cluster, manually add the master node's IP address and hostname to the /etc/hosts file on all cluster nodes.
- make sure you add "master-node" into hosts file before running the script

## Usage

1. Clone this repository to your CentOS 9 machine:

   ```bash
   git clone https://github.com/rsoran/kubectl.git
   cd kubectl

**make it executable and run**

 ```bash
chmod +x kubectl.sh

./kubectl.sh
```
**Important Notes**
The script modifies firewall rules, installs Docker, and configures Kubernetes components. Ensure you understand these changes before proceeding.
The script may require adjustments based on your network configuration or specific use case.
**Disclaimer**
This script is provided as-is, without warranties or guarantees. Use it at your own risk. Review and understand the script's content before executing it on your system.




