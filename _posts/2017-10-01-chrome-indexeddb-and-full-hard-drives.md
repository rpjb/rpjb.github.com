---
layout: post
published: true
author: robert barretto
description: Free Chrome's grip on your hard drive
categories: computing
image: "/img/posts/2017-10-01-hard_drive_distribution.png"
---
Recently, my machines have been running out of space fairly quickly.  
![2017-10-01-hd-space-before.png]({{site.baseurl}}/img/posts/2017-10-01-hd-space-before.png)

I did a quick check of my hard drive inventory by using Disk Inventory X. One big block belonging to Google Chrome application data was occupying some 50GB of hard disk space.

![2017-10-01-hard_drive_distribution.png]({{site.baseurl}}/img/posts/2017-10-01-hard_drive_distribution.png)

It's useful to have access to your google drive using the online interface at drive.google.com.  Google Chrome stores some of the info locally in indexeddb, and while I'm sure that information is useful, it is also expendable (Google Drive is on the cloud)  and I will need to have disk space.

Rather than blindly deleting the files, all I had to do to empty the cache was go offline, and visit the drive.google.com.  Of course, being offline, an error is returned.  But this seems to purge the indexeddb.

![2017-10-01-hd-space-after.png]({{site.baseurl}}/img/posts/2017-10-01-hd-space-after.png)
