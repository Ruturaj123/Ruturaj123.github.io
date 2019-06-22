---
layout: post
title:  "GSoC Evaluation Phase 1"
date:   2019-05-22
desc: "Work completed till first evaluation phase."
keywords: "Ruturaj,Jekyll,gh-pages,website,blog,easy,gsoc,evaluation"
categories: [GSoC]
tags: [Ruturaj, GSoC, Jekyll]
icon: fa-pen-alt
---

## **Rucio: Exascale Data Management**
I have been working on the Rucio project for the past 1 month as a part of GSoC 2019. Rucio is a data management system that provides the functionality to organize, manage and access a large amount of scientific data (in the order of petabytes) using customizable policies. Rucio also provides monitoring and data analytics.

<br>

## **Work completed as of now**
My first task was to create a Username/Password login authentication for the Rucio-WebUI.
The need was to ass the userpass authentication alongside the default x509 authentication. This is because some organizations relied only on x509 authentication while some had username/password credentials. So depending upon the configuration specified in the config file, the desired auth type would be invoked.
The [PR](https://github.com/rucio/rucio/pull/2615) for this task has been merged into the repository.

<br>

## **Work in progress**
Currently I am working on the 2nd task which is to add SSO auth option to the WebUI.
As of now, a new identity type has been added in the core.
The next thing to do is to create a function to login to WebUI with CERN SSO using SAML.

<br>

## **Things Learnt**
For the past month, I have learned a lot about how things work in an open source organization. I learnt to communicate with my mentors, what coding conventions to follow, some new version control techniques like rebasing. I aim to further continue working on the tasks and communicate with the mentors to complete the project on time.