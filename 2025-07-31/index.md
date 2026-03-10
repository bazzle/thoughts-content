---
title: July 2025
slug: 2025-07-31
date: 2025-07-31
excerpt: Github pages and 11ty fun, Processwire and some Knut Svanholm
tags:
  - monthnotes
---
## Week ending 6th July 2025

Weather remains good, went for a cold swim in the English channel. Only just passable swimming weather. Heatwave in the UK, an unimaginable 25 degrees!

- Folkestone Fringe website rescue
- Further edits to my capitalism article
- Build educational website explaining how to start a Bitcoin meetup.

I'm working on a website for Folkestone Fringe a local organisation for putting on art and cultural activities in the area.

They needed me to rescue their site from the clutches of an uncontactable developer. This plays out regularly. Some developer or agency build a website for an organisation, time passes and said developer or agency either goes bust or disappears into the abyss.

She luckily dug out the login to the hosting dashboard. Got into the server, copied out the site files, created a new repo and setup a new git deployment. ProcessWire CMS goodness, (no idea) met them for a briefing and will work on it next week. Very little money, but doing like the people behind it. Well one of them is my wife, so how could I refuse!

Brendan got back to me with some very useful feedback on my capitalism article. I wonder if it's normal for writers to do so many re-writes, and basically never be happy with a piece of writing. I feel like I've got so much to say and cover, it's like the opposite of writers block.

Also working on a website for Simon from [bitcoinevents.uk](bitcoinevents.uk) he's got an amazing [resource](https://github.com/Hodl-Solo/BitcoinEventsUK) for helping people start their own meetups. However it's just a github readme. Simon took up my offer to build this into a website.

I got v1 finished today. Took me longer than expected. I thought this would be a simple build, but oh nothing is simple in web development! I wanted Simon to be able to continue writing markdown to update and create new content. Ok, so we need to convert .md to html

Please not next.js again, how about eleventy. Good pretty straight forward setup, got it working locally in minutes.

Then I realised I needed a separate configuration, to transform paths for my github pages environment. This wasn't straightforward to configure. Ended up using the [Base plugin](https://www.11ty.dev/docs/plugins/html-base/plugin).

Then I realised I need the site to regenerate whenever any markdown files are updated and pushed up to the remote repo. So need to setup a github action to do this on every push.

I created my own repo, and setup the gh pages site, with the plan to eventually drop this code into Simon's repo, ask for admin priviliges to do the configuration on the github side, but then realised that personal repo's don't allow assigning admins. You need to setup an organisation.

Luckily my day job was quiet!

## Week ending 13th July 2025

Funny how Brits complain about heatwaves, when the temperature barely surpasses 27 degress. I say bring it on! This week I've been:

* Having the pleasure of unpicking an inherited website built in ProcessWire. I met up with the ladies at Folkestone Fringe and came out with a to-do list as long as my arm. After enough head scratching, var dumping and chatGPT interrogating, I think I'm nearly there.
* Spending a fair amount of time researching different accessibility certifications, and if I fancy going for them. Will it help me with my job and freelance prospects.
* Caught up with my longest friend Rob after a long while. He's an SEO and digital marketing expert aswell as an AI/vibe coding whizz. His productivity is incredible using tools like [https://bolt.new/](https://bolt.new/)
* Considering doing more with [satoshi-power.com](satoshi-power.com) adding a sat converter. Nice project to challenge myself with, asked Rob about what SEO keywords I could go for.
* Listened to a podcast with my favourite Bitcoin personality Knut Svanholm.
* Argued with buttcoiners on reddit for a bit of fun.

I'm done with ProcessWire! it is not a nice CMS to deal with. I really don't see why any agency would choose to use it and not another open-source one like WordPress.

Some incredible thought bombs from Knut. Particularly around inflation. How the natural state of the free market is deflation, prices go down, the productivity gain is absorbed by our inflationary system, where new printed wealth is funelled into the pockets of the cantillionaires. Nothing I haven't read about in his books, but great to hear again straight from the horses mouth. Knut called Bitcoin a "lovely little headfuck" what a legend.

My friend gave me the idea to use chatGPT to  challenge my Bitcoin conviction. Tell it to take the view of a sceptic and challenge me. I plan to do this when I get over my aversion to uncanny-valley AI.

Still so much on my to-do list.

## Week ending 20th July 2025

Weather doesn't know what it's doing. Warm sun one minute, torrential rain the next.

- Bug fixes and improvements on Folkestone Fringe website. Mildly cursing at ProcessWire. Noticing how much of an accessibility hellscape this website front-end is.
- The above leading me to consider starting a business doing accessibility audits and remediations.
- Further styling updates on my website and this one.
- Found out they do complimentary coffee at my gym. So my evening work-out I can enjoy a nice double espresso! Being unable to sleep that night is an unfortunate side-effect.

Enjoyed walks along the coast listening to my favourite podcaster Knut Svanholm talking about Bitcoin (of course) and other things on Robert Breedlove's show. One point stood out and made me think.

How inflationary government issued paper currency is putting the brakes on what could be exponential productivity growth. 1 to 2 to 4 to 8 to 16 and so on. With taxes and inflation we don't even get to two. He doesn't go into much more depth on this but it has me thinking. If money was not inflationary, and there were no taxes, could productivity exponentially grow year on year?

I guess in the same way that there's a physical limit to how many times a piece of paper can be folded in half, Exponentials always hit a limit in nature, or the top of the S-curve. There's a limit to how much energy and resources can support this kind of growth. But we like to say that it would only take 42 folds for a piece of paper to hit the moon, how many years would it take for us to become a Type III civilisation? 42?

## Week ending 27th July 2025

Nothing much to report on this week. Was a quiet one. Did a lot of boring personal admin, swore a lot at various apps' clear interaction design failures, while I migrated to a new phone and new number. Many of them sending me into 2FA circle of doom. A fair amount of reflecting and figuring out where I want my career to go next.
