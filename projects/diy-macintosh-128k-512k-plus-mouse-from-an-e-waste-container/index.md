---
layout: page
title: "DIY Macintosh 128K/512K/Plus mouse from an e-waste container"
description: "Building a working Macintosh 128K/512K/Plus mouse from an old optical mouse with quadrature outputs, a DB-9 connector and e-waste parts."
permalink: /projects/diy-macintosh-128k-512k-plus-mouse-from-an-e-waste-container/
redirect_from:
  - /DIY-Macintosh-128K-512K-Plus-mouse-from-an-E-Waste-container-0b674e2e4d84493db69c6d5f2adb16ea
image: /projects/diy-macintosh-128k-512k-plus-mouse-from-an-e-waste-container/images/Untitled.jpg
---

I once acquired a Macintosh Plus in pretty good condition locally, but without a mouse or keyboard. A keyboard showed up some weeks later, but I struggled to find a compatible mouse locally in Switzerland.

From my undergrad days, I somehow recalled that early optical mouse sensors actually had quadrature outputs, simulating the behavior of mechanical mice with a shutter wheel. That should fit!

The project was triggered after digging out the mouse, a DB-9 connector and an old Ethernet cable from an e-waste container at work (shown here already assembled):

[![DIY Macintosh 128K/512K/Plus mouse from an e-waste container, photo 1](images/Untitled.jpg)](originals/Untitled.png)

Inside, the ADNS-2051 optical mouse chip directly outputs quadrature signals as required by a Macintosh. No conversion using a microcontroller or any other circuitry is needed.

[![DIY Macintosh 128K/512K/Plus mouse from an e-waste container, photo 2](images/Untitled%201.jpg)](originals/Untitled%201.png)

Beautiful, ADNS-2051 actually directly outputs quadrature signals:

[![DIY Macintosh 128K/512K/Plus mouse from an e-waste container, photo 3](images/Untitled%202.png)](originals/Untitled%202.png)

So it's enough to solder the X1/X2/Y1/Y2 lines to the chip itself (XA/XB/YA/YB). The two blue wires go to ground, the orange one to +5V and the orange-white one to the button's tactile switch.

Ready to use it with my faithful Plus :)

[![DIY Macintosh 128K/512K/Plus mouse from an e-waste container, photo 4](images/Untitled%203.jpg)](originals/Untitled%203.png)

Aaaand it works!

[![The DIY mouse moving the cursor on a Macintosh Plus](images/u3pkhcsuehw61.gif)](originals/u3pkhcsuehw61.gif)
