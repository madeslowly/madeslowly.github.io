---
layout: single-post
categories: [ fun ]
title: "Fun with JavaScript"
subtitle: "Can your browser do science?"
date: 2018-06-05
background: 'assets/img/posts/experimenting-with-javascript.jpg'

description: Fun with JavaScript. Is your browser capable of doing science? We try this out with some simple JavaScript and a little bit of physics.

thumbnail: fun-with-js-thumb.jpg

nav: 'dark'

func: drawOpticalTrapData

comments: true
---
<script src="https://cdn.jsdelivr.net/npm/p5"></script>

<script src="{{ site.baseurl }}/assets/js/trapping.js"></script>

<link rel="stylesheet" type="text/css" title="made slowly has all the style" href="{{ site.baseurl }}/assets/css/locals/trapping-with-js.css" media="screen" />

OK, so JavaScript is not the go to language for a scientist wanting to simulate some science. That would be silly. BUT, I'm a nerd, and the thought process of a nerd is as follows;

- Ooo, what's that?
- I wonder if ...
- Wow, it worked, that's so cool.
- Ooo, what's that?

This probably explains why academia moves so slowly, but equally why humans have evolved and progressed to where we are today.

Right, let's get to it. First off, what is an optical trap and why do you care? Optical trapping is a technique where the momentum of a photon is used to control the position of a small particle, often refered to as colloid. Our colloid will more than likely be a few micrometers in size and suspended in some solvent. Now the tricky bit is to get a source of lots of photons (no, really, lots and lots and lots, typically around a million times the global population... every second.) Luckily some peeps sorted that out in the 70s by inventing a thing.

So we have our colloid and our laser and with some optical jigery pockery we can control the position of our colloid. This is good because we can study the behaviour of these micro-enviroments whilst simultaneously being able to manipulate them.

Now we can get to our first 'experiment', trapping a single colloid and recording its movement.

{% include optical-trap.html %}
