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

Infrastructure automation helps an organization optimize everyone's work, meet business targets and ensure the system can be resilient and faultless.

It is done through IaC (Infrastrure-as-code) approach, where the infrastructure is defined in source code using frameworks, such as Terraform or Ansible.

## Who?

This is set of best practices from a open community.

Everyone is welcome to contribue through pull requests or issues on [rabbids-incubator/infra-automation-best-practices](https://github.com/rabbids-incubator/infra-automation-best-practices) repository.

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
