# F5 Multi-Cluster Container Ingress Services

## Overview
The Multi-Cluster architecture is a F5 Aliances product shocase and will be part of the F5 Automation Sandbox. This is built by F5 Business Development organization.

## Goal
The Purpose of the multi cluster use case is to show how F5 Container Ingress Services can be used inconjunction with serveral other F5 Aliances integrations to demonstrate conducting an A / B Deployment of a web application.

![E2E Architecture](/docs/images/e2earchitecture.png)

## Prerequisites
Currently some of the set up for this architecture is a manual process. A method to build these POC envornments via the F5 Povisioner is in progress. For this learning materal you will need several prerequisites in place to begin.

- Access to git preferable a valid GitHub account
  - https://github.com/
- A Jenkins Server
  - https://jenkins.io/doc/book/installing/
- A minimum of two openshift clusters
  - https://docs.openshift.com/container-platform/3.11/welcome/index.html
- Two Licensed BIG-IP VE appliances with Best licenses, one per cluster

## Use Case Specific Prerequisites
- Access to F5 Cloud Services (DNS Load Balancing)
  - https://www.f5.com/products/ways-to-deploy/cloud-services/preview
- Access to Equinix Smart Key
  - https://www.equinix.com/services/edge-services/smartkey/

## Getting started

Once the necessary infrastructure is in place users wil be able to run through the automation scenerios via Jenkins to demonstrate a A / B deploymnet scenerio.

The Multi-Cluster  can be used:
- as a self learning tool to get familiar with OpenShift Container Ingress Services for F5 BIG-IP
- to build demos and proof of concepts
- to uderstand:
  - F5AAS Service DNS load balancing
  - F5 Integration with Equinix Smartkey

Follow [Getting Started](http://github.com) for detailed steps on how to build out the A / B Deployment setup.

## Support

This project is a community effort to promote container ingress service automation and is maintained by F5 BD. For any feature requests or issues, feel free to open an issue and we will give our best effort to address it.
