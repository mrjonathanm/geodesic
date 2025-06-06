---
title: ABOUT(1) | Geodesic
author:
- Erik Osterman
date: May 2019
---

## NAME

about - About the Geodesic Cloud Automation Shell

## FEATURES

* **Repeatable** - 100% Infrastructure-as-Code with change automation and support for scriptable admin tasks in any language, including Terraform
* **Extensible** - A framework where everything can be extended to work the way you want to
* **Comprehensive** - our [helm charts library](https://github.com/cloudposse/charts) are designed to tightly integrate your cloud-platform with Github Teams and Slack Notifications and CI/CD systems like TravisCI, CircleCI or Jenkins
* **OpenSource** - Permissive [APACHE 2.0](LICENSE) license means no lock-in and no on-going license fees

## TECHNOLOGIES

At its core, Geodesic is a framework for provisioning cloud infrastructure and the applications that sit on top of it. We leverage as many existing tools as possible to facilitate cloud fabrication and administration. We're like the connective tissue that sits between all of the components of a modern cloud.

* [`atmos`](https://atmos.tools) for managing configuration of deployments across multiple environments
* [`aws` CLI](https://github.com/aws/aws-cli/) for interacting directly with the AWS APIs
* [`chamber`](https://github.com/segmentio/chamber) for managing secrets with AWS SSM+KMS and exposing them as environment variables
* [`helm`](https://github.com/kubernetes/helm/) for installing packages like Varnish or Apache on the Kubernetes cluster
* [`helmfile`](https://github.com/roboll/helmfile) for 12-factorizing chart values and installing chart collections
* [`kubectl`](https://kubernetes.io/docs/user-guide/kubectl-overview/) for controlling kubernetes resources like deployments or load balancers
* [`gomplate`](https://github.com/hairyhenderson/gomplate/) for template rendering configuration files using the GoLang template engine. Supports lots of local and remote datasources
* [`terraform`](https://github.com/hashicorp/terraform/) for provisioning miscellaneous resources on pretty much any cloud
* [`tmate`](https://tmate.io) for remote terminal sharing with other engineers (pairing) and collaborative debugging

## SEE MORE

Extensive documentation is provided on our [Documentation Hub](https://docs.cloudposse.com/resources/legacy/fundamentals/geodesic/).
