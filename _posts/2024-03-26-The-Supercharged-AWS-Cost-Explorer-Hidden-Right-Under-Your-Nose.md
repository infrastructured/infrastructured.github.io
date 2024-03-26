---
layout: post
title: "The Supercharged AWS Cost Explorer Hidden Right Under Your Nose"
date: YYYY-MM-DD hh:mm:ss -0000
categories: AWS FinOps
---
# The Supercharged AWS Cost Explorer Hidden Right Under Your Nose

In their quest to understand and manage their AWS cloud costs, almost everyone leverages the AWS Cost Explorer at some point, and they should! It’s an extremely useful tool for understanding your AWS costs at a high level, allowing you to gain insight into costs across services, accounts, regions, tags, and more. But, as cloud costs grow so often does the complexity of managing those costs.

Wrangling in your cloud costs can be difficult at almost any scale. At smaller scales, companies lack the knowledge and expertise to know which levers to pull to save money and as scale increases so does complexity, often increasing the complexity and expense of optimization activities. Savvy finops practitioners have turned to a set of open-source dashboards called the [Cloud Intelligence Dashboards](https://wellarchitectedlabs.com/cloud-intelligence-dashboards/) from AWS’ Well-Architected Labs. These powerful dashboards enable high-level and granular insight into AWS cost and usage data, but they can also be [intimidating to install](https://catalog.workshops.aws/awscid/en-US/dashboards/foundational/cudos-cid-kpi/deploy) and manage even with the helpful CloudFormation templates, requiring users to understand permissions and services that they may not use currently.