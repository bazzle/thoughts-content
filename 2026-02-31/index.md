---
title: February
slug: 2026-02-31
date: 2026-02-31
excerpt: House move, building and tinkering
tags:
  - Month notes
---

We moved into an apartment in an old Victorian block. Creaky floors, paper thin windows, peeling paint and ceilings about a mile high but with no lack of personality. Other than moving home, I've been:

* Playing around with Storybook
* Using it to host my personal design system, which I'm tentatively calling Debazzled
* Refactored some components in my design system for composability
* Created [MegaTabs prototype](2026-03-13)

### Reflections

It's funny how one thing leads to another. When I created the prototype, I thought "Why don't I use the styling and components from my personal website" I had already made my Design system repo, and added it as a submodule to my website repo, so I thought it should be easy to do the same for the MegaTabs website.

Thinking about components being used in different contexts led me to integrate Storybook. I spun up a new repo with Storybook installed, which prompted me to think more critically about component composability. I realised the components I'd built for my personal website were tightly coupled to it — fetching data and consuming context internally rather than receiving them via props. This goes against the principle of separation of concerns in component-driven architecture, where presentational components should be agnostic to their data source.