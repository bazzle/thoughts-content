---
title: The Tinkerer
slug: 2025-12-05
date: 2025-12-05
excerpt: This post is the result of a shower thought, around the verb _to tinker_, and what this means in a Design Engineer context.
tags:
  - design
---

This post is the result of a shower thought, around the verb _to tinker_, and what this means in a Design Engineer context.

A _Tinkerer_ can have negative connotations. An obsessive, an over-thinker, an over-complicator. But I think to tinker is to make the small changes. To iterate rapidly, refine and evolve a product. Rather than reinvent.

I've compiled a few phrases that centre around this thinking.

1. Design is as much about what you take away as what you add
2. Small changes can make huge differences
3. A digital product is impermanent, constantly evolving
4. A great design lands through iteration, not reinvention
5. What is the smallest change I can make?
6. What are the quick wins, the low-hanging fruit
7. Abandon the ego, stay humble

## Tinkering for the web

A website or app is modular — an aggregation of composable parts. A perfect medium to add to, to take away from, to modify, to refactor, to retest, review, to _tinker with_.

The Tinkering mindset can work for any design discipline. But it works _particularly_ well in the web medium, and more broadly software development. Unlike graphic design, or interior design, where the designer can only tinker during the design phase. The impermanence of digital products allows for ongoing design iteration as more is understood about user needs, how users interact with the product and the constraints of the technical implementation. The agile methodology favours tinkering.

## Look and feel

Tasked with improving an interface, giving it some polish, making it more user-friendly — the Tinkerer would figure out the smallest changes that can make the biggest impacts and best outcomes. That could be taking something away as much as it could be adding something new. Stripping back, zooming out, reviewing.

> "Good design is as little design as possible." — Dieter Rams

My approach that is aligned with this mindset is to add minimal but impactful visual and interactive flourish, along the lines of what I call _The subtle art of making things POP_ — the restrained use of typography, hierarchy, animation, colour, white space and other design principles to create the impact, or emotional response that is required.

## User-centred design

If some user testing informs that a piece of the UI is not sufficiently serving its purpose, then the tinkerer mindset would be to make the smallest changes to address that problem.

## Development

The Tinkerer wouldn't build a component and ship it in one go, but divide the work up into small chunks which can be individually tested and described in their commit messages. Using git introduces necessary friction to tinkering, by compelling the developer to write commit messages, branching code they want to tinker or experiment with, keeping the original one clean.

A website or app is made up of individual composable parts that can be adjusted in isolation, without affecting anything else. Again lending itself to tinkering. Each component owns its own behaviour and its own appearance. Change one thing without breaking another. The architecture gives you permission to iterate.

To describe Tinkering as being exclusively concerned with the small changes is not correct. It is not the _small_ change to achieve a certain goal, it is the _smallest_ change, which might be in itself a relatively large change. This is all to say that the tinkerer wouldn't shy away from suggesting a website redesign for example, if that is the most appropriate thing to do.

## The impact of restraint

The Tinkerer rejects the assumption that big changes must be made to achieve the big impacts a client is asking for. To emphasise this point, let's look at music. Brian Eno's _An Ending (Ascent)_ is a very impactful piece of music, despite the fact that it's just a sustained tone with some slow harmonic drift. Even though audiophiles will argue it's a very complicated and nuanced piece, to my ears the merit lies in its simplicity and restraint.

## Practical examples of tinkering

### Optimising an interface for a newly identified user need or persona

I'd find a way to satisfy the need without introducing new screens and user journeys, only doing so if necessary. This way, the product evolves slowly in response to changing user needs.

### Improving the usability of an interface following an accessibility audit

Simply remediating WCAG violations improves the interface for everybody, not just users with disabilities. From there I can address instances where best practices have been overlooked.

### A website refresh to go with a new content strategy

I'd seek to figure out how I can present the new content as well as possible with what already exists. An adjustment of a single font property and a few styling rules — loosening that line-height, reducing the line length, or increasing the white space — might make a massive improvement to the presentation of content on a web page.

### A new build

Involved in a new build project pre-launch, there are a few principles I'd follow which are in line with the ethos of the Tinkerer.

1. Modularity — keeping components small, focused, and easy to adjust in isolation.
2. Clear boundaries between concerns, global and component-level styling and keeping data handling separate from presentation logic. This ensures components can be tinkered with easily without affecting other components.
3. Workflow — chunking up what needs to be done into the smallest sensible tasks, keeping Pull Requests small in scope.

## To conclude

The Tinkerer is not about doing less. It's about doing the _right_ amount. Finding the smallest lever that produces the biggest shift, and having the restraint to stop there. It's a mindset that values clarity over cleverness, iteration over reinvention, and humility over ego.

Whether it's a subtle animation that brings an interface to life, a spacing tweak that transforms readability, or a commit that addresses one thing well — tinkering is the quiet, deliberate work that compounds over time.

The best digital products aren't the ones that were built perfectly in one go. They're the ones that were tinkered with, continuously, by people who cared enough to keep looking.