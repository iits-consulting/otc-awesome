# Awesome OpenTelekomCloud [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome OpenTelekomCloud (OTC) guides, libraries, tools, and resources. Inspired by [awesome](https://github.com/sindresorhus/awesome) lists.

## Contents

  * [Projects](#projects)
    * [Identity access management (IAM)](#identity-access-management-iam)
    * [Terraform](#terraform)
    * [Monitoring](#monitoring)
    * [Workshops](#workshops)
    * [Useful OTC Helm Charts](#useful-otc-helm-charts)
    * [SDKs](#sdks)
    * [CCE](#cce)
  * [Community Posts](#community-posts)
    * [Events](#events)
    * [Blogs](#blogs)
  * [Tutorials and Courses](#tutorials-and-courses)
  * [Forums and Discussions](#forums-and-discussions)
  * [Contribution](#contribution)

## Projects

### Identity access management (IAM)

- [otc-auth](https://github.com/iits-consulting/otc-auth) - Login through cli via OIDC/SAML/IAM, create openstack config, fetch kube config for CCE 

### Terraform

- [terraform-opentelekomcloud-project-factory](https://github.com/iits-consulting/terraform-opentelekomcloud-project-factory) - modular terraform scripts to automate the creation of OTC projects.
- [terraform-provider-opentelekomcloud](https://github.com/opentelekomcloud/terraform-provider-opentelekomcloud) - The official Terraform provider for OpenTelekomCloud.

### Monitoring

- [otc-prometheus-exporter](https://github.com/iits-consulting/otc-prometheus-exporter) - A Prometheus exporter for OTC metrics.


### Workshops

- [otc-terraform-template](https://github.com/iits-consulting/otc-terraform-template) - A templated project to quickly start using Terraform with OTC. Used for OTC Workshop
- [otc-infrastructure-charts-template](https://github.com/iits-consulting/otc-infrastructure-charts-template) - A Helm chart template for creating OTC Kubernetes infrastructures based on ArgoCD.

### Useful OTC Helm Charts

- [https://github.com/iits-consulting/charts](https://github.com/iits-consulting/charts) - Some helm charts are specifically designed for OTC

### SDKs

- [golang](https://github.com/opentelekomcloud/gophertelekomcloud) - Golang SDK for OTC
- [Python SDK for OTC](https://github.com/opentelekomcloud/python-otcextensions) - The OTC Extensions augment the OpenStack SDK of features and services provided by the Open Telekom Cloud.

### CCE

- [cce-argocd-bootstrap](https://github.com/iits-consulting/charts/tree/main/charts/argocd) - ArgoCD will be auto installed over terraform and installs the first project
- [cce-storage-classes](https://github.com/iits-consulting/charts/tree/main/charts/otc-storage-classes) - auto create storage classes which are encrypted by default
- [rds-auto-init](https://github.com/iits-consulting/charts/blob/main/charts/db-init/README-OTC.md) - manage your databases, schemas, users and permissions by infrastructure as code
- [otc-nginx-ingress-example](https://github.com/iits-consulting/otc-nginx-ingress-example) - An example of setting up an NGINX ingress in an OTC Kubernetes cluster.

## Community Posts

### Events

- [Terraform/ArgoCD](https://community.open-telekom-cloud.com/community?id=community_event&sys_id=589fd667b780f010d15aa7b16b8c02bd&view_source=searchResult) - An OpenTelekomCloud community event focusing on best practices (Terraform/ArgoCD).
- [HashiCorp Vault](https://community.open-telekom-cloud.com/community?id=community_event&sys_id=dc34455cb7587410d15aa7b16b8c0213&view_source=searchResult) - Another OpenTelekomCloud community event focusing on Vault.

### Blogs

- [nginx-cce](https://community.open-telekom-cloud.com/community?id=community_blog&sys_id=08f3fb40132c0190d15ac969a674412b&view_source=searchResult) - How to configure nginx ingress with CCE and Elastic Loadbalancer

## Tutorials and Courses

- [Getting Started with OpenTelekomCloud](https://open-telekom-cloud.com/en/support/first-steps) - A beginner's guide to using OTC. 


## Forums and Discussions

- [OpenTelekomCloud Forums](https://community.open-telekom-cloud.com/) - The official community forum for all things OTC.


## Contribution

Contributions are welcome! Just create a pull request
