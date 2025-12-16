---
layout: post
title: Mobile Debugging
category: DulyNoted
date: 2015-10-30
tags: shorts tech
permalink: /DulyNoted/Mobile-Debugging/
original_url: https://notes.shaunagm.net/post/132218788867/mobile-debugging
---

I recently made myself a new personal website, and I noticed there were a couple of problems with the mobile version: the font-awesome icons weren’t displaying, and the collapsed, mobile-friendly navbar wasn’t expanding.  

I was at a loss for how to debug these problems, until I discovered [this guide](https://developer.chrome.com/devtools/docs/remote-debugging).  After a bit of set up (most of which I’d already taken care of for Android app development) I was able to navigate to chrome://inspect and access the full suite of developer tools for my phone.

After that, debugging was easy.  The navbar issue was a simple typo in the ID attribute, and the icon issue was the mobile site loading a different (faulty) format than the web version.

Celebratory cat gif:

![gif of a cat using a mouse on a computer](/assets/image/blog/celebratory_cat_gif.webp)