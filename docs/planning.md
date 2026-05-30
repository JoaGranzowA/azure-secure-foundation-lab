# Planning

## Main idea

The idea of this project is to build a small Azure environment and use it to practice cloud security basics.

I don't want to just create resources. I want to understand why each resource exists, what risks it can have, and what basic security controls I can apply.

---

## What I want to build

For the first version, I plan to use:

- One resource group
- One virtual network
- One subnet
- One network security group
- One Windows virtual machine
- One storage account
- One Key Vault
- One Log Analytics workspace
- Some basic Azure Policy practice

This may change as I learn more.

---

## What I want to practice

### Resource organization

Use a resource group so the lab is easy to understand and clean up later.

### Networking basics

Create a virtual network with one subnet; just the necessary in this case.

### Access control

Start learning how to use RBAC and avoid giving more permissions than needed.

### Secure access

Avoid exposing resources unnecessarily, especially the virtual machine.

### Storage security

Create a storage account and review basic security settings like public access and secure transfer.

### Secrets management

Use Key Vault to understand how secrets should be stored instead of keeping them in plain text.

### Logging

Use Log Analytics to start learning how Azure resources can send logs to one place.

### Governance

Try basic Azure Policy rules to understand how cloud environments can be controlled.

### Cost control

Keep the lab small and delete or stop resources when I am not using them.

---

## Naming Convention

rg-securelab
vnet-securelab
snet-securelab
nsg-securelab
vm-securelab-win
stsecurelab01
kv-securelab
law-securelab
budget-student-lab

---

## Cost notes

Since I am using Azure for Students credits, I need to be careful with costs.

My basic rules:

- Avoid expensive services
- Stop or deallocate virtual machines when I am not using them
- Delete unused resources
- Use a budget to track spending
- Keep the first version of the lab small

**Estimated Cost:** Using Pricing Calculator I set an estimated monthly cost of $0.49; I don't need a lot of resources, so I set everything to the minimum (Storage Account capacity, Transactions, VM hours, and more).