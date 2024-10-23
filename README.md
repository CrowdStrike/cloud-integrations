![](https://raw.githubusercontent.com/CrowdStrike/falconpy/main/docs/asset/cs-logo.png)

# Cloud Integrations

This repository provides an overview of the various open-source projects created by the CrowdStrike Cloud Integrations Solution Architect team. These projects range from integrations that facilitate cloud partner-specific solutions to Falcon sensor deployment across virtual machines, containers, and Kubernetes workloads, as well as other tools designed to help customers and partners extend the capabilities of the CrowdStrike platform.

## Table of Contents

- [Cloud Partner Integrations](#cloud-partner-integrations)
- [Falcon Sensor Deployment Strategies](#falcon-sensor-deployment-strategies)
  - [Configuration Management tools](#configuration-management-tools)
  - [Integrations](#integrations)
  - [Shell Scripts](#shell-scripts)
  - [Kubernetes and Containers](#kubernetes-and-containers)
- [Extending the Falcon Platform](#extending-the-falcon-platform)

## Cloud Partner Integrations

The table below outlines the primary repositories that consolidate various integrations for each cloud partner. To learn more about the specific integrations available for each partner, please visit their individual repositories.

| Partner | Description |
| ------- | ----------- |
| [AWS](https://github.com/CrowdStrike/Cloud-AWS) | This repository provides a  overview of our integrations with AWS, featuring key services such as AWS Verified Access, Amazon S3 bucket protection, and AWS PrivateLink. It also highlights integrations with SSM Distributor, enabling cloud-native sensor automation, and Amazon Built-in, which streamlines the CSPM registration process and bundles our cloud-native sensor deployment solutions for easier implementation. |
| [Azure](https://github.com/CrowdStrike/Cloud-Azure) | This repository provides an overview of our integrations with Azure, including cloud-native sensor automation via VM Extensions and VM Applications, and Azure Blob storage protection. It also features seamless integrations with Microsoft Sentinel, enabling advanced threat detection and response capabilities within your Azure environment.|
| [Google Cloud](https://github.com/CrowdStrike/Cloud-GCP) | This repository provides an overview of our integrations with Google Cloud, including cloud-native sensor deployment through VM Manager OS Policy, Cloud Storage protection, and integrations with Chronicle.|

## Falcon Sensor Deployment Strategies

The sections below provide an overview of the configuration management tools, scripts, and other projects that facilitate Falcon sensor deployment across virtual machines, containers, and Kubernetes workloads.

### Configuration Management tools

| Tool | Description |
| ---- | ----------- |
| [Ansible](https://github.com/CrowdStrike/ansible_collection_falcon) | Our certified Ansible collection automates Falcon sensor deployment across cloud and on-premises environments. It uses roles to streamline the process, ensuring consistent and reliable deployments with minimal manual effort. |
| [Chef](https://github.com/CrowdStrike/chef-falcon) | Our Chef Cookbook allows you to automate the deployment of the Falcon sensor by defining policies as code, ensuring consistent and scalable installations across your infrastructure.  |
| [Puppet](https://github.com/CrowdStrike/puppet-falcon) | Our Puppet module allows you to automate the deployment of the Falcon sensor by defining policies as code, ensuring consistent and scalable installations across your infrastructure. |

### Integrations

| Tool | Description |
| ---- | ----------- |
| [Falcon Bosh Tile for Tanzu TAS](https://github.com/CrowdStrike/falcon-boshrelease) | This project provides a BOSH release for deploying the CrowdStrike Falcon sensor on VMWare Tanzu Application Service (TAS) to ensure security across your cloud infrastructure.|
| [MSI Installer](https://github.com/crowdstrike/msi-installer) | This project allows you to create an MSI to deploy CrowdStrike Falcon Sensors using native Windows tooling. |

### Shell Scripts

| Script | Description |
| ------ | ----------- |
| [Falcon Scripts](https://github.com/CrowdStrike/falcon-scripts) | A collection of shell scripts designed to facilitate the deployment of the Falcon sensor, work with Falcon Container Sensor images, and assist with migration between Falcon cloud tenants. |

### Kubernetes and Containers

| Tool | Description |
| ---- | ----------- |
| [Falcon Operator](https://github.com/CrowdStrike/falcon-operator) | The Falcon Operator is a Kubernetes operator designed to automate the deployment and management of the Falcon sensor in Kubernetes environments. It provides a declarative way to manage sensor deployment, configuration, and updates, ensuring a secure and compliant Kubernetes environment. |
| [Falcon Helm Charts](https://github.com/CrowdStrike/falcon-helm) | A collection of Helm charts designed to facilitate the deployment of the Falcon sensor and integrations in Kubernetes environments. |
| [Falcon OpenShift Console Plugin](https://github.com/CrowdStrike/falcon-openshift-console-plugin) | The Falcon OpenShift Console Plugin enhances visibility by integrating the Falcon operator and Falcon-protected virtual machines directly into the OpenShift web console.|

## Extending the Falcon Platform

| Tool | Description |
| ---- | ----------- |
| [Falcon Terraform Provider](https://registry.terraform.io/providers/CrowdStrike/crowdstrike/latest/docs) | The CrowdStrike Terraform Provider allows you to manage your Falcon tenant resources, such as Host Groups, Prevention Policies, and Sensor Update Policies using the Terraform. |
| [Falcon Terraform Module](https://registry.terraform.io/modules/CrowdStrike/falcon/kubectl/latest) | The CrowdStrike Terraform Module streamlines the deployment of the Falcon sensor and Kubernetes Protection agent on a Kubernetes cluster using kubectl. |
| [Falcon Ansible Collection](https://github.com/CrowdStrike/ansible_collection_falcon) | The CrowdStrike Falcon Ansible Collection allows you to interact with the Falcon platform beyond sensor deployments. Take advantage of dynamic inventories to combat shadow IT or use the Event-Driven Ansible (EDA) eventstream source to react to near-real time security relevent events in your environment. |
| [Falcon Integration Gateway (FIG)](https://github.com/CrowdStrike/falcon-integration-gateway) | The Falcon Integration Gateway (FIG) is an open-source project that acts as a bridge between Falcon and other security tools by forwarding threat detection findings and audit events from the CrowdStrike Falcon EventStreams API to the backend of your choice. |
| [FCS CLI GitHub Action](https://github.com/marketplace/actions/crowdstrike-fcs-cli-github-action) | This GitHub Action enables you to run the CrowdStrike FCS CLI tool directly in your CI/CD pipeline, supporting the scanning of Infrastructure as Code (IaC) for misconfigurations and security vulnerabilities. |
| [Container Image Scan GitHub Action](https://github.com/marketplace/actions/crowdstrike-container-image-scan) | This GitHub Action allows you to scan container images for security vulnerabilities using the CrowdStrike Falcon platform directly within your CI/CD pipeline. |
