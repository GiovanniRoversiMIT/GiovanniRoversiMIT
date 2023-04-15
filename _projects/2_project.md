---
layout: page
title: A smart dictionary for Passamaquoddy
permalink: /projects/passamaquoddydictionary
img: assets/img/pmq_screenshot.jpg
importance: 1
category: work
---

We are trying to build a "smart" online dictionary for the Passamaquoddy language, based on the open source technology developed at the Arctic University of Tromsø by the [Giellatekno group](https://giellatekno.uit.no/index.eng.html).

The goal is to make a dictionary that will be able to, among other things:
- Generate complete paradigms on the fly for any verb, noun, or other parts of speech;
- Recognize and parse inflected forms, helping users to find what verb/noun/... they're a form of;
- Decompose forms containing several roots (so-called "initials", "medials", and "finals" in the Algonquianist tradition).

Dictionaries like this already exist for other languages, even ones related to Passamaquoddy, such as [Plains Cree](https://itwewina.altlab.app/). 
This is extremely handy for people who want to learn the language.

On the technical side, the infrastructure is based on finite state transducers, formalized in *lexc* and *twolc*, then compiled with *hfst* into functioning programs for morphological analysis. This technology has the advantage of not requiring massive datasets, which don't exist for low-resource languages like Passamaquoddy.