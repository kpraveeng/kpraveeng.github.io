---
layout: post
title: "Running Docker And Virtual Machine On the Same Physical Machine"
date: 2020-05-06 23:54:20 +0530
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: docker-virtualbox.png # Add image post (optional)
---

Because of different Hyper-V used by Docker and Virtual Machines i.e. VirtualBox / VMWare etc cannot be run on the same machine. In this post I will share a way where both of them can run on the machine albeit only one of them will at a given point of time

# Run VirtualBox

Disable Hyper-V as follows

Open command prompt as administrator and run the command:

`bcdedit /set hypervisorlaunchtype off`

You’ll need to reboot, but then you’ll be all set to run VirtualBox.

---

# Run Docker

To turn Hyper-V on run as follows

Open command prompt as administrator and run the command:

`bcdedit /set hypervisorlaunchtype auto`

You’ll need to reboot, but then you’ll be all set to run Docker.
