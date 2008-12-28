---
layout: post
title: Drobo troubles
---

# [Drobo][drobo] troubles

  [drobo]: http://drobo.com "Data Robotics Inc"

Got a [Drobo][drobo] and I really want to like it, but I've been having problems.

Here's what I did:

I had two Western Digital 1TB GreenPower drives I'd been planning to set up in a JBOD with external cases, so I put one of them into the Drobo.

It came up nicely.  The Drobo software said that my data wasn't going to be protected (with just one drive).

So I inserted the second one.  After a few seconds, it said it was the same capacity (900+ GB) but now my data was protected.  Great!

So I disconnected it from my Macbook Pro (via Firewire) and attached it to my Mac mini (via USB).

Then I began to copy my 600+GB of data from my 750GB external drive to the Drobo.

The copy took overnight.

After the copy completed, I unmounted the 750GB drive, detached it from the Mac mini, and pulled out the drive.  I put it into the Drobo.

The lights went yellow for a bit, then back to green, and the software said I had more storage.  Great!

Since I had some active bittorrents running (via Transmission.app) on the original drive, I'd quit Transmission.  I started it again and it asked me 
to find the missing files.  I pointed them to my new Drobo volume, and it began to checksum them one at a time.

It didn't complete the first one (about 350MB) before it crashed (Transmission.app did).  The Mac gave me a warning about removing devices uncleanly.
And the Drobo was just sitting there with the power light green and the activity light solid green as well.

I double-checked the connections (in case the cat had knocked something loose, but my office door was closed and he wasn't in the room).

Then I unplugged the Drobo, waited a few seconds, and plugged it back in.

It appeared soon after.  I figured it was a fluke, and started Transmission again, this time watching closely.

About 70% through checksumming the first file, it happened again.  Transmission crashed, Mac warned of device removal, etc.

Flummoxed, I went through the same steps again, to verify it was truly repeatable.  It was.

So, I rebooted the Drobo a third time, and when the Drobo volume appeared on the mac, I unmounted (ejected) it.  Then I let it sit that way
(Drobo powered up, and connected to the Mac mini, but the Mac mini not mounting the device).  We're away for the day, so it'll have been sitting for 
over 24 hours by the time I return home and try again.

I really want it to work, because it's a great concept and idea.

Hopefully it's fixable, or it's a defective unit that can be fixed by replacing it.  Otherwise, I've got no alternative but to return it for a refund, 
and that'd make my wife feel badly (even though _I_ asked for it!)
