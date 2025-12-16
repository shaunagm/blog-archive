---
layout: post
title: Proof is the bottom line for everyone
category: DulyNoted
date: 2015-10-20
tags: math games puzzles
permalink: /DulyNoted/Proof-is-the-bottom-line-for-everyone/
original_url: https://notes.shaunagm.net/post/131535970347/set-proof
---

A few days ago I was playing [Set](http://www.setgame.com/) with friends when one of them asked how many cards could be put down without making any sets.  Someone else responded that whatever the answer was, there was probably a very sound mathematical/logical reason for it.  After a bit of thinking I came up with this:

(Let “attribute” mean any one of the shape, color, shade or number of items on the card.  Let “state” mean one of the three options an attribute can take - for instance, red, green and purple for color.  Let “Max Cards” equal the maximum number of cards it is possible to put down in Set without making a match.)  

There are two different ways to make a set across a given attribute: by having each card have the same state, or each card have a different state.  However, it is not possible to make a set if all four variables have the same state on each card, because that would make the three cards identical, and there are no identical cards in the deck.  At least one of the attributes must have a different state for each card.  Therefore, you can make a set-less subset of the deck by removing all cards with a particular state for each attribute, for instance removing all reds, triangles, full-shaded, and three-numbered cards from the deck.  So the minimum number that Max Cards could be is sixteen - 2^4.  
  
Is that also the maximum number of cards it could be?  Will any additional card make a match with the sixteen played cards?  Yes.  Let’s say you play a card that has one attribute in a previously disallowed state and three attributes in allowed states - say, one that is red (the disallowed color state) and an empty single circle.  One possible set for that card would be a set in which all of the attributes corresponding to the allowed states are the same, and only the attribute in the disallowed state (color) are different, aka in the allowed states.  Therefore the two remaining cards in the set would not have any disallowed states, and would already have been played.  You can do this for a card that differs on two, three, or all four attributes.

This is not a perfect proof, because it doesn’t *rule out* the possibility of getting to some sort of higher number of cards, but it does prove you can get to 16 and no higher through one particular method.  I’m pretty pleased with it.