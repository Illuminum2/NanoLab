# NanoLab

Made by: @Iluminum2  
Repo link: [https://github.com/Illuminum2/NanoLab](https://github.com/Illuminum2/NanoLab)  
Total hours so far: 12.5
- [x] I have a 3D printer

## Idea
A small and thus hopefully portable 3D printer that allows printing high quality models with a whole bunch of different materials, including ABS and ASA

## Design
###  Goals
- Cost(lower than ~300€ grant + Own Parts)
- Quality(Best quality achievable within the budget)
- Sacrifice speed for points above

### Build Volume
- 100(length)x100(width)x100-150(height) mm

### Printable materials
- PLA
- PETG
- TPU
- ABS
- ASA

### Printer size
- To be determined, as small as possible
- Electronics contained in chassis, only exception can be PSU

### Chassis
- Clear(gray) aluminum extrusion
- Sizes to be determined
- Blind joints
- Optionally angle brackets as well(if budget allows, probably unnecessary)
- Electronics and print head at bottom, print bed above, upside down printing
- Tinted translucent plastic cover(resin cast/print)
- Printed bottom cover

### Motion platform
- CoreXY system
- Dual linear rail y-axis mounted on extrusion
- Mono linear rail x-axis mounted on y-axis linear rails, maybe aluminum extrusion support, but better would be CF plate reinforcement
- Dual or mono linear rail z-axis on one extrusion(bed only mounted on one side)
- 3d printed belt housing mounted on extrusion and linear rails
- AB drives mounted on backside of aluminum square, gear ratio to be determined
- Fiberglass core GT2 belts for XY mechanism, routed in extrusion if possible
- Fiberglass or steel core GT2 belts for z-axis

### Print head
- Bowden extruder with PTFE Bowden tubes
- 45° mounted hot end for improved space efficiency or Positron 90° hot end

## Day 1 (Mar 14) 4.5h
I did general research, found a lot of useful guides and videos, and outlined the basic design idea. I also made a few sketches in my notebook to get a better idea of how everything should come together.

## Day 2 (Mar 15) 8h
I did a lot more research, made a few more sketches, and tore down my 3D printers print head to get a better understanding of it. I also took a look at the [Positron LT](https://github.com/Audiotronix/Positron_LT) 3D model (a fork of the [Positron V3](https://github.com/Positron3D/Positron)). After a lot of consideration, I think I am going to go for a Bowden extruder setup and a 45° mounted hot end, but if the budget allows I want to get a Positron 90° bent hot end, but those are over 70$.
