---
title: deviantART Page View Hack
layout: post
date: 2018-05-19 00:00:00 +0000
sub_heading: ''
tags: []
banner_image: ''
related_posts: []
---
Javascript element that will reload a random user's page on deviantART.  Inspect element of comments block on deviantART webpage and insert following code.

\`\`\`javascript

javascript:var int=setInterval(function() {document.getElementById('comments' ).innerHTML=&quot;&lt;iframe src='[http://www.deviantart.com/random/deviant](http://www.deviantart.com/random/deviant "http://www.deviantart.com/random/deviant")'&gt;&lt;/iframe&gt;&quot;;void(0);},5000);

\`\`\`

The idea is to visit a random user's web page every 5 seconds.  If they have 'recent visitors' enabled they will see you visited their page and possibly visit your page in return.  Must be logged in for it to register.