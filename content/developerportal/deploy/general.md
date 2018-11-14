---
title: "General"
category: "Deployment"
menu_order: 10
description: "An overview of all the ways in which a Mendix app can be deployed"
tags: ["Deploy", "App", "Developer Portal", "Mendix Cloud", "Cloud Foundry", "Azure", "Docker", "IBM", "SAP", "On-premises", "Kubernetes"]
---

## 1 Introduction

A Mendix application can be deployed in different ways. You can deploy to your local machine for development and testing, you can deploy to the Mendix cloud, Cloud Foundry-based platforms, Azure, AWS, SAP Cloud, or a server you configured yourself.

## 2 Locally

You can click **Run Locally** in the toolbar to run your app locally. Use the **Open browser** button to directly jump to your app running at localhost. If you plan to deploy to the Mendix Cloud later on and your project contains Java actions, you should enable the **Emulate Cloud Security** setting. For more information, see [Java in the Cloud](java-in-the-cloud).

## 3 Mendix Cloud

The Mendix Cloud is the default deployment option when you get started with the Mendix Platform. As an integrated solution, the Mendix Cloud includes backups, monitoring, high availability, and more.

From within the Modeler, you can view the cloud nodes you have available in the Mendix Cloud. You can create a deployment package (MDA) in the Developer Portal, and from there, you can transport it and start running your application. For more information, see [Mendix Cloud](mendix-cloud-deploy).

## 4 IBM

If you create your app from an IBM Starter App, or an IBM Starter Kit on IBM Cloud, then the Developer Portal will lead you through the creation of an environment on IBM Cloud. You can then deploy your app to your IBM environment directly from within the Modeler.

For more information, see [IBM Cloud](ibm-cloud).

## 5 SAP

If you create your app from an SAP Starter App, the Developer Portal will lead you through the creation of an environment on SAP Cloud Platform. You can then deploy your app to your SAP environment directly from within the Modeler.

For more information, see [SAP Cloud Platform](sap-cloud-platform).

## 6 Cloud Foundry

From within the Modeler, you can deploy directly to Cloud Foundry-based platforms. To get started, see [cf-mendix-buildpack](https://github.com/mendix/cf-mendix-buildpack) and [Cloud Foundry](cloud-foundry-deploy).

## 7 Docker and Kubernetes

Mendix can be deployed in a Docker container to provide highly scalable solutions and automated delivery pipelines (CI/CD).

The Docker buildpack is available here: [Mendix Docker Buildpack](https://github.com/mendix/docker-mendix-buildpack) and instructions for using the buildpack are available here: [Build a Docker Image from a Mendix App Project](/developerportal/deploy/docker-deploy).

## 8 Azure

Deploying to a Azure is possible from the [Azure Marketplace](https://azure.microsoft.com/en-us/marketplace/partners/mendix/mendix-pro/). For details on how to deploy, see [Azure: Deploy](azure-deploy).

## 9 On-Premises

To learn how to deploy your Mendix application on-premises, see [How to Deploy Mendix on Microsoft Windows](deploy-mendix-on-microsoft-windows), [How to Install Mendix on Debian GNU Linux](installing-mendix-on-debian-gnu-linux), and [How to Install Mendix on RedHat and CentOS](installing-mendix-on-redhat-and-centos).
