<!--
theme: gaia
class:
 - invert
headingDivider: 2 
paginate: true
-->

<!--
_class:
 - lead
 - invert
-->

# Infrastructure automation best practices

## What?

Infrastructure automation is key in any organization in order to optimize everyone work, be able to meet business targets and ensure the system can be resilient and faultless.

Infrastructure automation is done through IaC (Infrastrure-as-code) approach, where the infrastructure is defined in code using frameworks such as Terraform, Ansible, Chef to deploy it on multiple environments.

## Principles (1/2)

* **KISS** (Keep It Simple): take the time to use the easiest solution possible (vs. KICKME = Keep It Complicated Keep Me Employed)
* **Sharing**: documentation (no knowledge should be in people's head only), presentations, break silos
* **Resiliency**: build highly available systems, any task can be performed by more than one person (fight the "Heroe" mode)
* **State of the Art**: use the latest best practices and technologies

## Principles (2/2)

* **DRY** (code): Don't Repeat Yourself
* **Open source / InnerSource** (model): shared components, everyone can contribute, high quality, ready to use, reusability
* **Craftmanship**: value quality and seek expertise

## Frameworks

* [Ansible](./ansible.html)
* Chef
* Terraform

## Tools

* git
* GitLab
