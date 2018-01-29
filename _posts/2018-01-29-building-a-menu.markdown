---
layout: post
title:  "Menu System"
date:   2018-01-29
image: "../assets/posts/menu.png"
categories: jekyll update
desc: This post details my experience building a menu system and pitfalls to avoid
---

![Sketch of the house where the cats live]({{ "../../../../../assets/posts/menu.png" }})

In this post I'd like to reflect on some things I've done wrong whilst building a menu system for our game. Here's the list:

- Use a new room for your menu system, don't try and work it into your current rooms
- Actually, use a new room for each screen in your menu
- Don't be silly like me and try and draw your menu in the Draw event, use the Draw GUI event
- Use a [ds_stack](https://docs.yoyogames.com/source/dadiospice/002_reference/data%20structures/ds%20stacks/index.html) to manage menu state, this makes your life a lot easier

It's petty late here and that's my quick 2 cents. If you wish to see a tutorial on this, please do request so in the comments below and I'll be ever so swift with a full blown tutorial on this. Have a lovely time developing. Also, subscribe to our newsletter on the homepage for more info on our game High Cats


