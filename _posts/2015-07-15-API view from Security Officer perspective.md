---
layout: post
title: "API view from Security Officer perspective"
modified: 2015-08-17T23:31:04+01:00
categories: API API_Security API_Management
excerpt:
tags: [API, API Roles, API Security, API Management]
image:
  feature:
date: 2015-07-15T19:23:02+01:00
---

Advancing from beginning of I.T. we’ve been constructing walls, dams, fences, nonces and weapons to defend outer limits of the company from any attack, and even doing business close to those barriers has been a nightmare.

One of the takes from API Management is to make barriers permeable to allow making more and better business. Anyway this has to be taken totally seriously, permeable is not meaning clear and open, but easy to integrate with by using APIs. And this without making a bigger trouble from security perspective, at the end Business perspective.

Which are the common considerations that a Security officer will keep an eye on when talking about API Management ?

One of the first topics to worry about is the channel security between API client and API server. This is usually managed by using SSL over http, there a couple of elements to take here:

+ Although SSL over http might be found secure, it’s possible to have intruders using MITM (man in the middle) attack vectors.
+ Depending on the case ( internal APIs / partner APIs ), only certain predefined consumers will be allowed to access the APIs.
+ Other interesting axe regarding channel security is the possibility to forbid usage of broken algorithms in SSL handshake.

Once first line of defence considerations are taken, another worries come into scene when exposing APIs:

+ Is API data manipulated secure?
+ Is API data manipulated allowed to be manipulated?
+ Apart from authentication of API caller, course grain authorization and fine grain authorization.
+ What about API data returned, does it contain information that shouldn’t be leaked from our company?

And that’s all, isn’t it?

Life from a security officer shouldn’t be as easy as it seems, don’t forget to check that the devices in exposing those business assets (APIs) are secure themselves, and many other topics that cannot be covered in a single post, stay tunned.

