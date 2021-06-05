---
title: Validating a new SaaS idea
date: "2021-05-01T13:06:00.169Z"
description: The worst mistake I made was focussing on the idea and not the problem. The best exercise I did was building the landing page first (i.e. the packaging), writing my value propositions and working backwards to the product.
---

### Don't start with the idea, start with the problem
Stupidly, at the start I fell in love with the "idea" of being able to annotate web pages with comments / feedback and tried to retrofit the feature into existing problem spaces like customer feedback and digital agency tools. I even bought the domain [annotately.io](http://annotately.io/) thinking the product was set in stone and all was left was to validate it.

Thankfully I realised the idea was terrible, I discovered this by doing market research and working on my value propositions. The best exercise I did was building the landing page first (i.e. the packaging) and working backwards to the product.

Here's the steps I took to get to my landing page:

### 1. Market research
I'm not going to pretend to be an expert in validating how much a specific market is worth or who owns what share of said market - I didn't dig that far. What I did do was come up with a list of competitors in a similar space, looked them up on [g2.com](https://www.g2.com/) and made some lists:

1. **What customers would _expect_ as standard:** I looked up all the positive reviews and grouped the common stuff into a list of features customers would expect as standard.
1. **How I could differentiate:** I looked up all the negative reviews and made a list of the things missing from existing products. This was how I could be _better_ or how I could position myself differently for an under-served niche.
1. **How my product experience could be better:** I signed up for free trials for all competitor products. This gave me a feel for how they on-boarded users and what features they focussed on. Seeing how average some products were also helped ease some doubt that I was too far behind building a product from scratch.
1. **How I could _sell_ my product:** I looked up all the competitor landing pages to see what language they were using to describe their products and what their core value propositions were. This again gave me ideas on how to position myself _differently_.

### 2. Come up with my core value propositions
Based on the above lists, I came up with a rough list of features and converted them to value propositions using [Julian Shapiro's guide](https://www.julian.com/guide/growth/landing-pages). This was _really_ time consuming, but it was worth it as I avoided getting tunnel vision on ideas and building things no one wants. The exercise helped me realise some of those features didn't have a corresponding benefit and they got killed in favour of better ones.

### 3. Design and build a landing page
Obviously this part is more straight forward:

* I used [Figma](figma.com) to come up with mockups first. I used to just build the page and keep tweaking the CSS until I was happy, but from experience found there's a lot of waste with that workflow.
* I used [Gatsby](https://www.gatsbyjs.com/) and [Tailwind CSS](http://tailwindcss.com/) to build the page. For anyone that doesn't know Tailwind it's worth checking out for the time it saves making pages responsive.
* I used Google Tag Manager to set up [GA4](https://blog.google/products/marketingplatform/analytics/new_google_analytics/) and [Hotjar](https://www.hotjar.com/). GA4 will help me get insights into the SEM keywords that are driving the highest converting users on my page. Hotjar will help me discover where people are engaged and where they're dropping off.

### 4. Set the first milestone
I need to figure what my distribution channels are and _how_ I can reach my target customers. I'll start with SEM to test the cost of acquisition but I'm going to test some alternatives like [Betalist](https://betalist.com/) (although I'm not expecting high quality leads from there).

> Milestone #1: Interview 10 users in my target market
