---
layout: post
title: Sudo Make Me An Operating System
category: DulyNoted
date: 2015-11-10
tags: tech bugs puns
permalink: /DulyNoted/sudo-make-me-an-operating-system/
original_url: https://notes.shaunagm.net/post/132952846712/sudo-make-me-an-operating-system
---

Yesterday I backed up my entire computer, deleted and resized some partitions, and then attempted to upgrade my operating system from 32-bit to 64-bit.  I was following [this guide](http://www.ewan.cc/?q=node/132), which unfortunately doesn’t tell you to follow the instructions as root from the beginning.  The result?  Halfway through the process, I deleted my 32-bit version of sudo in order to install the 64-bit one.

This is a perfect example of the kind of thing people forget to put in their instructions because they think it’s obvious.  And it was obvious in retrospect!  When I tried to use sudo and got a program-not-found response I think I actually facepalmed.

Anyway, no harm done - I simply installed a new system via my USB and have spent the morning downloading programs, resetting preferences, etc.  And I have learned a lot about root and sudo.  So maybe this was for the best.  

I will leave you all with [one of my favorite business names](http://www.sudoshoes.com/):

![picture of the storefront of Sudo Shoes](/assets/image/blog/sudo-shoes.jpg)