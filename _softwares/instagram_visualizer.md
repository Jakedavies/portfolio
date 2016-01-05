---
title: Instagram Visualizer
subtitle: A social network visualizer using the instagram api and network science.
link: https://github.com/kevineger/instagram-visualizer
tags: api, electron, node, promises, javascript, html
---

The instagram visualizer was a project for a final year project in a network science course. 
The project was to create an application that allows visualization of a users personal instagram network using network science. 

> Example of full UI with a simple network of my followers
![instagram example](/images/full-ui.png)

The application is an electron app that uses the instagram api for OAuth and query for data. 
The instagram querying wrapper uses asyncronous javascript heavily, and makes use of promises to handle api calls. 
Graphing is done using the [vis.js](http://visjs.org/) library, and is able to quickly graph our social networks nearly instantly.



> A network of the likes on my last 100 instragram posts
![instagram example](/images/clustered-graphs.png)




