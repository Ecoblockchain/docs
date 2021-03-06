---
title: MultiTech Conduit
redirect_from:
 - /multitech/
sections:
 - multitech/_aep.md
 - multitech/_mlinux.md
---

The [MultiConnect® Conduit™](http://www.multitech.net/developer/products/multiconnect-conduit-platform/) is a configurable, scalable cellular communications gateway for industrial IoT applications. Conduit allows users to plug in two MultiConnect mCard™ accessory cards supporting wired or wireless interfaces.

This guide will help you set up the gateway to communicate over The Things Network. Both the guide and the [install script](https://github.com/kersing/multitech-installer/) are a community effort lead by [Jac Kersing](https://www.thethingsnetwork.org/u/kersing/). 👏

## Prerequisites

* MultiTech Conduit [AEP](http://www.multitech.net/developer/software/aep/) or [mLinux](http://www.multitech.net/developer/software/mlinux/) model.

  > There is no need to update any of the MultiTech software on the conduit.

* MultiTech [MTAC-LoRa LoRa accessory card](http://www.multitech.net/developer/products/accessory-cards/mtac-lora/), installed as [instructed](http://www.multitech.net/developer/products/accessory-cards/installing-an-accessory-card/).

  > Do not forget to mount the antenna to the mCard after fitting it in the conduit.
  
* Computer with USB port and terminal software. Included with Mac OS and Linux. For Windows use something like [Putty](http://www.chiark.greenend.org.uk/~sgtatham/putty/download.html).
* For the mLinux version you'll need a USB stick.
