---
title: Node discovery protocol
description: 
published: true
date: 2020-06-16T10:21:15.819Z
tags: 
---

# Node discovery protocol
In a nutshell:
* Aimed at discovering _RLPx nodes_ to connect to
* UDP-based RPC protocol ([kademlia](https://en.wikipedia.org/wiki/Kademlia)-like)
* Defines 4 packet types: _ping_, _pong_, _findnode_ and _neighbors_

See details at the [devp2p](https://github.com/ethereum/devp2p) repository's [node discovery protocol](https://github.com/ethereum/devp2p/blob/master/discv4.md) page.