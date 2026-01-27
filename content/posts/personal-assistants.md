---
title: "How Clawd Found Me A Girlfriend"
date: 2026-01-26T02:41:23-03:00
description: "why is the shiny new thing kind of a big deal"
draft: false
cover: "posts/images/clawd.jpg"
toc: false
images:
  - /posts/images/clawd.jpg
tags:
---

 okay I’ll admit it: clickbait. no LLM found me gf or bf _(yet)_

 so clawd is the shiny new thing on X this week. so what? why is that interesting?

 I think this new wave of adoption is going to warp pricing + reliability in ways people aren't pricing in yet. 
 
 so let’s discuss that instead of why I don’t have a partner ◝(ᵔᗜᵔ)◜
 
 # what's so interesting about clawd adoption?

 we've seen a massive wave of adoption of this new harness for LLMs.

 so what makes this new thingy so interesting? why shouldn't we just dismiss it as the new shiny thing on X?

 freedom to choose.

 unlike most (mainstream) LLM powered applications, it allows the user to swap to any given model and to leverage the capabilities of agents that have been possible for a while, but weren't felt by the majority of AI power users. even the ones using claude code.

 the thing with clawd is that you _can_ own your data, even if you don't right now. or at least you have the possibility.

 why do i say this? clawd lets you use any LLM provider, and holds your data in whatever device you're running it on. it also holds the credentials to all the services you connect it to. _(yes, scary)_

 so even if openai, anthropic or whoever has the hottest SOTA this week goes down, you can just swap to another model. so if you’re filthy rich you could just host some open-source SOTA yourself and keep it running even if we nuke each other out for some time.

 this way of using LLMs by owning the harness rather than borrowing it will drive some changes.

TLDR:
 1. Providers will price this in.
 2. Models will become more reliable.
    
 # providers will price this in
 
 if you didn't know it already let me break the news to you. the AI industry is heavily subsidized by almost anyone who'll lend them money by selling them the promise of a path to profitability in the future.

 that's why Microsoft burns cash like you could just print money.. oh wait. sorry, I meant that they burn money like Microsoft _owned_ the federal reserve.

 it's a long-term bet. it's an arms-race that requires patience and a huge pile of cash, or rather a pile of heads willing to lend you that cash.

 so how do they even convince those heads to lend them money for a completely uncertain endeavor?

 the pitch is basically: _"subsidize usage now, capture the workflow, monetize later."_

 if you don't own the harness, you don't own the user. and if you don't own the user, those subsidies look less like strategy and more like lighting money on fire.
 
 and the 'asset' they're trying to amortize is your model: you know, that massive pile of floats (weights) that can be held on an SD card and costs dozens of billions, or even hundreds of billions to train. and can be just copied infinitely.

 so we don't really know how much cash they're burning vs revenue.

 but using an h100 for a whole day for $200 a month? that's a steal, right?

 bc it kinda is, there's no way they're making money right now. everyone knows this.

 everyone on X and their mom are posting on how to use the OAuth credentials of low-price/high-quota plans to avoid paying hundreds or thousands in api credits.

 all of that cash they're burning?
 all of that is so you use their harness, buy into their ecosystem and they collect data about how you use it for fine-tuning and improving their models. that’s their moat. 

 **_or at least that must be what they must tell to their investors_**

 how do you think they're gonna justify to their investors subsidizing **_you_** if they don't own the harness you use and you give them scattered usage data?

 I mean, you use their platform so they _do_ have your data when you generate tokens, but you can just switch to another provider that has a SOTA model without a massive impact in your day to day use.

 this is something that has been said for a while, but now more than ever it's going to be felt in inference providers' pricing.

 that $200 subscription for unlimited model use? who knows how long it's going to last.

 that awesome chinese model that offers 20M tokens per day for $20 a month? gone. _(eventually, depending on adoption speed)_

 some providers subsidize API prices more than others, but if the dozens of billions are to keep rolling for model training, new promises will have to be made, and some hard numbers might be needed to convince _the heads_.

 so we will probably see unlimited or high-usage flat tiers going up or disappearing, and API prices going up. my bet is before 2027.

 # all models will be more reliable and secure in high-value tasks for real users
 
 yes, we do have some standards at this point to establish how a model should talk to a tool, or API (ex: MCP, openai standard), but the agentic flow and the way they perform tasks are not the same along most providers. and the range of tasks each model can do differs.

 some models perform agentic tasks better than others based solely on the harness. for example codex performs way better on the codex-cli harness than on say claude-code or opencode.

 the cool thing with apps like clawd is that it will generate new benchmarks of real high-value tasks for the end users that all providers will try to optimize for.

 if it ends up being something people keep using companies are gonna end up training on that data and optimizing for those use cases.

 so we will end up with a very robust ecosystem where agents can reliably perform a lot of tasks users really want done by their agents daily.

 it will enforce a soft-default standard on how agents should act, and what minimum range of tasks a model should be able to bring to the table to even be considered SOTA-ish.

 # the security tradeoffs won't turn off mainstream adoption

 since clawd got so popular a lot of inexperienced or non-technical users tried it. a lot of vulnerabilities were discovered and a lot of people got hacked.

 lots of people are getting hacked, and that _will_ keep happening. but i don't think this will be a turnoff for adoption. there's so much to gain that people won't care the tradeoff.
 
 ofc this also means that there are going to be a lot more guardrails to approximate 'foolproof' usage of these tools. and eventually security oriented clawdbot copies will be made into products for non-technical people.

 guardrails will be tested in the real world and will get more and more robust.

 # the best thing about owning the shoggoth harness :D

 so I wanted to have a personal assistant for gamification of goals for some time.

 never took it to a place where it was a real project or product at all.

 but the idea was, eventually I want to be having a personal coach with a personality sitting in my home. not in some data center where all my personal data is exposed and can be taken away. I want it to be _mine._

 but then, reality check: any open-source SOTA model needs a big GPU, and that means to invest a lot upfront, for a model that might be mediocre, and may be unusable (at that time llama 3 or equivalents were the only options).

 so the question is, how do I make this today while preparing for when I _can_ have this at home?

 make the whole car and borrow the motor.

 make your own harness. you own* the data, you can choose the provider dynamically, and you choose what goes into the model vs what's just done with scripts to save tokens.

 so I tried building this idea a couple of times, but it never came out very useful, until model gains and standardization of agent tools made my harness kinda useful with most models. still is not as good as the clawd harness.

 so really clawd is what I've been looking for some time made real in this specific point in time.

 and guess what, when hardware gains reach to a level of having a Claude opus 4.5 in your home for the price of a gaming desktop you will just be able to switch providers to localhost and be done borrowing the motor of your car and sending your data to multiple billion dollar companies **_yay ^ ^_**

 so even though _it is_ the flashy new thing, it's a good thing!

 and this new massive wave of adoption is a really good first step on real world agent-reliability and data ownership.
