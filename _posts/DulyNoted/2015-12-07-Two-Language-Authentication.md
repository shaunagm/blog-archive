---
layout: post
title: Two Language Authentication
category: DulyNoted
date: 2015-12-07
tags: psychology stats python r projects reproducibility openscience
permalink: /DulyNoted/Two-Language-Authentication/
original_url: https://notes.shaunagm.net/post/134750650582/two-language-authentication
---

Last year I participated in a novel and exciting meta-analysis project called [Many Analysts, One Dataset](https://osf.io/gvm2z/). A single dataset was given to researchers in over a dozen independent groups to analyze, with the hope of seeing just how divergent the analyses would be.   

It was a great project, and they’re in the middle of a follow up now. The reason I mention it now is tangential. I initially tried to do the full analysis in Python, because Python is a lovely language which does not [silently do unexpected things](http://notes.shaunagm.net/post/132696416637/the-end-of-an-error-kind-of).  Alas, the scientific python suite did not have a particular test statistic I needed and so I had to try again with R.  When I re-implemented in R, though, I got a different result for one of the intermediate steps.  After much fine-toothed-combing, I realized I’d made a simple error in the Python script that my basic unit tests hadn’t caught.   

This experience led to a vow: for any important analysis I do, I will implement it in at least two languages.  

Earlier today I came up with a name for this process: two language authentication.