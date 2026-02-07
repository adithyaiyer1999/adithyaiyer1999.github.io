---
layout: post
title: On tech, research, AI, and maybe the future?
---

I write this on the 7th of Feb, 2026, as Anthropic releases Opus 4.6 and OpenAI releases GPT 5.3, and a large part of the tech world (maybe mostly on Twitter) is letting AI write most, if not all, of their code.

A big reason I wrote this is this blog: [Building a C Compiler with Claude](https://www.anthropic.com/engineering/building-c-compiler).

I transitioned from doing non-tech/consulting/materials science to working in Deep Learning. I have friends who want to make that transition—and young college grads who want to get into tech as a way to do interesting work. This blog is my take on the question: should you? And if so, how will it be different in five years?

## Why people built software before, and why you were paid to build software

I use the term "software" loosely to represent anything digital. This might be a SaaS product, a recommendation algorithm, or a deep learning model.

A company or user has a problem, which usually relates to the inability to find information X or means to acquire/order Y, and your "software" S bridges this gap. People pay you to use it once or monthly. For Netflix (Y = movies, S = Netflix website). For Amazon (Y = product, S = their website). For more SaaS B2B companies like GitHub, Y = code version control, S = GitHub repos/hosting.

You ONLY pay for these SaaS B2B services if you can't build them yourself. This is why Meta/Google don't have a GitHub subscription—they are large enough and have enough money to make one internally. A small company, like Anthropic (3k people), does not. If you want to build such a service internally, there are three things you need:

1. People, whom you have to pay  
2. Time and focus, which you have to allocate  
3. Maintenance: someone has to maintain this service so they can fix it if it breaks  

In the internet era (2000–2024), you (a large enterprise) would pay for a GitHub/Google subscription or hire Infosys to solve these problems for you. In cases where the benefit was small enough (like, say, an observability platform like Sentry), you might build it yourself.

In the new era (today): for small enough software tasks, Claude Code can probably solve all three of the problems.

1. People: you really only have to pay for a Claude Pro subscription, which is $200  
2. Time: Agents run on their own; you only have to review them  
3. Maintenance: Pull requests are super easy to push via Claude Code, so it barely takes time  

Earlier, I might have paid a monthly fee for an observability platform for my software business. Today, I would spend two days "vibecoding" a tool specifically for my business. It doesn't have to be perfect—just good enough for it to work so I can focus on my main business.

If you're building small software that adds marginal value, and it can be done by someone "vibecoding" it on Claude Code in a week, you will be replaced. Period.

It's hard to pinpoint exactly what software gets killed. For instance, a large insurance firm is not going to "vibecode" a Salesforce competitor in a week for their CRM. But that does not mean that a young startup of 10 people won't do it and undercut Salesforce on cost.

The moat of manpower is gone; the only moat is switching cost. If switching away from your product is easy and cheaper, people will do it. AI can write the data transfer scripts to make it easy for competitors. Your codebase is no longer an irreplaceable asset.

## So what is an asset for a company if code is commoditized?

We need to jump to 2029 to answer this question. We do this because models are still improving at a rapid pace, and it makes sense to solve for the case when AI WILL write better code than any human. How will you THEN add value?

A few things come to mind:

1. Solve a problem that code alone cannot solve: think coordinating with physical humans, robotics, operations, etc. Any role which moves goods/creates physical products  
2. Entertainment: Claude can write your code, but Claude cannot watch the latest season of Stranger Things for you.  
3. Niche software: security, privacy, etc  
4. Anything where you trust a human: people hate talking to AI in call centers for complex issues; people still want surgeons.  

Infosys/TCS/boutique IT consultancies: you have a rough time ahead.

Basically, if you're a hard-core coder who spends most of your time building things others tell you to build, you need to move to being the person who decides what to build. Leadership > tech prowess when code isn't a differentiator.

## But won't learning to use AI make me a supercoder—and hence, more valuable?

It took me a while to understand this, but my main realization is: having AI "supercoders" does not mean more software will be needed; it means less software is needed in the future. Super arrogant claim—but let me explain.

We spent the last 15 years building more software, better UI/UX, services to make it easy for humans to use our products. What will change is that in five years, a human will NEVER directly interact with your services. They will interact with an LLM that will relay information/products from your service to the human.

Think about it—why will you need a beautiful UX to book flights, if ChatGPT can just query the Skyscanner API for the information and show you the flight in a UX you prefer (say you are price-sensitive and hate ads)? Dynamic UX, which just presents you information just the way you like and need it, is the last frontier to cross. Once your LLM has the information to book you a flight, you can really ask it weirder questions like "1/2 stop", "no Airbus planes please", "need Jain food", etc.

In a world where unstructured information can be transmitted via tokens, and JSONs are no longer needed, UX becomes a personal choice. It's like having a personal assistant who will only show you what makes sense, not 30 extra buttons.

## Are all tech bros/sis's done for?

I think anyone who ONLY writes code as their value proposition is done for. If you write extremely niche code that AI can't do, you might be safe for a while, but will be irrelevant in 2029 when AI manages to get there.

If you can talk to humans, understand the problems businesses face, and use this free code-generating god to build solutions for non-tech people, you'll be valuable.

If you do more than write code—i.e., scientifically conduct experiments for anything (say, new algorithms, robotics), and just use code as a means to your real value proposition—you'll be valuable.

Lastly, if you work on something people won't trust AI with—even if it's insanely good—like money managers, surgeons, therapists, artists/musicians, "maybe" you're safe. A Porsche is still valuable even if Teslas are better cars, because of the art. Maybe we all need to be artists to make a living in the future.

## Predictions?

I'd be dumb to say there will be no SWEs in the future. I just think there will be 1/5th the number, and they'll mostly monitor the code—not write as much. There's going to be unique value in something human-made, for the same reason hand-crafted chocolate is more expensive.

