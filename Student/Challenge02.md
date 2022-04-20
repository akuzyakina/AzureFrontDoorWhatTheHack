# Challenge 2 - Publish ContosoMasks website

[< Previous Challenge [1]](./Challenge01.md) - **[Home](../README.md)** - [Next Challenge [3] >](./Challenge03.md)

## Pre-requisites

- Azure subscription
- Your own GitHub repo with the source code of ContosoMasks

## Introduction

When it comes to publishing a website to the Internet, we need to keep in mind a few basics:<br/>
Web Browsers (Microsoft Edge, Google Chrome, Mozilla Firefox etc) are the general clients used to interact with Web Sites. For a Web Browser to load a web site, generally you need the following:
- A Domain Name 
  - This lets your Web Browser take ***www.contosomasks.com*** and turn that into an IP Address to then talk to.
- Something to host your content/website
  - There are lots of choices to run the application code and/or store the JavaScript, CSS, and HTML files.

<p align="center">
  <img src="https://user-images.githubusercontent.com/54835093/164078163-e50c3538-a039-4cbb-9277-41e60caa83e0.png" width="550" height="300">
</p>

Fortunately, Azure has one solution (actually, several solutions) for all of the above!

**Azure App Service** is a fully managed platform as a service (PaaS) designed for hosting web sites, web applications, REST API and many other things. 

Key features of Azure App Service:
- Azure App Service supports multiple languages and frameworks - ASP.NET, ASP.NET Core, Java, Ruby, Node.js, PHP, Python and PowerShell.
- DevOps optimization - integration with Azure DevOps, GitHub, BitBucket, Docker Hub, or Azure Container Registry.
- Autoscaling capabilities
- Integration with Virtual Networks <br\>
and dozens of others!

Ok, we've got an option (some kind of Server) to host website. But how to get the code to this server?

Typically, there are several options to achieve that: deploy via FTP, use some IDE plugins, but the most modern way is to use **Continious Deployment** - software engineering approach in which software is delivered through automated deployments. Modern cloud services (such as Azure App Service) provides **out-of-the box functionality** to configure autodeployment of your source code to the App Service instance! 

## Description

For this challenge we are going to:
- Deploy the App Service instance
- Publish the source code to App Service by setting up GitHub integration
- Check out your newly deployed website

## Success Criteria

- Show the newly deployed resources in the Azure Portal
- Demonstrate that your newly deployed Website is up and running

## Bonus task , if time permits
- Modify the source code to change the heading from "Contoso Masks" to something new and make sure it is updated on your website.

## Learning Resources

- [Domain Name System (DNS)](https://en.wikipedia.org/wiki/Domain_Name_System)
- [App Service QuickStart: Deploy .NET Core app](https://docs.microsoft.com/en-us/azure/app-service/quickstart-dotnetcore?tabs=net60&pivots=development-environment-vs)
- [Set up Continious Deployment with GitHub](https://docs.microsoft.com/en-us/azure/app-service/deploy-continuous-deployment?tabs=github)

