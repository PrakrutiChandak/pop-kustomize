<walkthrough-metadata>
  <meta name="title" content="Google Cloud CI/CD End-to-End Demo" />
  <meta name="description" content="Guide for helping you get up and running with Google Cloud CI/CD" />
  <meta name="component_id" content="101" />
</walkthrough-metadata>

<walkthrough-disable-features toc></walkthrough-disable-features>

# Google Cloud CI/CD End-to-End Demo
This repo demostrates Kubernetes CI/CD with Google Cloud devops tools Google Cloud Deploy, Cloud Build, and Artifact Registry. The example app is based on a simple Python Flask example app named "Population Stats" and uses Kustomize overlays to enable configuration differences across three different environments: test, staging, and prod. 

![Google Cloud E2E DevOps Architecture Diagram (1)](https://user-images.githubusercontent.com/76225123/145627874-86971a34-768b-4fc0-9e96-d7a769961321.png)

## Fork this repo
This demo relies on you making git check-ins to simulate a developer workflow. Fork this repo, or otherwise copy it into your own Github repo. Note, currently this demo only works if you initiate the workflow via Git check-in.

If you've already done that, you can start the setup tutorial.

## Setup tutorial
The following tutorial walks you through all the setup needed to configure Google Cloud components needed to run this demo. Clicking this button provisions a Cloud Shell Editor and launches an interactive tutorial which steps you through the process. Google Cloud account and project required.

[![Open in cloud shell](https://gstatic.com/cloudssh/images/open-btn.svg)](https://ssh.cloud.google.com/cloudshell/open?git_repo=https://github.com/vszal/pop-kustomize&cloudshell_tutorial=tutorial.md)

If you don't want to run the tutorial in Cloud Shell, you can view the md file [here](https://github.com/vszal/pop-kustomize/blob/main/tutorial.md).

# About the Sample app - Population stats

Simple web app that pulls population data based on U.S. address queries. Note, other countries are currently not supported.

Population data gathered from the U.S. Census Bureau [Population Estimate API](https://www.census.gov/data/developers/data-sets/popest-popproj/popest.html). 

Feedback and contributions welcomed!
