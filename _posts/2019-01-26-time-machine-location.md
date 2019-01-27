---
layout: post
published: true
author: robert barretto
categories: computing
title: Changing a Time Machine location
description: using a windows share
---

Creating a sparse image called Babyfuku using the Terminal
``` 
hdiutil create -size 500g -type SPARSEBUNDLE -fs "HFS+J" Babyfuku.sparsebundle
```

Copy the sparse image to your windows share from the mac, using Finder's "connect to server" dialog
![finder dialog](/img/posts/2019-01-26-time-machine-location_y7mmbi.png)

After the image is on the windows share, mount the image.  This will give your mac access.

My time machine is mounted as Babyfuku, so the command to set the location is:
```
sudo tmutil setdestination '/Volumes/Babyfuku'
```

The only other hiccup, is that my server connection disconnects after periods of inactivity.  To prevent this, I copy the Calculator app to the windows share, and run the app.  This prevents the inactivity.