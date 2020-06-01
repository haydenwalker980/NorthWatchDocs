---
layout: default
title: Server Regions and Ping
nav_order: 4
---

# Server Regions and Ping
This page explains slow connections to NorthWatch, unexpected session timeouts when switching VPN server regions, or other region-related troubles.

## Multi-Region (aka Load Balancing + High Avalibility)
NorthWatch uses multiple server regions to ensure that you are always getting a reasonably quick connection (assuming servers aren't overloaded).  Most of the time, it makes sure that people in North America, for example, aren't being routed to servers in Mumbai.  Very rarely, load balancing can have unintented consequences, and this article explains them in more depth, and how you can solve potential issues.

### Server Regions
As mentioned above, we have multiple server regions.  Here is the definitive list:

* Los Angeles, United States
* Atlanta, United States
* London, United Kingdom

If you live near any of the places that list (although if you are in India, you don't have easy access to NorthWatch as a scambaiting tool), you can expect very good speeds except in very rare cases of high server load, and high load is typically mitigated in seconds.

## Session Timeouts
As mentioned in the very beginning of the article, when you switch VPN server regions, your session is sometimes timed out. This is because our load balancing solution uses your IP's nearest server region, and uses that, and when you change IPs, you might change server regions, and since session information isn't shared between servers, you might get an error about missing permissions.  There is an easy solution, just don't jump arround too much!

## Common Questions
Here are some common questions you might have about load balancing and server regions.

```
"I am nowhere near any of the locations on the server list.  Am I still going to be able to access NorthWatch quickly?"
```
The answer is usually yes, unless you are in a very remote area.  If your country isn't on that list and your connection speeds suffer because of it, [please send us an email](mailto:help@northbaits.com)!  We love to hear suggestions, and are happy to look into adding server regions where neccesary.  You can easily test it out, just browse NorthWatch and see if you have significant ping or slowdowns.

```
Did the servers change?
```
Possibly, the servers change freqently along with usage.  You can see [the history of this file here](https://github.com/evanspy1/NorthWatchDocs/commits/master/docs/server-regions-and-ping.md), and that shows all the changes that have been made to this documentation file, including additions and deletions of server regions.
