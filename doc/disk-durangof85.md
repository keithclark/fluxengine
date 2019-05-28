Disk: Durango F85
=================

The Durango F85 was an early office computer based around a 5MHz 8085 processor,
sold in 1977. It had an impressive 64kB of RAM, upgradable to 128kB, and ran
its own multitasking operating system call DX-85M, as well as CP/M. It had an
interesting electric-typewriter form factor, with a little monitor sitting on
the side of it --- in operation you were facing the 14" printer.

It was touted as being portable. Which it was, if you were strong; the story
is that they had to do an extensive search to find someone capable of lifting
it for the following photo...

<div style="text-align: center">
<img src="durangof85.jpg" style="max-width: 60%" alt="A Durango F85, held precariously">
</div>

...and even then, they had to airbrush out the tendons in her neck from the
effort!

It used 5.25 soft-sectored disks storing an impressive-for-those-days
480kBish on a side, using a proprietary 4-in-5 GCR encoding. They used 77
tracks, 12 sectors and 512 bytes per sector. Later models used double-sided
disks; I don't have access to an image of one so don't know how they work
(there's a suspicious looking spare byte in the sector header which could
store the side). As always, if you have one, please [get in
touch](https://github.com/davidgiven/fluxengine/issues/new).

Reading discs
-------------

Just do:

```
.obj/fe-readf85
```

You should end up with an `f85.img` which is 472064 bytes long.

Useful references
-----------------

There's amazingly little information about these things.

  * [Chuck Guzis' F85 page](http://www.sydex.com/durango/durango.html) with lots of pictures
