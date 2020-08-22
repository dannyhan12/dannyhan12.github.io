---
layout: post
title: Setting up NextCloud on My Raspberry Pi
date: 2020-08-01
categories: [ESTIMATION]
comments: true
---

Over the last week or two, I set up our raspberry pi to work as a Nextcloud server. I wanted an easy way to back up photos from my phone.

I read through and followed lots of guides to get it working. 

- https://opensource.com/article/18/7/network-attached-storage-Raspberry-Pi
- https://pimylifeup.com/raspberry-pi-exfat/
- https://www.raspberrypi.org/documentation/configuration/external-storage.md
- http://baddotrobot.com/blog/2017/10/26/upgrade-raspian-jessie-to-stretch/
- https://pimylifeup.com/upgrade-raspbian-stretch-to-raspbian-buster/
- https://pimylifeup.com/raspberry-pi-nextcloud-server/
- http://unixetc.co.uk/2016/11/20/simple-nextcloud-installation-on-raspberry-pi/

Now that it's up and working, I can say that it alls works pretty well without too much trouble. With some time and perserverence, I'm sure you can set it up as well. But as a reminder to myself, I wanted not some things that tripped me or slowed me down. No matter how trivial the project, we should all remember, these things take some time.

First, before I got started at all, I found out that my Raspberry Pi operating system was a bit behind. So, I spent a bit of time upgrading. First, I had to upgrade from "Jessie" to "Stretch". Then, I upgraded from "Stretch" to "Buster". This was completely straightforward, but it took a while (hours?) to complete. It probably went quicker than that, but it was so long that I stepped away and just periodically checked on it. I think this sort of "rot" happens on any project. You go to fix one thing, but you discover you have to do a lot of other clean up before you can even get started.

The next big time consuming thing was permissions. In Unix, every file and folder associated permissions. Who owns a file? Who can read, write or run a file? Setting tight permissions prevent bad-guys from messing with your stuff and keeps you from shooting yourself in the foot. But it can also be a pain. 

Finally, the last big time suck was figuring out how to adjust the power settings on my hard drive. I expect the next cloud to only need to back up to my hard drive in spurts. Couple of time a day max. So, I wanted my hard drive to spin down to save on wear and tear. Getting my hard drive to do the right thing was a lot of trial and error.

I don't have too much more to add about this. I'm glad I completed this project and I'm putting my raspberry pi to good use. It didn't take too much to set up the Nextcloud server, but yet, it took longer than I expected. I'll try to remember this whenever I estimate work. If I don't know exactly what I'm doing, it'll probably take a little longer than I'd guess.