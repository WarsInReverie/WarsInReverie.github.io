---
date: '2025-11-18T03:05:48-06:00'
draft: false
title: 'Big Site Update'
showAuthor: false
authors:
  - "cwiffy"
showTableOfContents: true
showHero: false
---

You won't read it, but the changelog I've written is comically long.

It's past midnight and getting into the early morning as I write this, so I'll keep this rather short. This short devlog is primarily meant as a perosnal landmark to signal when the website's principal update was finalized and deployed. Outside of marking this site's big update, there's not much for my tired mind to explain, outside of some nuts and nooks with the details. I'm too tired to adlib some fantastic prose, so I'll keep this devlog rather frank for tonight.

# What & Why Was This Update?

This has been an implimentation I've been planning ever since I started coding this website with Hugo. I chose Hugo because I wanted to emulate another worldbuilding project called [Vekllei](https://millmint.net/) which also used Hugo. But outside of that, I didn't have a firm vision for what the website should be, or what it'd look like. So, browing the Hugo themes for inspiration, I encountered the Blowfish theme, and immediately was struck with an idea.

The [Blowfish example website](https://blowfish.page/) has an animated background that I really wanted to impliment for this site. When I first saw it, it reminded me of video game websites that showcase their game or a trailer in the background of the landing page. The two examples I took express inspiration from were of [War Thunder](https://warthunder.com/en) and [Nikke: Goddess of Victory](https://nikke-en.com/) —  both of which had a cinematic video running behind their logo or download button. 

{{< gallery >}}
  <img src="/img/refs/WarThunderExample.png" class="grid-w100" />
  <img src="/img/refs/NikkeExample.png" class="grid-w100" />
{{< /gallery >}}

I seen a golden opportunity to impliment something similar when I seen the Blowfish theme. And frankly, I thought it'd be easier to impliment than the parallax partials that's on MillMint. I have no idea how Hobart and Ben R.R. were able to [take the Monochrome theme and go balls to the wall](https://millmint.net/millmint/website/#:~:text=was-,originally,unique) on the millming website. In any case, my objective was to integrate a looping video in this website's index.

Haven't actually got around to doing it until now. I first deployed this website in July, but honestly felt too intimidated to go digging around in the theme's add spagetti of GO and HTML. Not to say that it's all a mess ([Coração](https://n9o.xyz/posts/202310-blowfish-tutorial/) did such a fine job making everything abstract and modular), but I never learned GO nor knew how Hugo handled it bundled with HTML. So, I just deployed the website with the original theme and sat on my idea — my collegiate studies didn't help either.

It wasn't until this past weekend, once Midterms had passed and I was a little bummed out, that I picked up the video implimentation again. It took two days (I started after I finished editing the [project teaser video](/content/media/roblox-teaser/)) but I eventually added the features that I want in this site, chief among them the looping video in the index page.

# What's Next?

This big update finally puts this website into what I'd consider a presentable state, but there's still other goals I'd want this website to reach eventually. Like MillMint, I'd also like to integrate a wikipedia-style section into this site (or a [factbook](https://millmint.net/factbook/) as called on the MillMint site). 

{{< figure
    src="img/refs/MillMint-Factbook.png"
    >}}

That's the next big goal for me, but something I'll do further into the future; I just don't think it's a big priority yet. Right now there's not enough website content that deserves whole-ass wikipedia entries, lest all those articles will be legalese and word salad without any visual references.

With this, I can rest assured that this site is now in a state that I trust that it can stand alone. It has a good landing page that immediately gives visitors an impression, and has some content to pique their interest. The website can stand alone now, without me having to add context when sharing it to people.