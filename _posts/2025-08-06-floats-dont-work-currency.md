---
layout: post
title: Floats Don’t Work For Storing Cents: Why Modern Treasury Uses Integers Instead
---

Pretty much everywhere within my field of Finance seems to use some kind of fixed point representation for good reason, I was wondering about that one day and thought about exploring all the things that need to be accounted for when trying to store money in floats. 

https://www.moderntreasury.com/journal/floats-dont-work-for-storing-cents

Basically lots of things go wrong because of the myriad of quirks of IEEE-754, lossy formatting, and various rounding modes. Please use Integers, BigDecimal/BigNumber or even Strings instead.