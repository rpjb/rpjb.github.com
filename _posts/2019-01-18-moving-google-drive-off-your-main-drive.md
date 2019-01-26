---
layout: post
published: true
author: robert barretto
categories: computing
description: reclaiming your solid state disk space
title: How to move google drive to a new location
image: /img/posts/2019-01-18-moving-google-drive-off-your-main-drive_330jpa.png

---

Solid state drives are fast, but do have limited size.  Google Drive can be particularly tricky with managing capacity -- say a colleague dumps very large files into your shared folder.

Google then released a program called Google Drive Sync, that allows users to download files on demand, rather than hogging the limited drive space with files that are rarely used. This is a good idea, but one does suffer a few latencies between reqesting a file, and having access to the file.

Another solution is to simply move the Google Driver folder off the main system drive.

[google support page](https://support.google.com/a/answer/7644837)
```
sudo defaults write 
/Library/Preferences/com.google.drivefs.settings DefaultMountPoint '/Volumes/Google Drive File Stream'
```

The resulting file will have the following entry:
![com.google.drivefs.settings](/img/posts/2019-01-18-moving-google-drive-off-your-main-drive_330jpa.png)

