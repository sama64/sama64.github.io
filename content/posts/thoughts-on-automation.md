---
title: "Random Thoughts On Automation"
date: 2024-09-28T01:02:47-03:00
description: "the industrial society and its consequences blah blah"
draft: false
toc: false
images:
  - post-cover.png
tags:
---

Historically, total economic output has been bottlenecked by human labor availability, with capital and tools acting only as multipliers.

From an economic perspective, humans do two things:

- Consume
- Produce

The economic output formula looks roughly like this.

**_Number of humans_**  x  **_Efficiency_**  =  Economic Output

Efficiency is a relative measure assigned to the tools humans have used throughout history to complete tasks that produce something of value.

This is obviously a simplification, but it captures the historical constraint: tools amplified humans, they didn't replace them.

The human has historically been at the core of the economic production unit. You can only go so far by upgrading your workers' tools. Eventually to scale you need more hands.

That might change.

## Agents 10x the economy

For the first time in history, we’re reaching a point where humans will not be the only thing on earth that can reason and can both produce, and consume.

A basic example of this are customer support agents. These agents can hear a customer’s complaint and plan how to solve it. Some agents have the capability of spawning new instances to work on specific parts of the problem.

In the example above this agent both uses energy (consuming energy, compute, bandwidth, or other agents' outputs) and produces an economic output on its own by retaining a customer.

Agents can plan the demand of resources to produce an economic output. This is way different from all the other tools humans have used throughout history.

As time goes on the level of human intervention will go down. The share of humans in the loop will drop, and since production requires work, machines will also increase their share of demand from other machines.

Some possible examples:
- Infrastructure agents buying compute.
- Datacenter planning agents buying hardware, energy, land, etc.
- Logistics agents contracting other logistics agents.
- Trading agents hedging other agents.

Mid-term, human demand will still be at the core of the total demand of the economy, but machines will expand the economy so much to satisfy human demand that the humans in the loop will be reduced drastically. 

## Agents need to be reliable for it to work

For agents to be able to exponentially expand the economy they need to be reliable.

Currently the failure rates of agents are pretty bad even on basic tasks that look to be perfect for LLMs. Like customer service for example.

The set of tasks that the machine is allowed to do will increase as the failure rate of adjacent tasks decrease. And as the set of tasks trusted to agents increase, the effects of this will be felt exponentially once deployed into the physical world.

Why? Because agents will generate demand for other agents unlike what happened with all other human tools throughout history. 

So in the end adoption will depend on reliability (failure rates dropping for any given set of tasks).

## The self-replicating machine

Imagine you have a machine that receives energy, and outputs >2x the economic value you put in.

Those are very profitable agents. If the machine can plan to output more value than it receives it means that the number of machines in existence can and will grow exponentially if left alone and legislation allows, rather than actively constraining replication.

It has a big economic incentive to do so.

## How to make AI agents reliable

How do we make organizations (companies, nations, communities, etc) be robust?

Given that they're composed of multiple people that could be malign or incompetent, why do these still work?

in practice, this works mostly through redundancy and internal competition, not correctness.

We set a system of incentives that limits the action of individuals, and makes them control and police each other.

But that alone won't get us to acceptable reliability. Even in organizations, if everyone is incompetent, you can't get any meaningful work done.

So we need to increase correctness too. And to do so we need to provide the right environment.

At the point where AI can logically reason through real world facts it becomes a system where abstract ideas can fit together in a constrained set.

If we have a set of coherent facts, then it means there is a constrained set of conclusions that can be determined.

For AI to be coherent on the real world, we need to find a good way to represent abstract ideas in a way that’s grounded in the real world.

It needs representations of abstract concepts and a way to test those representations against reality.

It needs a closed loop of improvement where it evaluates reality based on real world output.

## Simulations will teach machines how to reason

Gathering real world data and letting the machines test their reasoning on the real world would be too slow or insufficient in practical terms.

It is now possible to simulate detailed worlds with enough resolution to teach algorithms how to perform certain tasks.

We need to do the same for reasoning. Machines should be able to evolve in a dynamic simulation where they can learn physical causality and long-horizon planning. The model needs to learn with delayed rewards.

## It is being done right now

There are multiple companies right now teaching models to operate robots and perform tasks using physics based simulations. Once you have an environment with a way to objectively measure success that approximates your target task in reality, it's just a matter of time and compute given any modern architecture.

Architecture breakthroughs will only accelerate this process and in most cases make them economically feasible.

I think the bottleneck is not the current architecture alone but economics: compute cost, energy and incentives.

New compute generations and architecture breakthroughs will make possible to develop meta-cognition. This will accelerate development by orders of magnitude.

We might have the technology but it's still not yet economically feasible. 

My bet is that we will in a few generations.