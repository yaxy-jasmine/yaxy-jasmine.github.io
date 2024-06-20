---
layout: post
title:  a sample post
date:   2024-06-19 16:40:16
description: format of md post
tags: formatting links
categories: sample-posts
hidden: true
---

### Add your title here
<br/>
A simple way to add a new post from web (the alternate way is to use git/editor from laptop).
1. copy contents of this file.
2. create a new file, with name of date and post name.
3. paste contents of this file into new file, and update the titles/date etc. (delete those you don't need).
4. If you don't want it to be publicly visible, set published as false above. (others can still see it if you give them the link, but it's not visible from web).
5. commit the changes, it should appear on the web in 1 minute or so.

The post can be visited with the filename, but not visible from the list of posts, i.e. <br/>
[sample-post](https://yaxy-jasmine.github.io/blog/2024/sample-post/)

<br/><br/>

## remove all those not needed.
<br/>
### refer to markdown quick start
[Quick-Start-Markdown](https://github.com/jorditorresBCN/Quick-Start/blob/master/Quick-Start-Markdown.md)
also some basic html can be used, i.e. br above is used to add empty lines.

### you can add emojis
:smile: :cat:

### to show pictures (which was already uploaded to assets/img/):
{% include figure.html path="assets/img/IMG_2676.jpg" class="img-fluid rounded z-depth-1" width=200 zoomable=true %}
{% include figure.html path="assets/img/IMG_2672.jpg" class="img-fluid rounded z-depth-1" width=200 zoomable=true %}
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
