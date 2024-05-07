---
layout: post
title: can you make your own protocol? 
date: 2024-05-07-11-04-52
categories: [Uncategorized]
---
One of the areas of research that I've gotten more interested in with networking is protocols since so much of the networkign world is defined by it.  I figured one of the best ways to figure out protocols would be to make my own, so I set out to see if I could make my own, and the short answer is that yes it's possible to make your own protocol.

Apparently Industrial Control System vendors have been doing this for ages by building on open source protocols and adding their own features and things they find useful for their purposes, and that's what we'll do for what we need.

Most of the advice I found came from [reddit](https://www.reddit.com/r/compsci/comments/9rfotg/how_could_i_go_about_making_my_own_network/) and there was a list from LinkedIn that laid out some considerations when building one:

"""
1: Define objectives

2: Choose the protocol layer

3: Design the protocol format

4: Implement the protocol logic

5: Test and debug the protocol

6: Document and share your protocol
"""

Basically from what I gathered from reddit some of the primary tools are: [network simulator](https://www.nsnam.org/) and [scapy](https://scapy.net/) for network simulation and testing.

Onward and upward from here