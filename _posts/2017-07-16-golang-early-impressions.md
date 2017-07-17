---
layout: post
title:  "Go Lang Early Impressions"
date:   2017-07-16 17:00:00 -0700
categories: code
---
Have you ever watched an old old cartoon or movie from your childhood that you simply loved and it was better than you remembered?

Go has become my Voltron, GI Joe, Fraggle Rock, and Tranformers all in one. 

For some background, the past couple of years I find myself being able to code a little less and less with each day. You know so I can make time for all those presentations, emails, financial models, and such that my job requires. That trend does not sit well with me and to compensate I have been furiously trying to find a language that rekindles my love of code. Don't get me wrong I love to code...there has just been something missing when I do it now versus when I got started.

Go has in an odd way been able to capture my imagination where other languages and platforms have failed. So why has it been so fun for me?

The first thing that jumped out to me was the procedural nature of the code. Believe you me I have loved some object oriented and functional paradigms; its just that these approaches feel slightly contrived and elitest...like a dandy at a royal party. Procedural approaches remind me of Norman Rockwell painting, classic simple with no pretension. Google built the language with an expressed objective to be productive and utilitarian; I love this. It just feels so good to dive in and build something of value. It's like Node before the bloat.

Another thing that has pulled me in is the fact that Go is a C derived language. I started learning development in C. C based languages have always felt so clean and nostalgic. 

The syntax is simple yet expressive, but it does feel in some places that things have been changed for the sake of change. The variable declaration makes complete sense to me. The use of pointers versus reference passed throughout forces thoughtful design. So much more. At the end of the day the syntax and structure is opinionated. If you share the same thoughts as the original language design aspirations you will love go. If you do not you will fight it and struggle.

One of the things that I loved & loathed about C#, C++, etc was the interface system or I should say the promise of interfaces versus the reality. The promise to me of an interface was a mechanism that enabled polymorphic code. The reality felt as if i was bloating my code...I always wondered why I had to explicitly declare that a class was an implementation of an interface. It just felt like a little messy and redundant.

In Go interfaces are declared in a very similar manner to other languages. The difference is that there is the idea of implicit satisfaction. What this means is that there is no need to declare that each piece of code implements an interface. No need to plumb through endless class files when adding or changing an interface definition. This is a huge win especially given code brought in from other packages. You can now interact with 3rd party code through interfaces without actually have to adjust the third party code. WOW! 

Go was engineered to solve some very specific problems at Google. If you are solving server side problems Go is a fun flexible language with a growing community. It definitely does not have the utility and depth that both C# and Java have, but that is part of its charm. My time thus far in Go has been productive and has resulted in some clean code that for sure has me wanting to code some more. I'm sure I'll hav esome more criticisms in time as I dig in, but for now its just fun. 

Below are some of the awesome resources I used to come up to speed. The Go Programming Language linked below was by far the most useful for me. Immediately behind that I just started coding and used popular Go libraries on Github to read up on the way others use the language to great effect.

* [The Go Programming Language - by Alan Donovan & Brian Kernighan](https://www.amazon.com/Programming-Language-Addison-Wesley-Professional-Computing/dp/0134190440/)
* [Getting Started with Golang](https://golang.org/doc/install)
* [Go Programming Language Code](https://github.com/golang/go)
* [Hugo - A static page generator similiar to Jekyll](https://github.com/gohugoio/hugo)
* [Tyk - A Go based api gateway](https://github.com/TykTechnologies/tyk)

