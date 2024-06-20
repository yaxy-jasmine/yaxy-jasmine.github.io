---
layout: post
title:  a post with formatting and links
date:   2024-06-19 16:40:16
description: format of md post
tags: formatting links
categories: sample-posts
hidden: true
---


### Add your title here
A simple way to add a new post from web (the alternate way is to use git/editor from laptop).
1. duplicate this file as sample, and put your blog contents in the new file. Update the titles/date etc. (those you don't need).
2. If you don't want it to be publicly visible, set published as false above. (others can still see it if you give them the link, but it's not visible from web).
3. commit the changes, it should appear on the web in 1 minute or so.

The post can be visited with the filename, but not visible from the list of posts, i.e.
https://yaxy-jasmine.github.io/blog/2024/sample-post/


## remove all those not needed.

### refer to markdown quick start
https://github.com/jorditorresBCN/Quick-Start/blob/master/Quick-Start-Markdown.md

### you can add emojis
:smile: :cat:

### to show pictures (which was already uploaded to assets/img/):
{% include figure.html path="assets/img/IMG_2676.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
{% include figure.html path="assets/img/IMG_2672.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
Stary Stary Night, meet with Van Gogh.:smile:


#### Hipster list
<ul>
    <li>item1</li>
    <li>item2</li>

</ul>

this will add a thematic break
<hr>
test

<blockquote>
   Intelligence is the ability to avoid doing work, yet getting the work done.
    — Linus Torvalds
</blockquote>
