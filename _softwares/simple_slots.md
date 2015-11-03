---
title: Simple Slots
link: http://simpleslots.herokuapp.com/
---

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
