---
layout: post
title: My Recommendation Links For Anyone Starting with Ruby on Rails
date: 2025-11-26
comments: true
external-url:
tag: Info
toc: true
---

Curated links and the order to do them. 

Everything should be free unless I tag it with **Paid**. If it's paid it's not an affiliate link. 

## Start With Basic Ruby 

Rails uses the Ruby language heavily and before doing any Rails I highly recommend starting with a cursory understanding of Ruby.

https://try.ruby-lang.org/ - 15-30 minutes in browser introduction to ruby with some interactive exercises 

https://learnxinyminutes.com/ruby/ - quick syntax reference on the various aspects of ruby. After a bit you might not look at this as much, but it's a great starter. 

You don't need to be an expert in ruby before starting rails, but definitely take the time to eventually learn the language well if you're planning to use Rails for some time. 

## New to Programming 

https://pine.fm/LearnToProgram/

If you're new to programming in general, I highly Pine's short book. This book is how I really got into programming myself when I was 12. It builds up all the basic programming concepts in a nice chapter by chapter format and has great exercises.

## Installing Rails

Installing Rails has always been an ordeal, and my go-to guide has always been 

https://gorails.com/setup/ubuntu/26.04

select your OS, Version and it'll apply the right template on how to install Rails and all the moving parts it needs. 

Once you have it working, newer Rails versions come with an idempotent install script called `bin/setup` that can be used to install or refresh your Rails setup.

## Quick Dive Into Rails

Rails is a _huge_ framework that's famous for being batteries included for basically every baseline web development need. It's a lot to take in and takes months till I've seen someone broadly fluent in the entire thing. The best way to learn is take a quick tour of the core concepts that rails offers, and then learn more in later passes and based on whatever your project needs.

https://guides.rubyonrails.org/getting_started.html - Official quick start guide, I've been contributed to many sections here

https://guides.railsgirls.com/start - it's not too recently updated, but I think the chapters cover the broad concepts quite well

## New to Frontend

https:freecodecamp.org/learn - You don't need very extensive knowledge of frontend to use Rails well, but if you don't have much of background try Freecodecamp in browser exercises that build up HTML, CSS, and JavaScript really well. This is how I really picked up a solid foundation after years of Swiss cheese knowledge.

## Frontend frameworks

Rails started with a view of embedded ruby and sending html over the wire, but it's quite popular to use it with a popular frontend framework. Here's an example for React with Rails 7

https://thoughtbot.com/blog/how-to-integrate-react-rails

## Rails Philosophy

Rails has a very opinionated philosophy on how to develop and why it is the way it is. You must have already noticed in the tutorials so far, but if you're this far, you should definitely understand the underlying principles.

https://rubyonrails.org/doctrine

https://blog.codeminer42.com/an-introduction-to-ruby-on-rails-from-someone-with-a-frontend-background/ - interesting take from someone coming in from a frontend background 

## Deeper Dives

Now that you have the basics down there's no set order to the rest. Learn more based on your curiosity and what you need 

### Rails

https://www.railstutorial.org/ - **PAID** 

I highly recommend Michael Hartl's long book that takes you over several Rails applications with increasing levels of complexity along with software best practices. It peels back a lot of the layers you'll often see handled by the Rails generators and have the confidence to develop your own stuff by then. 

This book is how I went from a programmer to a software engineer. While it took me many years (and a cs degree) to become reasonably productive, 

## Ruby

https://poignant.guide/

Why's Poignant Guide to Ruby is a cute and quirky book that dives further into understanding Ruby and it's language design with lots of nice illustrations.

I actually have this one in print from a limited edition run, I don't know if there's still any runs around. 

## Ruby style Object Oriented Programming 

While you've probably worked with other OOP languages before, Ruby takes a certain message passing purist approach to it. Until I read all of this myself, I never really appreciated why it's such a powerful paradigm and why Ruby is uniquely well suited to it. 

I think Sandy Metz writes about it the best:

https://thoughtbot.com/blog/sandi-metz-rules-for-developers - 4 rules for rails code. It's a broad heuristic but it goes surprisingly far in thinking about actually designing our objects, their relationships and how they call each other well. 

https://www.poodr.com/ - **PAID** Her Book, Practical Object Oriented Design in Ruby (POODR) really dives deep into the different ideas around object oriented programming and how to use it to create well readable and flexible code. While I wasn't new to the principles from the book, this book really helped me embrace the _why_ and _how_. 


## Rails Guides 

Rails officially has lots of guides on a very broad variety of topics. It doesn't have everything, but it's a great starting point to learn more about specific points. Besides the Getting Started Guide I've contributed a lot too, you might catch some of my other contributions here or there.

https://guides.rubyonrails.org/