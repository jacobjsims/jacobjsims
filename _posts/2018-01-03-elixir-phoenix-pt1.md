---
layout: post
title:  "Incidently Build Part 1 - Elixir & The Phoenix Framework"
date:   2018-01-02 17:00:00 -0700
categories: code elixir phoenix side-projects
---
On a monthly basis, I spend some time deeply reflecting on recent challenges in my life applying a lens towards what opportunities are there to improve the status quo. This time around I found two different opportunities one personally and one professionally that align.

Personally, the need to explore new technologies beyond the surface level buzz words on the internet.

Professionally the need to address a long standing organizational communication challenge coupled with incident management activities.

Fulfilling both of these needs I have decided to build out Incidently, an incident communication product whose express purpose is to streamline how, when, and to whom incident related communications are distributed. On the technical side, I have always loved the promise of Erlang but have never really delved into it much. Elxir, an Erlang derived language, has been gaining significant traction and seems perfect for easing me into the Erlang world when coupled with Elixir. 

So what is Elixir? 

> Elixir is a dynamic, functional language designed for building scalable and maintainable applications. 

>Elixir leverages the Erlang VM, known for running low-latency, distributed and fault-tolerant systems, while also being successfully used in web development and the embedded software domain.

These two statements are critically important but will sound buzz wordy to the laymen who is not familiar with [Erlang](https://www.erlang.org/), the Erlang VM aka [BEAM](https://erlangcentral.org/tag/beam/) or [OTP](http://learnyousomeerlang.com/what-is-otp). Let's dive deeper. Erlang as a language and platform was established by Ericsson in the 80's with the purpose of supporting their telecommunications aperatus. As a telecommunications entity Ericcson needed handle and respond to a significant amount of concurrent connections in a way that was fault tolerant and scalable. 

To link this example to the real world you want to be able to make phone calls anytime, have a quick response, and not be blocked out at say a sporting event where thousands of other people are trying to make calls. Also, if an issue does occur you don't want to have someone dispatched physically to each cell tower to fix the problem. You want a platform with high uptime, healing capabilities and the ability to grow with use easily.

Erlang was built to solve these problems and it does it remarkably well. The beauty of Erlang is that the problems faced in telecommunications are remarkably similar to those faced in an internet connected world. You want to be able to handle multiple concurrent connections, web requests, rapidly without significant downtime. Internet, web, and mobile companies also depend heavily on uptime so you want a platform that is fault tolerant and resilient, much like a phone system.

Wow...this sounds wonderful...why isn't everyone using Erlang?

Adopting Erlang for many has been a significant challenge due to Erlangs functional paradigm and very strict syntactic limitations. Combining these two challenges made the learning curve for adopting Erlang en masse impossible during a time where Object Oriented programming was all the craze. With the creation of the Erlang VM (BEAM) Elixir was established by the community as language that leveraged the power of the Erlang platform with a syntax and code organization that found balance with more conventional programming styles. 

As Elixir has matured many developers have established platforms and frameworks in an effort to realize the benefits of Erlang. One such framework, the [Phoenix Framework](http://phoenixframework.org/) bills itself as "a productive web framework that does not compromise on speed or reliability." Doing the Phoenix framework an injustice I will summarise a wealth of other internet material by stating that Phoenix borrows the best of Rails, introduces the power of Elixir and its functional roots, and has enough community traction so that you are not re-inventing the wheel.

In the coming weeks and month's I will outline each of the steps in my effort to build a basic functioning version of Incidently. I look forward to learning more and hoping I can share my experiences so others may learn with me.