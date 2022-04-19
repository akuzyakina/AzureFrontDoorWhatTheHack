# WhatTheHack: Internet happened to my website! 

## Introduction

The Internet is much like water, in one hand an amazing thing that provides life/capability for so much, but in the other hand can be the most destructive force in nature.  Large numbers of users, large size and/or number of resources on pages, malicious activity, site slows down the further away it is, or events triggering massive spikes in traffic are only a few of the problems that we need to adresss.  This challenge based hack is intended to teach you how to evolve a simulated local web site into a globally accelerated and protected web site. 

![image](https://user-images.githubusercontent.com/54835093/164018823-2d110aba-3052-4942-8713-ba9ec75b9d96.png)


## Learning Objectives

In this hack you will be solving the common challenges for customers migrating their websites/webapps to the cloud:

- Getting source code ready
- Provisioning hosting option and deploying the app
- Optimizing performance
- Configuring firewall to secure the website

## Challenges
1. [Fork the code](Student/Challenge01.md)
   - Create/use existing GitHub account to create your own copy of the source code
2. [Publish ContosoMasks to the Internet](Student/Challenge02.md)
   - Provision Azure App Service instance and deploy the source code
3. [Move ContosoMasks closer to users](Student/Challenge03.md)
   - Create an Azure Front Door instance and route traffic to the origin 
4. [Speed up the website](Student/Challenge04.md)
   - WORK IN PROGRESS Implement caching / Use a Static Web Site in Azure Storage and route specific traffic to it.
5. [You shall not pass!](Student/Challenge05.md)
   - Use the Rules Engine in Front Door to filter requests by geography

## Prerequisites
- Your own Azure subscription with Owner access
  - Or a Resource Group with Contributor access and ability to manage [Resource Providers](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/resource-providers-and-types)
- GitHub account 

## Contributors
- Andy Wahrenberger
- Dmitrii Tyryshkin



