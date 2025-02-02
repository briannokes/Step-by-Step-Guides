---
layout: default
title: Step-By-Step Guide - Xpenology USB to SSD Boot Main OS
subtitle: Created by Brian Robert Nokes 2025
---

<h2 style="text-align: center;">Step-By-Step Guide - Xpenology USB to SSD Boot Main OS</h2>
<br>
<span style="display:block; background-color:red; width:100%; height:2px;"></span>
<h4 style="text-align: left;">Thank you for taking the time to explore this comprehensive guide. I've invested significant effort into its creation, aiming to provide you with detailed and valuable insights. I trust that you will find it helpful and worthy of sharing with others.</h4>
<br>
Created by Brian Robert Nokes
<br>
<span style="display:block; background-color:red; width:100%; height:2px;"></span>

<h7 style="text-align: left;">The first thing I started to do was use rescuezilla, and cloned the USB drive to the SSD. That partially worked, the first run, it put the 1st partition on the SSD drive, but it left out the other 2 partitions 2, and 3. So I didn't one more time to see what happened, and it said some stuff and partition 2 didn't get done and rescuezilla wasn't able to complete again, but now I see partition 1, and 3 and still missing partition 2. Now this all is being seen by using a Linux Ubuntu box and stopped using windows to do this. On Linux, I was able to see all the partitions on the USB drive.</h7>
<br>
<span style="display:block; background-color:red; width:100%; height:2px;"></span>
<h7 style="text-align: left;">I then looked at using, on Linux Ubuntu Gparted. I tried things, one thing I did was unmount USB drive, the missing partition 2 and use the gear to copy, or I right-clicked it, however, just copy the partition from the USB drive and then in the upper top right corner of Gparted, change to the SSD drive you that you want these partitions on.</h7>
<br>
<span style="display:block; background-color:red; width:100%; height:2px;"></span>
<h7 style="text-align: left;">I also copy the other partitions from the USB drive to the SSD drive and pasted them into the SSD over the partition that didn't finish correctly. Also after copying and pasting you will want to use the check mark in Gparted on each one to complete that actions, and then I checked back and forth to see all the same partitions on the SSD drive, and it looks just like the USB drive now.</h7>
<br>
<span style="display:block; background-color:red; width:100%; height:2px;"></span>
<h7 style="text-align: left;">I then disconnected the USB driver correctly from the Linux box and then plugged that back into my Xpenology NAS and fixed the BIOS to first boot from that SSD drive, and it booted just like the USB drive; without any problems, it is working the same as the USB drive, but now it is the SSD drive and that is much faster for the loading time. Well worth it.</h7>
