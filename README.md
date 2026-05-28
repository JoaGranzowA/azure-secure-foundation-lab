# Azure Secure Foundation Lab

This repo is my first hands-on Azure security lab, focused on building a secure baseline cloud environment.

The goal of this project is to practice Azure administration and cloud security fundamentals by designing, deploying, and documenting a small but secure Azure environment.

---

## Goals

- Build a simple Azure environment from scratch
- Apply basic cloud security controls
- Practice Azure administration concepts from AZ-900 and AZ-104
- Document security decisions clearly
- Keep the lab small, low-cost, and reproducible

---

## Planned Architecture

```text
Azure Subscription
└── Resource Group
    ├── Virtual Network
    │   ├── Public Subnet
    │   └── Private Subnet
    ├── Network Security Group
    ├── Windows Virtual Machine
    ├── Storage Account
    ├── Key Vault
    ├── Log Analytics Workspace
    └── Azure Policy basics
```

---

## Security Focus Areas

- Resource organization
- Network segmentation
- Least privilege access
- Secure storage configuration
- Secrets management
- Logging and monitoring
- Basic governance
- Cost awareness

---

## Roadmap

### Phase 1 — Planning

- Define architecture
- Create resource naming convention
- Define security objectives
- Estimate cost

### Phase 2 — Core Azure Resources

- Create resource group
- Create virtual network and subnets
- Create network security group
- Create Windows VM with restricted access

### Phase 3 — Security Controls

- Configure RBAC basics
- Create Key Vault
- Create secure Storage Account
- Enable basic logging
- Add Azure Policy basics

### Phase 4 — Documentation

- Add architecture diagram
- Document security decisions
- Add screenshots
- Write lessons learned

---

## Current Status

```text
Planning phase.
```

---

## Notes

This is a learning project. The environment is intentionally small to control costs while focusing on security fundamentals.
I will update this repo as I build each part of the lab and learn from mistakes along the way.
