---
layout: post
title: Fast sites and trimming bloat
date: '2017-12-13 18:15:24'
tags:
- web-development
---

## How fast should the website be?
You get to make this call. Set a goal and compare to you and your client's competitors.

## Where to start?
First get the baseline metrics.

Once you have your current state metrics, set a goal and improve.

## What tool would be way to do on going tests?
Us at [SH](sodiumhalogen.com) are toying with [sitespeed.io](sitespeed.io).

## What about a quick setup?
You bet!

- install [Docker](https://docs.docker.com/engine/installation/)
- run it in terminal: $`docker run --shm-size=1g --rm -v "$(pwd)":/sitespeed.io sitespeedio/sitespeed.io:4.0.0 http://www.yoursite.com/ --speedIndex --video`

## Wait, what is Docker?
...see this post

If you liked this setup or want to chat, [get in touch with me](https://twitter.com/Chance_Smith).