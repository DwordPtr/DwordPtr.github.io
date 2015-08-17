---
layout: post
title: I took the Arch challenge
date: 2015-08-17
categories: Arch Linux
---
I took the Arch challenge
===

###Why?
Last year Linux Action Show promoted the Arch challenge. Presumably because Arch is regarded as one of the more challenging distro's (but possibly less challenging the Gentoo or Linux from Scratch). I was a long time Ubuntu user, but I'd been itching to try something. I was considering switching to Debian but chose Arch because I like the idea of a bleeding edge rolling release (or just hate the hassle of reinstalling). So with after spinning up a virtual machine  and running through the install I decided to do a clean install over Ubuntu and see how it performs as a daily driver.

###Experience
The install would've gone alot more smoothly if I had read the documentation about UEFI and mounting the /boot partition more closely. I've learned just how spoiled I was with Canonical. I won't go to in detail because the wiki covers the install process and whats expected quite well. After that I decided to try kde's new plasma 5 as a DE. I was surprised at how sparse arch can be. I had to manually install KMix and plasma-nm to get the gui volume controller for alsa and wifi respectively. Running jekyll required messing with the path in my bashrc and manually installing nodejs. This kind of thing has taught me much about how an OS fits together. I can see how Arch would be tough at first but bring benefits as far as flexibility and simplicity go. 

###Vs Ubuntu
One thing that shocked me about Arch is the learning curve wasn't too steep. It was definitely there and many things were definitely less easy in Arch, but they weren't much harder; except for things that you only do once (secureboot initial install etc). The wiki is amazing even for the hard parts. I've yet to run into anything that I can't do in Arch that I used to do in Ubunut. It's a solid distro and the devs deserve recognition. 

###Pain points
Arch has a reputation for it's difficult install process. Compared to distros with graphical installers Arch is really tough to get a booting base. The actually install just requires running pacstrap the real challenge is doing everything else to get a bootable system. There are distros that add a GUI install to pacman to help relieve the stress, but tend to be frowned upon due to fragmentation and downstream issues. I've also had more crashes than with Ubuntu, but this could be attributed to using Plasma 5 and beginner mistakes. Luckily I've never lost any major work because of it. 

###Why switch?
The real pro's of Arch are its quick deployment of the latest software and its one time setup philosophy; setup a good system and just install updates. It really feels like just a package manager + the latest from various open source projects since its upstream patches are minimal.

###Takeaways
Arch is a solid choice for anything in user-space. It's worth giving a shot if you like control over your PC and have some degree of experience with Linux.
