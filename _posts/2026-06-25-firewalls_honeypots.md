---
layout: post
title: "Firewalls and Honeypots"
date: 2026-06-25
category: security-plus
---

## What I Learned Today

Today was all honey! Honeypots, honeyfiles, honeynets and honeytokens. And some firewall stuff. 

## In My Words

Firewalls are a basic component when it comes to Cybersecurity. Everyone must use them! They protect your network 
from attacks and malicious communication. They are either stateful or stateless. In a stateful firewall, it pays
attention to the "state" of traffic and makes decisions based upon it. They DO NOT review every single packet.

In a stateless firewall, it filters every packet based on data like the source IP, protocol, and port, among other
things.

I had heard of honeypots before but never knew there were so many variations. The names of some are pretty self
explanatory but I will still discuss them briefly. A honeypot systems that have been purposely configured to look
vulnerable but they have actually been set up to monitor and document any interaction with it. Honeynets are the 
same thing just on a larger scale, a group of honeypots. A honeyfile is a file that has been configured to be
attractive to an attacker. It contains unique detectable data and if that data is detected leaving the network
the network admin knows the system was breached. A honeytoken is similar in attractiveness and configuration. It
too is able to be tracked. You can find them in files, databases, directories, etc. IDS, IPS, and DLP are configured
to watch for them to be sent outside organization or accessed outside of normal circumstances.

## Did It Click?

These concepts were relatively simple and easy to understand. My brain wants me to connect "stateless" with "less work"
and therefore a stateless firewall doesn't inspect every packet but I'm gettinf closer to that being wiped from the
memory bank.
