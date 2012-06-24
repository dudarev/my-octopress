---
layout: page
title: "Visualization of twitter social graphs"
date: 2009-01-11 21:44:15
comments: true
sharing: true
footer: true
---

Some time ago I visualized my twitter social graph. The graph was
handled with [NetworkX](http://networkx.lanl.gov/), Python package
to work with graphs. [Graphviz](http://www.graphviz.org/) package
is used for the visualization, specifically its neato layout, that
uses
[Kamada-Kawai algorithm](http://en.wikipedia.org/wiki/Force-based_algorithms).
It represents a graph as some physical model of masses connected
with springs. Optimization for lowest energy state automatically
generates visually appealing pictures where clusters of tightly
connected nodes are automatically formed.

In my twitter network three visual cluster are clearly formed (as
of December 2008). The largest one is openstreetmap and GIS crowd.
Two others are from Russian speaking part of tweetosphere: users
mostly related to Donetsk and surroundings, and a small group of
users related to web startups in
Kiev.[![Twitter social graph for @dudarev](http://farm4.static.flickr.com/3486/3188408507_ec6c705a7b.jpg)](http://www.flickr.com/photos/dudarev/3188408507/ "Twitter social graph for @dudarev by dudarev, on Flickr")

Presently, I am working on a project that will allow to
systematically organize social dance videos on youtube.
Specifically, it will help to tag dance moves in numerous videos.
Similar to subtitles, the moves are pinpointed to specific times
inside of the videos.

To understand if such a website may be useful to anybody else
except me, I did a number of searches on twitter. Salsa is
definitely rather popular with several dozens of twits mentioning
it every day. Swing dances are mentioned no more than ten times per
day. In both cases, if to search only for "salsa" or "swing",
manual filtering is necessary, since both can be used in various
contexts. It helps to play with additional keywords: "swing dance",
"salsa learn" ... My favorite twit from these searches is by
[@chrismoreschi](http://twitter.com/chrismoreschi): "We're learning
to salsa to youtube tuts in our undies." Great to know that other
people do watch the tuts :)

It was interesting to visualize how people who mention social
dances are connected. The similar approach as in visualizing my own
social graph is
used.[![Twitter social graph (social dances)](http://farm4.static.flickr.com/3321/3188408581_64c617d579.jpg)](http://www.flickr.com/photos/dudarev/3188408581/ "Twitter social graph (social dances) by dudarev, on Flickr")

Even though there are more salseros here than those who mention
swing dance, the latter are more connected. As in real live, swing
dancers seem to be more social.
