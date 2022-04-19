# Challenge 4 - Speed up the website

[< Previous Challenge [3]](./Challenge03.md)&nbsp;&nbsp;-&nbsp;&nbsp;**[Home](../README.md)**&nbsp;&nbsp;-&nbsp;&nbsp;[Next Challenge [5] >](./Challenge05.md)

#### Пока есть вопросы относительно такого типа кэширования, но сделать челлендж попробуйте.

## Introduction

Things are going well.  The website is able to handle global traffic well  What else could go wrong?

EXPLAIN CACHING, ADD IMAGE
Caching is the concept of storing a response from your website for a configured period of time. It can greatly increase the end client performance and website utilizations. CDN level Caching caches the ***entire*** HTTP request, including cookies and headers. 
First, take a read of the [What is a CDN?](./whatiscdn.md) article, as Azure Front Door is a Dynamic Site Acceleration CDN Service.  And

## Description

For this challenge we are going to: 
- Configure Front Door to cache static content of your website


## Success Criteria

1. Demonstrate that you have caching enabled.
2. Compare the page loading time between Azure App Service and Front Door endpoints. Is there any difference? Explain to your coach
   - Use https://gtmetrix.com to compare performance. Run test for one endpoint, then click "compare" and paste the second endpoint.
4. Simulate 10-20 requests per team member and show cache hit ratio to your coach. What does cache hit ratio mean?

## Learning Resources

- [TBD](https://docs.microsoft.com/en-us/azure/storage/blobs/storage-blobs-introduction)
- [TBD](https://azure.microsoft.com/en-us/features/storage-explorer/)


