---
layout: page
title: "Tektronix 22xx 4-pin cap adapter"
description: "An adapter PCB to replace the hard-to-find 4-pin high-voltage PSU capacitor in Tektronix 22xx oscilloscopes (2230, 2232) with a modern snap-in cap."
permalink: /projects/tektronix-22xx-4-pin-cap-adapter/
redirect_from:
  - /Tektronix-22xx-4-pin-cap-adapter-f6a031720d164a31ae33c158cec04b6e
---

When servicing vintage CD players, I need a capable scope with 50-100 MHz bandwidth. I came across a neat Tektronix 2232, working but clearly requiring new capacitors.

All but one caps are of standard dimensions/footprint - but the high voltage PSU cap has 4 pins and I couldn’t find a decent modern replacement.

The project is about an adapter for the 4-pin capacitor for Tektronix 22xx (2230, 2232 etc.) series. 4-pin caps are generally hard to come by these days and it's much easier to replace those with a modern Snap-In type.

The project files are located in the GitHub repo: 

[https://github.com/dymczykm/22xx_tek_cap_4pin](https://github.com/dymczykm/22xx_tek_cap_4pin)

![](https://github.com/dymczykm/22xx_tek_cap_4pin/raw/main/pictures/bottom_view_3d.png)

![](https://github.com/dymczykm/22xx_tek_cap_4pin/raw/main/pictures/tek_4pin.png)

### Which devices does it fit?

The adapter should fit all 22xx with a switching power supply and a 270uF/450V cap (potentially others too). Definitely Tektronix 2232, 2230, 2245, 2245A, 2246, 2246A, 2247A, 2252.

### What is necessary?

Parts used:

- 1x LGW2W271MELC30 (Digikey: 493-8572-ND) Nichicon 270uF 450V 105*C cap, but others with similar dimensions will fit too
- 4x Harwin H2101-01 (Digikey: 952-1433-ND) pins

With these parts, the cap with an adapter nicely fits under the HV plastic shield and the pins are well aligned with the PCB.

![](https://github.com/dymczykm/22xx_tek_cap_4pin/raw/main/pictures/IMG_2318.JPG)

![](https://github.com/dymczykm/22xx_tek_cap_4pin/raw/main/pictures/IMG_2319.JPG)

### References

This project is loosely based on the existing project for Tek 7xxx scopes: [https://github.com/peekpt/tekcaps](https://github.com/peekpt/tekcaps)
