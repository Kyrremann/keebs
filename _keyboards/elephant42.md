---
layout: post
title:  "Elephant42"
categories: [ '40', split ]
image: assets/images/elephant42.png
source: https://github.com/illness072/elephant42
---

I have taken a liking to the concept of a split-board, and this is my second board. Compared to the
[Ergodash Mini]({{ site.baseurl }}/ergodash-mini), the Elephant42 has bigger bend for the thumb cluster, and is more
staggered in it's ortholinear columns. This is especially noticeable when I'm trying to type `A`, but end up pressing
`Q`.

It also has room for a small OLED screen above the micro controller, but I don't have anyone, so haven't tried that out
yet.

![The back side of the Elephant42]({{ "assets/images/elephant42-back.png" | absolute_url }})

Even though I really like to the look of the Elephant42, it's not much used, I didn't even bother to solder in the RGB
LED's (as there is one for each key, would probably look cool though). The reason for that is that the stagger is too
much for me, even with my short fingers. Was also missing some keys on the left hand, so something with less stagger and
a couple more keys would probably be more ideal for me.

Should mention that it is hot-swappable, meaning that you can change the switches on the fly! That's a huge selling point
for me.

## Get your own

Haven't seen the Elephant42 sold anywhere, but it's an open-source keyboard, so everything you need is at
[github/illness072](https://github.com/illness072/elephant42). The build for this is failry simple, but the diode for
the switch are surface mounted (SMD), so some small tweezers are necesarry. No English build guide as I could find, but
there not much to guide if you've built some keyboards before. Maybe I should make my own English guide, still have an
extra set of PCB left. If you order PCB to be produce, be aware that some companies don't like the compact layout with
the part that your supposed to break of when you get it. So you may need to split the gerber/PCB in two before ordering.

![The layout of the Elephant42]({{ "assets/images/elephant42-layout.png" | absolute_url }})
