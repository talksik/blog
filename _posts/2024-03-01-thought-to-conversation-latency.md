---
layout: post
title: "Thought-to-conversation latency"
tags: [flowy]
---

## The problem
There are many design considerations that were overlooked when various digital communication products/methods are created.

You can't particularly blame specific individuals for this, as they were consumed by a focus on technology and "making it work".

As platforms get older and older, it becomes more and more difficult to change foundational patterns, technologies. People build on top of existing platforms with slight differences, but they fail to re-think the paradigms underpinnings their solutions.

This is similar to what David Deutch explains when it comes to knowledge creation (a tangential but related concept): "...the good explanation is hard to vary. It’s hard to vary because it was hard to come by. It is hard to come by because the easy ones don’t explain much... _Good explanations are hard to find, hard to vary, and falsifiable."_ See his chat with Naval [here](https://nav.al/david-deutsch).

### Let's get practical - modeling conversations
When it comes to digital communication, there is a conventional paradigm that has existed from radios to walkie-talkies to TV to the chat apps of today (iMessage, Slack, WhatsApp). And that is the concept of a "room" or "channel" or "conversation", each containing multiple "members", and having one feed of artifacts (text messages, links, videos, etc) in order.

This by definition entails multiple people meeting in "some other place" to then transmit and post something on a board for other members to see. There are multiple potential explanations for this:
- perhaps it just makes sense from the SQL database layer of organizing information
- people just think it makes sense because it's familiar now

_The nuance problem here is that this paradigm was **not** designed with a focus on imitating real-life interactions._

This is why Slack, iMessage, Facebook Messenger, WhatsApp all look the same. They tend to keep adding features, but that adds even more `latency`. Instead, they have to re-define what a digital conversation looks like.

### The upstream effects of this design
This design (whether we call it bad or not is irrelevant) lends itself to a primary side-effect: poor augmentation of how conversations flow in the human brain. This leads to increased `cognitive load` and `latency`.

Our brains aren't meant to handle 100s of notifications from 20 different active threads in 10 different apps. See ["people are dying for less"]({% post_url 2024-03-01-flowy-why-it-will-work %}) for insight into what is a growing, yet hidden trend.

### On latency
When I want to get to get to someone on Slack, this is the lifecyle:
1. thought comes to mind about x, and I want to get to y person/channel
2. switch from current application to slack
3. find this person in the interface (person/channel)
4. convert thought to written form (conversational natural language to written English)
5. type it out
6. edit it
7. send
8. go back to other tasks

The other person/channel:
9. receive notification and read half of it in the notification banner
10. go to slack app
11. try to understand context by seeing other messages in the history
12. read the message
13. imagine those words coming out of that sender's mouth to better understand it
14. _start the response cycle like above_

_The three problems: text medium, model of conversations, and the protocol/flowy._ Text mediums are not efficient; this is why Slack threads rarely end in **complete resolution** and points get re-discussed in a zoom call later on. I explain the model of conversations and the protocol in `Let's get practical`; this paradigm was not built to be natural and lightweight.

One nuance to consider is that humans are poor at predicting the scope of a conversation. What medium should a thought/discussion be in?
- email person/people
- text thread in slack
- call the person on slack
- schedule a zoom on the calendar
- jump into a huddle right away
- send voice clips within slack?

Do we really know which medium fits best for a conversation about feedback for a presentation, for instance? By having all of these options, we are stuck in a pertual cycle of inefficiency.

We want to build something where the latency is nil, so that people can have a thought and they can immediately relay that thought to the person they are thinking of.

## The solution

To change the foundational structures of a building, you must tear down the building and re-build.

To design something that is `low cognitive load`, we have to focus intensely on the principle of "less is more". **The fastest way to make your boat go faster is to make it lighter.**

We also have to obsess over making communication human to human; without the pattern of "go to some other place to post, notify, and repeat". The idea is to reduce `latency`, and in this case we are talking about `thought to conversation latency`. This is how seamlessly we can take someone who has a thought and who they want to converse with to a real conversation, whether async or sync. In other words, it should feel like the other person is right there.

By making digital communication as human and authentic as possible, you more effectively augment real life conversations and introduce a new paradigm.

I shall add another article to explain a proposed protocol.
