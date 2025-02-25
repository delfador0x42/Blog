---
description: A very good EDR
---

# Ideal Endpoint Detection & Response Tool

You think that there are some magical devices that you don’t

know about that make up the internet, but you’d be wrong.

The internet is essentially workstations, switches, routers,

and servers. That’s it. Though they be big and small, though

they have various configurations. That’s it. No magic.

When thinking about how packets are routed across the

internet, it can seem quite mysterious when the packet

crosses your home router, but it really isn’t. There are no

magical devices past your home router; it’s just more

routers and switches and servers. The routers have their

routing tables updated in various ways and servers

configured for various purposes. But it’s important to stay

grounded to the real world, and not think about the internet

as an arcane thing.



It’s important to keep in mind that every technology used in

the internet, the various protocols, the various hardware

devices. Are all essentially solving the same problem. How

do I get information from point A to point B, regardless of

whether point A and B are 5 feet apart or 5 million feet

apart.



Don’t get lost in the sauce, remember the technology is

solving an aspect of this problem. How to get information

from point A to point B. It’s easy to get abstract about

this stuff but it’s important to stay grounded in how things

really work, so when you get lost or confused about a

technology, just think about the problem the technology is

trying to solve and try to think about how you would solve

the problem if you were the engineer designing the

technology. You’ll likely come to the same solution as the

engineer who made the technology and understand why things

are the way they are; or you’ll think of another way and are

then able to compare and contrast solutions, perhaps even

find a better way. This is in fact how innovation occurs and

things are done.



The problem my EDR is trying to solve is the age old "How do you find an A-game APT in your network?"



&#x20;The basic idea is that you're correlating every process with every network connection with every service. This is ideal for internal infrastructure where you have workstations connecting to internal services but is still very good in every other case.

The flaw with this edr and every other edr is that Actors can use valid CDN infrastructure as C2. Correlating a process with each network request helps to validate this, but if the APT is using a rootkit to hide an injected .dll/.so/.dylib into chrome and chrome is making a network connection to a valid CDN, this would be hard to catch. The way to catch even this is to have a transparent proxy in front of every network request through an inline tap and you validate every network request made. Even if you don't catch the bad guy you'll at least steal all their tools when they op.



This \\\* is \\\*  the end state for any and all network defense. If you implement this you will have as close to perfect defense as you can get. The good news is that when you implement this, even if you don't catch the bad guys you will at least catch all their tools and exploits as they hack your network.









