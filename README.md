Idea
====

This should be some sort game console-y.
Requied peripherals:
- LCD (RGB interface? hdmi?)
- DDR3
- buttons
- Audio
- USB
- debug uart
- status LED
- PCIe ?

Plan:
====

- 1. decide peripherals
- 2. assign pins
- 3. create symbol

 Toradex layout guidelines:
 https://developer.toradex.com/carrier-board-design/carrier-board-design-guides

Routing Interfaces:
 ===========

 PCIe, USB, HDMI	50
 Ethernet		55/86
 LVDS			55/100

Meandres:
segment size: 	1.5x trace width
clearance:	4x trace width

signal speed:
v = c / sqrt(Er) ~= 150 um/ps

design rules:
misc/layout_design_guide.pdf
