# Challenge 2 - Publish ContosoMasks

[< Previous Challenge [1]](./Challenge01.md) - **[Home](../README.md)** - [Next Challenge [3] >](./Challenge03.md)

## Pre-requisites

- Azure subscription
- Your own GitHub repo with the source code of ContosoMasks

## Introduction

In order for us to get started, let's talk a few basics.  Web Browsers are the general clients used to interact with Web Sites.  For a Web Browser to load a web site, generally you need the following:
- A Domain Name System (DNS) Name
  - This lets your Web Browser take ***www.contosomasks.com*** and turn that into an IP Address to then talk to.
- Something to host your content/website
  - There are lots of choices to run the application code and/or store the JavaScript, CSS, and HTML files.

We're going to setup a copy of the original Contoso Masks website. 



- Azure App Service hosting the **www** Web site of your instance of Contoso Masks.
  - The website will be auto-deployed to the App Service.

Once we get everything deployed, we will take some time and look to analyze the website using your Web Browser's developer tools.  

## Description

For this challenge we are going to:
1. Complete all the pre-requisites
2. Deploy the App Service instance
3. Publish the source code to App Service by setting up GitHub integration
4. In your Web Browser, load up your new copy of www.***SITENAME***.contosomasks.com, where ***SITENAME*** is that parameter you used in 2.iii.  Use the Development tools in the Web Browser to understand how the web pages and resources are loading, where they are coming from, and detail on how each requests loads.

## Deploy the Website 

Use the link below to deploy the solution to your resource group.

[![Deploy the to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmicrosoft%2FWhatTheHack%2Fmaster%2F017-FrontDoor%2FStudent%2FResources%2FChallenge00%2Fazuredeploy.json)

## Success Criteria

- Show that you can load w3af and display the help
- Show the newly deployed resources in the Azure Portal
- Demonstrate that your Contoso Website loads
- Show the "waterfall" of the one of the Images in the Dev Tools of your Web Browser 
- **If time permits, bonus task** modify the source code to change the title from "ContosoMasks" to something new and make sure that title is updated on your website.

## Learning Resources

- [Domain Name System (DNS)](https://en.wikipedia.org/wiki/Domain_Name_System)
- [Azure DNS Service](https://docs.microsoft.com/en-us/azure/dns/dns-overview)
- [How a Web Browser works (video)](https://youtu.be/DuSURHrZG6I)



