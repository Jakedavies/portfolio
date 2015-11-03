---
layout: page
title: Software
permalink: /software/
---

These are the software projects I am working on or have worked on in the past

## [Simple Slots](http://simpleslots.herokuapp.com/)

Simple slots was built for a coding test for a software job, I ended up getting the job, but turn it down.
It was built in 6 hours using a simple node backend, redis and javascript/html.

Spin results and user credit balance calculations are all done server side and sent to the client so the game can't be cheated easily.

It is backed by a redis key/value store that stores usernames as keys and the users credit balance as the value.
One of the requirements was that users have their balances kept and available when switching devices.
The user balances were not be persistant upon system restarts so redis was a logical choice for the simple storage needed.

>The login screen
![Image of login screen](/images/login_screen.png)

>Example of the game screen
![Image of play screen](/images/play_screen.png)

## [My Uni Trade](http://myunitrade.com)

Built as a textbook exchange targeted at university students, My Uni Trade was developed over a summer with a friend.
The project itself was proposed by two acquaintances, who had big plans to launch at the start of the school semester and get a lot of natural traction.
The site did get quite a bit of traffic, peaking at over 1000 hits in a day, but the traffic quickly died. As it turns out, a site centered
around selling used textbooks only has gets traffic 2 times a year; September and January. The project was shelved after a few months.

The application was built on Rails and is backed by a Postgresql DB, the frontend uses basic html with bootstrap and custom styles.
All uploads are resized into needed sizes and pushed into S3.

>The main search page
![My Uni Trade Seach Screen](/images/mut.png)
