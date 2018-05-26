---
layout: post
published: true
author: robert barretto
description: How to control a headless mac
categories: computing
image: "/img/posts/2017-12-21-icloud-back-to-my-mac.png"
---

To access my computers, I have traditionally used Chrome Remote Desktop. This is pretty effective and operates across macs and pcs.  I would use this as a way to control a headless mac that has no display (and in many cases I don't have physical access to the mac).

I've recently run into a situation, where I've had to control a mac that was booted in safe mode. In this state, only bare essentials are made available to the user, and Chrome Remote Desktop is not considered critical.

Apple has embedded a neat kind of remote desktop in their iCloud offering. In the System Preferences, the iCloud section lists an option called Back to My Mac. If this is turned on, and Screen Sharing or Remote Management are enabled in the Sharing section, this computer can be accessed by other macs on the network.

Apple has [good documentation](https://support.apple.com/en-us/HT204618) for setting Back to My Mac up.  And it's probably worth noting that you'd want to make sure all your iCloud and user account passwords are strong.
