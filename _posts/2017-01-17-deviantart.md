---
layout: post
title: 4HP DeviantArt Game
comments: true
---

4HP (4 Hour Project) is a series of simple tasks implemented in about 4 hours. The main reason is to learn something new, try hot technology or make small research and pickup the best framework/lib.

<a href="{{ site.url }}/deviantart-game" target="_blank">DEMO</a>

### Instructions
On mobile you swipe photos to left or right, on desktop use arrows (left/right) to swipe. Click on profile picture to change user with nickname.

### Foundation
Last week I had a small argument with my brother. We talked about photography business. My brother claimed that his friends is one of the best photographer and his photos are just amazing. I was trying to find out what makes his friend outstanding.

We couldn’t get any conclusions, so I decided to create simple game that will show if there is some difference between random photos and photos taken by his friend. I used his photos from DeviantArt, mixed them with random photos and displayed them in tinder-like gallery: you decide who’s the author by swiping photo.

My brother couldn’t get a 100% score so I assume that I won. After all I added ability to provide other deviants and play in one versus other game (for example to check if you can recognize a unique style of your favorite photographer).


### Technology
- [jTinder](https://github.com/do-web/jTinder) - jQuery plugin for tinder-like cards, first result on Google, works at first run, nothing to add, [example](http://netcup-gutschein.x5c.de/jtinder/)
- [ProgressBar.js](https://github.com/kimmobrunfeldt/progressbar.js) - I choose this lib from > 50 others, it has the greatest design and functionality that I was looking for (changing colors), [example](https://kimmobrunfeldt.github.io/progressbar.js/)
- [DeviantArt Gallery Plugin](https://github.com/jamesl1001/deviantART-Gallery-Plugin) - I used some snippets from this repo to parse user photos

### What I learned
- [Fisher-Yates Shuffle](https://bost.ocks.org/mike/shuffle/) - I was looking for some algorithm to shuffle photos in array (to not display the same photo in every game), I chose Fisher-Yates
- [YQL](https://developer.yahoo.com/yql/) - "Yahoo Query Langauge" yahooapis that change xml to json (which is nice)
- [DeviantArt API](https://www.deviantart.com/developers/rss) - is pretty strange, never used RSS API before, [example](http://help.deviantart.com/335/)
