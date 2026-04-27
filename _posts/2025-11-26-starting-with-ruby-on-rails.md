---
layout: post
title: My Recommendation Links For Anyone Starting with Ruby on Rails
date: 2025-11-26
comments: true
external-url:
tag: Info
toc: true
---

Curated links and a suggested order to follow.

Everything should be free unless I tag it with **Paid**. If it's paid, it's not an affiliate link.

## Start With Basic Ruby

Rails uses Ruby heavily, and before doing any Rails I highly recommend starting with a cursory understanding of Ruby.

[Try Ruby](https://try.ruby-lang.org/)

15-30 minute in-browser introduction to Ruby with some interactive exercises.

[Learn X in Y minutes](https://learnxinyminutes.com/ruby)

Quick syntax reference for various aspects of Ruby. After a while you might not look at this as much, but it's a great starter.

You don't need to be an expert in Ruby before starting Rails, but definitely take the time to eventually learn the language well if you're planning to use Rails for some time.

## New to Programming 

[Learn to Program by Chris Pine](https://pine.fm/LearnToProgram/)

If you're new to programming in general, I highly recommend Chris Pine's short book. This is how I really got into programming myself when I was 12. It builds up basic programming concepts in a nice chapter-by-chapter format and has great exercises.

## Installing Rails

Installing Rails has always been an ordeal, and my go-to guide has always been:

[Go Rails Install Guides](https://gorails.com/setup/ubuntu/26.04)

Select your OS and version, and it'll apply the right template for installing Rails and all the moving parts it needs.

Once you have it working, newer Rails versions come with an idempotent install script called `bin/setup` that can be used to install or refresh your Rails setup.

## Quick Dive Into Rails

Rails is a _huge_ framework that's famous for being batteries-included for basically every baseline web development need. It's a lot to take in, and in my experience it takes months before someone is broadly fluent in the whole thing. The best way to learn is to take a quick tour of the core concepts Rails offers, and then learn more in later passes based on what your project needs.

[Official Rails Getting Started Guide](https://guides.rubyonrails.org/getting_started.html)

I've contributed to many sections here so I might be a little biased, but it's a great intro tour of major Rails features.

[Rails Girls Guide](https://guides.railsgirls.com/start)

It's not too recently updated, but I think the chapters cover broad concepts quite well.

## New to Frontend

[freecodecamp.com/learn](https://freecodecamp.org/learn)

You don't need extensive frontend knowledge to use Rails well, but if you don't have much of a background, try FreeCodeCamp's in-browser exercises that build up HTML, CSS, and JavaScript really well. This is how I picked up a solid foundation after years of Swiss-cheese knowledge.

## Frontend Frameworks

Rails started with a model of embedded Ruby and sending HTML over the wire, but it's also popular to use it with a frontend framework. Here's an example for React with Rails 7:

[How to integrate React with Rails 7](https://thoughtbot.com/blog/how-to-integrate-react-rails)

## Rails Philosophy

Rails has a very opinionated philosophy on how to develop and why it is the way it is. You must have already noticed in the tutorials so far, but if you're this far, you should definitely understand the underlying principles.

[The Rails Doctrine](https://rubyonrails.org/doctrine)

[An Introduction to Ruby on Rails – From someone with a frontend background by Luiz Felipe Diniz](https://blog.codeminer42.com/an-introduction-to-ruby-on-rails-from-someone-with-a-frontend-background/) 

This post is also an interesting take from someone coming in with a frontend background.

## Deeper Dives

Now that you have the basics down, there's no fixed order for the rest. Learn more based on your curiosity and what you need.

### Rails

[Michael Hartl's Ruby on Rails Tutorial](https://www.railstutorial.org/) - **PAID** 

I highly recommend this long book that walks through several Rails applications with increasing levels of complexity, along with software best practices. It peels back a lot of layers that Rails generators usually handle, and you'll have more confidence to build your own stuff by then.

This book is how I went from a programmer to a software engineer. It took me more education and work experience to get to where I am today, but this book was my proper start.

### Ruby

[poignant.guide](https://poignant.guide/)

Why's Poignant Guide to Ruby is a cute and quirky book that dives deeper into Ruby and its language design, with lots of nice illustrations.

I actually have this one in print from a limited-edition run. I don't know if there are still any runs around.

### Ruby-Style Object-Oriented Programming

While you've probably worked with other OOP languages before, Ruby takes a certain message-passing purist approach to it. Until I read all of this myself, I never fully appreciated why it's such a powerful paradigm and why Ruby is uniquely well-suited to it.

I think Sandy Metz writes about it the best:

[Sandi Metz' Rules For Developers](https://thoughtbot.com/blog/sandi-metz-rules-for-developers)

Four rules for Rails code. It's a broad heuristic, but it goes surprisingly far in helping you think through object design, relationships, and how objects call each other well.

[Practical Object Oriented Design in Ruby (POODR)](https://www.poodr.com/) - **PAID** 

This dives deep into object-oriented programming ideas and how to use them to create readable, flexible code. While I wasn't new to the principles in the book, it really helped me embrace the _why_ and _how_.


### Rails Guides 

Rails officially has lots of guides across a broad variety of topics. It doesn't have everything, but it's a great starting point when you want to learn more about specific areas. Besides the Getting Started Guide, where I've contributed a lot, you might spot some of my other contributions:

[Ruby on Rails Guides](https://guides.rubyonrails.org/)

### The Two Rails Stacks: Core/Omakase vs Prime

As you go further in the Rails community, you'll encounter a popular set of alternative defaults adopted by many Rails projects. The exact stack has changed over the years, but it's common to see:

* RSpec over minitest for testing
* FactoryBot over Fixtures for test data
* A service layer for business logic instead of putting more logic in models/controllers
* Frontend frameworks like React instead of Embedded Ruby with Hotwire

I recommend sticking with the Rails Core/Omakase defaults initially since it's more intimidating to learn both at once, but learning these eventually is worthwhile. If you're joining a pre-existing Rails project, you're likely to see some of these Prime stack choices.

These two blog posts from a while ago capture the split well. It's interesting how much stays the same.

[Rails Has Two Default Stacks -  Steve Klabnik](https://steveklabnik.com/writing/rails-has-two-default-stacks/)

[Rails Core Stack and Rails Prime Stack - Noel Rappin](https://medium.com/table-xi/rails-core-stack-and-rails-prime-stack-f0e18442348b)