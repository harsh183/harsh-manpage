---
layout: post
title: Floats Don’t Work For Storing Cents Why Modern Treasury Uses Integers Instead
date: 2025-08-06
comments: true
external-url:
tag: Info
toc: true
---

Pretty much everywhere in my field of finance uses some kind of fixed-point representation for good reason. I was wondering about that one day and decided to explore all the things you need to account for when trying to store money in floats.

<https://www.moderntreasury.com/journal/floats-dont-work-for-storing-cents>

Basically, lots of things go wrong because of the many quirks of IEEE-754, lossy formatting, and various rounding modes. Please use integers, BigDecimal/BigNumber, or even strings instead.
