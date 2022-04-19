# WhatTheHack : The Internet just happened to my website! 

## Introduction

The Internet is much like water, in one hand an amazing thing that provides life/capability for so much, but in the other hand can be the most destructive force in nature.  Large numbers of users, large size and/or number of resources on pages, malicious activity, site slows down the further away it is, or events triggering massive spikes in traffic are only a few of the problems **Azure Front Door** addresses.  This challenge based hack is intended to teach you how to evolve a simulated local web site (https://www.contosomasks.com) into a globally accelerated, protected web site with burst offset.

## Learning Objectives
In this hack you will be solving the common problem that websites have with the Front Door services from Azure:

1. Fork the source code
2. Provision an Azure App Service and deploy the website
3. Provision an Azure Front Door 
4. WORK IN PROGRESS Implement caching / Provision a Static Web site with an Azure Storage Account
5. Configure simple/complex routing rules 

## Challenges
1. [Fork the code](Student/Challenge01.md)
   - Create/use existing GitHub account to create your own copy of the source code
2. [Publish ContosoMasks to the Internet](Student/Challenge02.md)
   - Provision Azure App Service to host the website, then deploy the source code to your App Service instnace
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



