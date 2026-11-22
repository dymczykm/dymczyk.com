---
layout: page
title: "Tektronix 22xx (2230, 2232, 2245, 2246) 4-pin capacitor adapter"
description: "An adapter PCB that replaces the hard-to-find 4-pin 270 µF/450 V PSU capacitor in Tektronix 22xx oscilloscopes (2230, 2232, 2245, 2246) with a snap-in cap."
permalink: /projects/tektronix-22xx-4-pin-cap-adapter/
redirect_from:
  - /Tektronix-22xx-4-pin-cap-adapter-f6a031720d164a31ae33c158cec04b6e
date: 2020-12-28
related:
  - braun-sk2-2-restoration
  - macintosh-portable-powerbook-1x0-power-adapter-bench
  - macintosh-classic-ii-performa-200-fpu-card
---

When servicing vintage CD players, I need a capable scope with 50-100 MHz bandwidth. I came across a neat Tektronix 2232, working but clearly requiring new capacitors.

All but one of the caps are of standard dimensions/footprint - but the high voltage PSU cap has 4 pins and I couldn’t find a decent modern replacement.

This project is an adapter for the 4-pin capacitor in Tektronix 22xx series oscilloscopes (2230, 2232 etc.). 4-pin caps are generally hard to come by these days and it's much easier to replace those with a modern snap-in type.

The project files are in the GitHub repo:

[https://github.com/dymczykm/22xx_tek_cap_4pin](https://github.com/dymczykm/22xx_tek_cap_4pin)

![3D render of the Tektronix 22xx 4-pin capacitor adapter PCB, bottom view](https://github.com/dymczykm/22xx_tek_cap_4pin/raw/main/pictures/bottom_view_3d.png){: width="300" height="273"}

![3D render of the adapter mounted under a snap-in capacitor](https://github.com/dymczykm/22xx_tek_cap_4pin/raw/main/pictures/tek_4pin.png){: width="300" height="273" loading="lazy"}

## Which Tektronix scopes does it fit?

The adapter should fit all 22xx models with a switching power supply and a 270uF/450V cap (potentially others too). Definitely Tektronix 2232, 2230, 2245, 2245A, 2246, 2246A, 2247A, 2252.

## Parts list

Parts used:

- 1x LGW2W271MELC30 (Digikey: 493-8572-ND) Nichicon 270uF 450V 105°C cap, but others with similar dimensions will fit too
- 4x Harwin H2101-01 (Digikey: 952-1433-ND) pins

With these parts, the cap with an adapter nicely fits under the HV plastic shield and the pins are well aligned with the PCB.

![Assembled adapter: a Nichicon snap-in capacitor on the 4-pin adapter PCB](https://github.com/dymczykm/22xx_tek_cap_4pin/raw/main/pictures/IMG_2318.JPG){: width="300" height="300" loading="lazy"}

![Adapter with the new capacitor installed in the Tektronix 2232 power supply](https://github.com/dymczykm/22xx_tek_cap_4pin/raw/main/pictures/IMG_2319.JPG){: width="600" height="600" loading="lazy"}

## References

This project is loosely based on the existing project for Tek 7xxx scopes: [https://github.com/peekpt/tekcaps](https://github.com/peekpt/tekcaps)
