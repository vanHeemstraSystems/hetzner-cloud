# 100 - Servers

## 100 - Overview

### Server Types:

**Standard**

- For best performance, hypervisors are used to distribute usage rights of CPU resources among several virtual servers
- Ideal for individual applications or development environments

|Name|vCPUs|Ram|SSD|Traffic|Price per hour*|Price per month*|
|--|--|--|--|--|--|--|
|CX11|1 Intel|2 GB|20 GB|20 TB|€ 0.0052 / h|€ 3.29 / mo| 

\* All prices excl. VAT

### Operating Systems

See also "Selecting the best Linux distribution for Kubernetes clusters" at https://www.x-cellent.com/posts/selecting-the-best-linux-distribution-for-kubernetes-clusters

You can choose from:
- Ubuntu, <== Prefered, as a well-tested base for RancherOS
- Fedora, 
- Debian, 
- CentOS,  
- Rocky Linux  
as your operating system.

*TIP*: Have a look at [Kubespray](https://github.com/kubernetes-sigs/kubespray),an Ansible based K8s installer. See a video titled [Deploying kubernetes using Kubespray](https://www.youtube.com/watch?v=CJ5G4GpqDy0) about a walk through the deployment of Kubernetes on **Ubuntu 18.04 LTS** using Kubespray.

## 200 - Getting Started

Based on "Creating a Server" at https://docs.hetzner.com/cloud/servers/getting-started/creating-a-server

Based on "Ansible for Kubernetes" at https://leanpub.com/ansible-for-kubernetes/read_full (in my library)

