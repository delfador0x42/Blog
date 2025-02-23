---
description: A very good EDR
---

# Ideal Endpoint Detection & Response Tool

The problem my EDR is trying to solve is the age old "How do you find an A-game APT in your network?"



&#x20;The basic idea is that you're correlating every process with every network connection with every service. This is ideal for internal infrastructure where you have workstations connecting to internal services but is still very good in every other case.

The flaw with this edr and every other edr is that Actors can use valid CDN infrastructure as C2. Correlating a process with each network request helps to validate this, but if the APT is using a rootkit to hide an injected .dll/.so/.dylib into chrome and chrome is making a network connection to a valid CDN, this would be hard to catch. The way to catch even this is to have a transparent proxy in front of every network request through an inline tap and you validate every network request made. Even if you don't catch the bad guy you'll at least steal all their tools when they op.



This \\\* is \\\*  the end state for any and all network defense. If you implement this you will have as close to perfect defense as you can get. The good news is that when you implement this, even if you don't catch the bad guys you will at least catch all their tools and exploits as they hack your network.









