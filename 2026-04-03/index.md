---
title: MegaTabs
slug: 2026-04-03
date: 2026-04-03
excerpt: For a long time I’ve had an idea in my mind for how desktop browser tabs should work. It wasn’t a sudden light-bulb moment, more of a recurring nagging in my mind, asking “why hasn’t this been done yet?”
tags:
  - Showcase
---

<PostImage src="signpost.jpg" alt="Signposts with signs pointing to various websites. Google, x.com, localhost" />

TLDR: I made a thing. [Megatabs — How browser tabs should work! (prototype)](https://megatabs.netlify.app/)

For a long time I’ve had an idea in my mind for how desktop browser tabs should work. It wasn’t a sudden light-bulb moment, more of a recurring nagging in my mind, asking “why hasn’t this been done yet?”

Here’s the problem. I often get drowned in browser tabs. And it’s not just me. It’s a regular theme of small-talk when I’m on screen shares with people. I call it the **chronic overconsumption of tabs**.

Opening a new tab is effortless, managing them is hard. When browsing, hitting `cmd+click` on a link opens a link in a new tab. When going down a rabbit hole, this often means the subsequent few tabs are branches of that tab. I might be looking at a wikipedia page on one tab, which, a few minutes later has sprouted to multiple tabs branching off the original one — *and* have YouTube open on another tab from which I've spawned multiple new tabs.

Most people seek order from chaos. There’s psychological studies relating to how we like to put things in boxes/buckets. Gestalt principles — particularly the Law of Proximity and the Law of Similarity, explain the visual side of why grouping feels intuitive. Hick's Law states that a person's decision time depends on the number of choices they're given — more visible choices, more cognitive load. An overabundance of choice leads to paralysis. “I’ve lost track of what tabs are what, I’ll just close the whole window and start again”

There is a strong case for a feature that allows for grouping of tabs. Most major browsers do have tab groups. However, grouping them is an extra step, a few extra clicks, a little more cognitive exertion when we may already be maxed out by whatever it is we’re working on.

**And here’s my idea**. Why not Introduce the ability to group tabs as we open them, and in the process introduce parent/child relationships between them. Hitting `shift+cmd+click` would open a new *child tab* in a row below. Kind of like how a website *mega-menu* works (hence the name).

With this, there’s no need for extra steps to organise tabs, they are organised on the fly while browsing. Compare the user journeys between the tab grouping interaction on Chrome on macOS and that of MegaTabs: 

### Tab groups

1. `cmd+click` on links to open them in new tabs
2. `shift+click` or `cmd+click` on tabs to select multiple
3. right-click > "Add tab to new group" to group them horizontally within the tab row.
4. Name group

### MegaTabs:

1. `cmd+shift+click` on links to open a new child tab, which opens in a row below.

An organised browser tab stack, with each tab contain in relevant buckets, materialises with little cognitive overhead. One interaction instead of four.

Some more rules this would work by:

* Closing parent tab also closes child tabs  
* Only two levels or hierarchy, parent and child  
* `Cmd+click` can be used to open sibling tabs, like current browser behaviour.

## **A prototype**

This is an itch I’ve been wanting to scratch for a while. But never got round to working on a prototype. Thanks to my agentic friend, Claude. I was able to get one up and running and published live in an alarmingly short space of time.

<a className="button" href="https://megatabs.netlify.app/">Launch prototype</a>