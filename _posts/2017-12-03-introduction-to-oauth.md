---
layout: post
title: "Brief introduction to OAuth Authorization Framework"
modified: 2017-12-03T13:21:09+01:00
categories: API API_Management API_Development OAuth
permalink: /Introduction-to-OAuth
excerpt:
tags: [API, API Management, API Development, API Security]
image:
  feature:
date: 2017-12-03T13:20:09+01:00
---

This post is a translation from the original I did some years ago here [OAuth 2.0, autorizando el uso de recursos](https://lacabezaenlanube.wordpress.com/2014/11/02/oauth-2-0-autorizando-el-uso-de-recursos/)

As defined in RFC 6749, the OAuth 2.0 authorization framework enables a third-party application to obtain limited access to an HTTP service, either on behalf of a resource owner by orchestrating an approval interaction between the resource owner and the HTTP service, or by allowing the third-party application to obtain access on its own behalf. We commonly use REST APIs as the HTTP Service, although this RFC is generic for any other HTTP Service that we’re willing to authorize.

OAuth Authorization Framework, stablishes a set of roles to orchestrate the needed processes to finally assign proper rights to a certain user over a resource, under the OAuth Authorization Framework is exactly to determine if the user is the Resource Owner and has given a certain consumer (the app) the proper rights (scopes).

Under OAuth the defined roles are the client, that consumes the resource, the resource server, where the resource is located, the resource owner and the server about to authorize the resource consumption.

In a typical example, the client is a web that we’re trying to access and instead of creating a new account (using my email address), allows me to use my existing credentials in a third party (facebook, google, for example). The resource server could be facebook as well, and the resource owner it’s me. And last but not least the authorization server is facebook itself.

How is the dialog between the different actors finally stablished to allow a certain client the usage of the given resource?

The web I’m trying to access is going to ask the resource owner, myself in this example, authorization to use the given information. In this step usually is to be determined the authorization level, and only those data and/or operations over my profile authorized can be accessed. Finally if I allow my credentials to be used, the client application will present an access token to the resource server in order to access my web.

Using OAuth, in this case the register process is simplified.

