---
layout: post
title: "Lightweight markup languages: Markdown and CommonMark"
modified: 2017-09-01T12:31:04+01:00
categories: API API_Management API_Documentation
permalink: /Lightweight-markup-languages
excerpt:
tags: [API, API Management, API Documentation]
image:
  feature:
date: 2017-09-01T06:23:02+01:00
---

A [lightweight markup language](https://en.wikipedia.org/wiki/Lightweight_markup_language) is designed to be easy to create, using any generic text editor, and easy to be read in raw format. It’s a very elegant solution to the typical problem of writing a READ.ME and be able to transform it to any enriched format. Who didn’t wrote first on notepad a set of ideas that finally were the specs document for any kind of software development?

In this sense [Markdown] (https://en.wikipedia.org/wiki/Markdown) is a lightweight markup language with plain text formatting syntax. It has some limitations like:
+ There is not a formal specification, but an implementation (Markdown.pl) by John Gruber.
+ There are some inconsistencies and ambiguities that are not resolved, and thus each of the implementations might not be interoperable.
+ At a certain stage Markdown is considered abandonware.

Due to these reasons [CommonMark] ( http://commonmark.org ) was born as an standard, unambiguous syntax specification for Markdown. It comes with a test suite to validate any Markdown implementation against it, so it might facilitate interoperability and why not a little bit of common sense.

Appart of these reasons, they might convince you or not,  the compelling event to start using Commonmark is that with [OpenAPI 3.0.0] (https://www.openapis.org) Markdown is now substituted by Commonmark.

So the first step is to take the 10 minutes tutorial on [Commonmark’s site] (http://commonmark.org/help/ )
