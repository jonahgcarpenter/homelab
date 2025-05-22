# Homelab

Welcome to the official documentation for my personal homelab! This repository serves as a central knowledge base for the setup, configuration, and ongoing maintenance of my home server environment.

My lab currently consists of **three physical host machines running Proxmox VE**, which in turn host a **K3s Kubernetes cluster**. This setup allows for experimentation with virtualization, containerization, networking, and various self-hosted applications.

---

## 🚀 Quick Navigation

- [**README.md**](./README.md)
- [**Hardware**](./hardware/)
  - [Host 1 (Proxmox)](./hardware/pve-1/specs.md)
  - [Host 2 (Proxmox)](./hardware/pve-2/specs.md)
  - [Host 3 (Proxmox)](./hardware/pve-3/specs.md)
- [**Networking**](./networking/config.md)
- [**Proxmox VE**](./proxmox/)
  - [Applications](./proxmox/applications.md)
- [**K3s Kubernetes Cluster**](./k3s-cluster/)
  - [Applications](./k3s-cluster/applications.md)
- [**HomeAssistant**](./homeassistant/smarthome.md)

---

## tujuan (Purpose of this Homelab)

This homelab serves several purposes:

- **Learning & Experimentation:** A sandbox to explore new technologies, software, and configurations in a controlled environment. This includes virtualization (Proxmox), containerization (Docker, K3s), networking, and various server applications.
- **Self-Hosting:** Running various services for personal use, such as media servers, home automation, development tools, and personal cloud storage.
- **Skill Development:** Enhancing skills in system administration, network management, DevOps practices (like IaC with Ansible/Terraform), and cybersecurity.
- **Reproducibility:** Documenting the setup allows for easy recreation or recovery in case of hardware failure or a desire to rebuild.

---

## 🛠️ Core Technologies

- **Virtualization:** Proxmox VE
- **Container Orchestration:** K3s (Lightweight Kubernetes)
- **Operating Systems:** (Docker, Debian, Ubuntu Server, Alpine Linux for VMs/Containers)
- **Networking:** (e.g., OPNsense/pfSense if used, Unifi gear, specific VLAN configurations)
- **Version Control:** Dockerhub & GitHub

---

## 📝 Documentation Philosophy

This documentation aims to be:

- **Accurate:** Reflecting the current state of the homelab.
- **Clear & Concise:** Easy to understand, even for "future me."
- **Practical:** Containing enough detail to reproduce setups and troubleshoot issues.
- **Up-to-Date:** Regularly updated as changes are made to the lab.

If you are me from the future, please keep this documentation current! Note down changes, big or small.
