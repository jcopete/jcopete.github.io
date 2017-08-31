---
layout: post
title: "API view from API Solutions Architect perspective"
modified: 2017-05-10T21:31:04+01:00
categories: API API_Management API_Development
permalink: /API-view-from-API-Solutions-Architect
excerpt:
tags: [API, API Roles, API Management, API Solutions Architect]
image:
  feature:
date: 2017-05-10T21:31:04+01:00
---

API Solutions Architect is between three worlds, and it might be sliced into three different roles:

+ As an API consumer will search, test and integrate third party REST APIs into existing developments.
+	Is going to be an important part of the Company’s Digital Transformation, by reusing the existing assets like SOA Services as REST APIs.
+	As technically responsible for API exposure will be delivering the right architecture and patterns to be used to deliver great REST APIs.

Taking the API consumer role a Solutions Architect ideally will be searching for REST APIs that could easily be integrated into current solutions. This might be to create API mashups, and thus create added value API solutions, or just to integrate into internal solutions that not necessarily need to expose an external API. What should be needed from his point of view as a consumer?
+	Is this REST API fulfilling the technical requirements?
+	How can this REST API enriched with added value information?
+	Which REST security mechanisms are required to consume this API?
+	How an API Management solution can help my enterprise architecture, by applying scale economy.
+	How to easily integrate into my java / php / js existing development?

On the Digital Transformation role, Solutions Architect is ensuring that the existing assets are reused or refactored properly. The SOAP to REST transformation is not as evident and automated as is currently, and you’re about to need all the wisdom and expertise. What should be considered from this Digital Transformation point of view?
+	What are the existing assets, and which are the possible synergies between them?
+	Which WS-Security mechanisms are required to consume those SOAP Services?
+	How an API Management solution can help me in the SOAP to REST transformation?
+	How can I measure existing SOAP assets usage?
+	What’s the best way to deliver the new assets, and ensure its adoption?


On the other hand, as responsible for REST API exposure there are some other topics that might arise:
+	Is our REST API definition clear enough for others to use it?
+	Are all the rest of items for this product ready: documentation, SDKs, samples,…
+	Which is the maximum capacity that can be offered?
+	Which avg. response times can be fulfilled?
+	Together with Product Owner, consider current version of the API if there is any improvement to be made, and adapt API’s roadmap accordingly.
+	Take advantage of API Management APIs lifecycle management, so validate whether is possible to deprecate/eliminate different APIs.

API Solutions Architects are not only worried about the API itself, but the different underlying assets like services, or microservices, databases, identity providers, etc.

Together with API Management other initiatives might arise, for example related to government of all the different assets related to SOA. This can and will end up in proper impact analysis on a certain REST API, knowing from which consumers might be impacted by a change to which services might be changed.

Other important topic is the performance behavior along the system, this is the reason why proper dashboards (both technical and non-technical) should be provided to gather as much information as possible to detect bottlenecks (slower backend services ranking) and integration with other monitoring services along the company to help create a global picture and help detect those bottlenecks. Typically, API Management solutions provide enough analytics to obtain insights and detect the possible API bottlenecks.
