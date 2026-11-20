---
layout: page
title: "Macintosh Portable battery charger tray"
description: "A 3D-printed charger tray for Macintosh Portable lead-acid batteries that makes reliable contact with the recessed terminals. STL included."
permalink: /projects/macintosh-portable-battery-charger-tray/
redirect_from:
  - /Macintosh-Portable-Battery-Charger-Tray-f72ddd18b8db4fe281274039afd3407f
image: /projects/macintosh-portable-battery-charger-tray/images/1_fb695a1003c1489d23b6e6f74204369b.jpg
date: 2023-08-13
related:
  - macintosh-portable-powerbook-1x0-power-adapter-bench
  - mactwister-maccon-dayna-etherport-rj45-breakout
  - macintosh-classic-ii-performa-200-fpu-card
---

## Why is that useful?

I happen to own three Macintosh Portables. Those computers use a 3-cell lead-acid battery, which consists of Enersys Cyclon cells. The batteries cannot be kept installed in the computer, as they get completely drained within 2-3 months and are irreversibly damaged when stored empty.

So I kept my stash of batteries separately, but then what’s the best way to charge them every 6-12 months? I’ve used a “smart” RC battery charger, but **it was a real pain to reliably connect wires to the battery, which has recessed contacts.**

Apple actually offered an external charger for the Portable:

[![Apple's original external battery charger for the Macintosh Portable](images/1_fb695a1003c1489d23b6e6f74204369b.jpg){: width="1600" height="1063"}](originals/1_fb695a1003c1489d23b6e6f74204369b.jpg)

Source: [https://www.worthpoint.com/worthopedia/apple-brand-macintosh-portable-1801509065](https://www.worthpoint.com/worthopedia/apple-brand-macintosh-portable-1801509065)

So the plan was to create something similar using a 3D printer and off-the-shelf components.

## The design

The idea was fairly simple: make a 3D-printable tray that holds the battery and makes reliable contact with the battery contacts.

The original charger used spring-loaded contacts (i.e. really large-diameter pogo pins). The choice at the usual suppliers was limited, but I found good candidates on Aliexpress:

[![A578 spring-loaded pogo pin, 6 mm diameter, 16.5 mm long](images/Untitled.png){: width="433" height="445" loading="lazy"}](originals/Untitled.png)

Link: [https://www.aliexpress.com/item/1005003405928702.html](https://www.aliexpress.com/item/1005003405928702.html) (make sure to pick A578)

The A578 type has a large diameter, so relatively high currents can flow without too much resistance, and enough travel (5mm) to tolerate some play when placing the battery.

Now about the tray. I found a 3D printable model of a Portable battery on Thingiverse, which was a very good start:

[Macintosh Portable Battery Enclosure (M5137) by StephenLulz](https://www.thingiverse.com/thing:5185715)

Then I designed a tray resembling the original one in Fusion 360 around the battery model and including the A578 pins:

[![Fusion 360 render of the Macintosh Portable battery charger tray with pogo pins](images/MacPortableCharger_v38_small.png){: width="1080" height="623" loading="lazy"}](originals/MacPortableCharger_v38_small.png)

And that’s it - print it, press the pins into the printed model, solder some wires and you’re done. The brown color of the tray is not exactly my choice - it’s recycled filament to limit the environmental impact of 3D printing 🌍

[![3D-printed Macintosh Portable charger tray with wires, next to a Portable battery](images/IMG_1478_small.png){: width="1210" height="907" loading="lazy"}](originals/IMG_1478_small.png)

<aside class="callout" markdown="1">
💾 Here’s the STL file to print the battery tray:

[MacPortableCharger v37.stl](originals/MacPortableCharger_v37.stl)

</aside>

## Usage

I used the tray together with an RC battery charger set to charge a 3-cell lead battery. I crimped a typical JST SYP battery connector to make sure the tray is safe, without a possibility to short the battery or to invert the polarity.

[![Macintosh Portable battery in the printed tray, charging from an RC battery charger](images/Untitled.jpg){: width="1600" height="1200" loading="lazy"}](originals/Untitled.jpg)

## Appendix: Macintosh Portable battery cell info

By the way, the original type of cells is still available, I purchased them from the TME electronics distributor and they worked great (and were exactly like the originals):

[EnerSys Cyclon X 0800-0004 (2V, 5Ah) at TME](https://www.tme.eu/en/details/cyclon-x/acid-cells/enersys/0800-0004/)
