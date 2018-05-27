---
layout: post
published: true
author: robert barretto
description: Automating the aggregation of categories
categories: mostlycurious
---
The categories of the blog post used to be hardcoded -- there are individual layout files for each category.  This is acceptable if I add an additional category, as I could just copy/paste and rename the file for the new category.

However, the inefficiency arises when I have to make a change to the layout itself.  In this case, lines of code needs to be changed in multiple locations, creating opportunities for error.

Jekyll can get around this by being configured to auto-generate output files. There is a nice simple tutorial from Kyle Banks at [Creating Category Pages in Jekyll without Plugins](https://kylewbanks.com/blog/creating-category-pages-in-jekyll-without-plugins).
