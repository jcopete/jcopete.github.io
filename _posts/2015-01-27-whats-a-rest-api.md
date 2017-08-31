---
layout: post
title: "What's a REST API?"
modified:
categories: API API Security API Management
excerpt:
tags: [API, API Security, API Management]
image:
  feature:
date: 2015-01-27T20:49:20+01:00
---

This post is a translation from the original I did some years ago here [¿Qué es un Web API?](https://lacabezaenlanube.wordpress.com/2014/10/09/que-es-un-web-api/)

Whenever I’m attending an APIs event, demo or presentation the starting point for all these times is to define what an API (Application Programming Interface) is. Typically defined as the set of procedures and functions that a certain library is offering to be used by other software like an abstraction layer (source wikipedia wikipedia).

This is almost right, but it’s only defining a part of what we are currently understanding as an API, plus all the implications that API term supposes nowadays. This is the reason why I used to call them Web APIs, or lately REST APIs as they should follow the REST Architectural Style ( [Roy Fielding’s doctoral dissertation](http://www.ics.uci.edu/~fielding/pubs/dissertation/rest_arch_style.htm) ).

A REST API, is a set of procedures and functions to Create, Read, Update and Delete (CRUD) business objects. This way a certain business object is exposed over a certain URL (http://example.com/v1/user) and with different http methods ( POST  - Create, GET - Read, PUT - Update and DELETE - Delete ) this business object might be manipulated. 

With web 2.0 boom more and more sites offer not only a better user experience, but an API that allows to execute certain functions or procedures. Taking Twitter API as example, you can tweet from the API and extract information like a list of tweets filtered with certain parameters, or even statistics. This has allowed new business generation over those services (APIs), like certain sites that integrate Twitter, Facebook, LinkedIn, and other social networks to allow marketing campaigns follow up.

Among biggest concerns of business objects exposure to third parties is to know how to properly size the systems underneath the APIs, those that will fuel the new Business revenue channels, which of my partners is making more business out of the APIs, how to authorize users of my platform to create, read, modify or delete from a third party platform, and moreover how to prevent non authorized accesses, non-authorized confidential information exposure, and so on.

Over the base of the basic concerns shown, different mecanisms have been developed to identify API consumers with the usage of tokens, monitoring tooling, automatic reporting over this monitoring, authentication mechanisms (OpenID) and authorization (OAuth) and different policies to define the APIs security.

Will develop these terms, and other related to API Management on following posts.

