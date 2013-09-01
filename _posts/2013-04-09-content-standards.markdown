---
layout: post
title: "Content Standards"
date: 2013-04-09 23:47
comments: true
categories: technology cms
---

### Current State of CMSs
Most of the stuff on the internet that doesn't involve transactions fits into a nice generic bucket: Content. Content that is provided by individuals (primarily on social networks and blogs) and then of course, media outlets and companies (primarily websites with supporting social media presence).

The market for providing [Content Management Systems](http://en.wikipedia.org/wiki/Content_management_system) (CMS) is a competitive landscape that includes titans such as [Adobe](https://www.adobecqcloud.com/content/login.html) and [Oracle](https://www.adobecqcloud.com/content/login.html). However, the market is big enough for a ton of players, especially for the SMBs ([Joomla](http://www.joomla.org/), [Drupal](http://drupal.org/) and [Alfresco](http://www.alfresco.com/) to name a few…).

Unfortunately, everybody does stuff differently and switching between systems is a nightmare for all. 



### Standardize The Chaos!
Creating standards across all of these platforms would ease the data migration and alleviate vendor lock-in. There are two standards that have been developed to address these issues:

1. [Java Content Repository (JCR)](http://www.ibm.com/developerworks/library/j-jcr/) (based on [JSR-170](http://jcp.org/en/jsr/detail?id=170)) with [Apache JackRabbit](http://jackrabbit.apache.org/) as its reference implementation 
2. [Content Management Interoperability Services](https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=cmis) with [Apache Chemistry](http://chemistry.apache.org/java/opencmis.html) as its reference implementation 

JCR has been around for longer but wasn't able to get the job done (partially due to politics within the steering committee and the spec's tight coupling to a specific language: Java). CMIS addresses the issues better and aims to tackle the same issue of interoperability.

### Hurray! Mission Accomplished! 
Not so fast! If you take a look at the [CMIS adopters](http://en.wikipedia.org/wiki/Content_Management_Interoperability_Services), there are a lot of significant players with large market shares that are missing from the list.

If they already have a loyal customer base, what value do they get by providing their customers an easy path to migrate off of their systems? 

I don't see CMIS doing what it was meant to do, especially for the larger systems as there may be little incentive to adopt the standard and there is no cross-platform CMS governing body that can require and enforce all providers to adopt a standard. 

If anything, customers could be made aware of the specification as the gold standard for interoperability so that they look for it from the get-go instead of as a line item in a complex RFP where interoperability gets a sufficient score for a crappy SOAP service.
