![](https://raw.githubusercontent.com/CrowdStrike/falconpy/main/docs/asset/cs-logo.png)

# Cloud Integrations

This repository provides an overview of the various open-source projects created by the CrowdStrike Cloud Integrations Solution Architect team. These projects range from integrations that facilitate cloud partner-specific solutions to Falcon sensor deployment across virtual machines, containers, and Kubernetes workloads, as well as other tools designed to help customers and partners extend the capabilities of the CrowdStrike platform.

## Table of Contents

- [Cloud partner integrations](#cloud-partner-integrations)
- [Falcon sensor deployment](#falcon-sensor-deployment)
  - [Configuration Management tools](#configuration-management-tools)
  - [Scripts](#scripts)
  - [Kubernetes and Containers](#kubernetes-and-containers)
- [Extending the Falcon Platform](#extending-the-falcon-platform)

## Cloud partner integrations

The table below outlines the primary repositories that consolidate various integrations for each cloud partner. To learn more about the specific integrations available for each partner, please visit their individual repositories.

| Partner | Description |
| ------- | ----------- |
| [AWS](https://github.com/CrowdStrike/Cloud-AWS) | This repository provides a  overview of our integrations with AWS, featuring key services such as AWS Verified Access, Amazon S3 bucket protection, and AWS PrivateLink. It also highlights integrations with SSM Distributor, enabling cloud-native sensor automation, and Amazon Built-in, which streamlines the CSPM registration process and bundles our cloud-native sensor deployment solutions for easier implementation. |
| [Azure](https://github.com/CrowdStrike/Cloud-Azure) | This repository provides an overview of our integrations with Azure, including cloud-native sensor automation via VM Extensions and VM Applications, and Azure Blob storage protection. It also features seamless integrations with Microsoft Sentinel, enabling advanced threat detection and response capabilities within your Azure environment.|
| [Google Cloud](https://github.com/CrowdStrike/Cloud-GCP) | This repository provides a detailed overview of our integrations with Google Cloud, including cloud-native sensor deployment through VM Manager OS Policy, Cloud Storage protection, and integrations with Chronicle.|

## Falcon sensor deployment

The sections below provide an overview of the configuration management tools, scripts, and other projects that facilitate Falcon sensor deployment across virtual machines, containers, and Kubernetes workloads.

### Configuration Management tools

| Tool | Description |
| ---- | ----------- |
| [Ansible](https://github.com/CrowdStrike/ansible_collection_falcon) | Our certified Ansible collection automates Falcon sensor deployment across cloud and on-premises environments. It uses playbooks to streamline the process, ensuring consistent and reliable deployments with minimal manual effort. |
| [Chef](https://github.com/CrowdStrike/chef-falcon) | Our Chef Cookbook allows you to automate the deployment of the Falcon sensor by defining policies as code, ensuring consistent and scalable installations across your infrastructure. |
| [Puppet](https://github.com/CrowdStrike/chef-falcon) | Our Puppet module allows you to automate the deployment of the Falcon sensor by defining policies as code, ensuring consistent and scalable installations across your infrastructure. |

### Scripts

### Kubernetes and Containers

## Extending the Falcon Platform
