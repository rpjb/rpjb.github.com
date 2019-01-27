---
layout: post
published: true
author: robert barretto
categories: computing
title: Whitespace isn't always just a space
image: /img/posts/2019-01-26-whitespace_hxanhz.png
description: 25 different flavors
---

Inside textareas and html elements, there are several types of white space.  There are line feeds, carriage returns, and of course, the space. But there are also other spaces. 

![https://stackoverflow.com/questions/2202999/why-is-textarea-filled-with-mysterious-white-spaces](/img/posts/2019-01-26-whitespace_hxanhz.png)

 And in particular compressed spaces.

![compressed white space](/img/posts/2019-01-26-whitespace_en98g3.png)

If you're going to process strings that contain sequences of white space, it might be worthwhile to make sure your html doesn't compress them into a special whitespace character.  This would allow methods like replace to work as expected:

```javascript
str.replace(/ /g,"");
```