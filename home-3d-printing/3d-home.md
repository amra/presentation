---
title: Innovation_Lab_Template
highlightTheme: zenburn
revealOptions:
    transition: 'fade-out'

---
## 3D printing at home

![](3d-home/pikachu-model.png) <!-- .element width="28.5%" -->
![](3d-home/pikachu-slicer.png) <!-- .element width="30%" -->
![](3d-home/pikachu-print.png) <!-- .element width="30.5%" -->

---
## 3d print series
1. **<span style="color:yellow">printing at home</span>**
1. modeling
1. print technologies
---
## 3D print = 2d print in layers
<video  src="3d-home/teleport-animation.webm" controls data-autoplay loop></video>
---
## Technology tree
![Technology tree](3d-home/technology-tree.png)
----
## Technology tree FDM
![Technology tree](3d-home/technology-tree-FDM.png) <!-- .element width="15%" -->
<span style="color: #222">...................</span>
![Technology tree](3d-home/technology-tree-FDM-companies.png) <!-- .element width="15%" -->

---
## History
![First 3D printer](3d-home/first-3d-printer.jpg)

SLA-1, the first 3D printer

invented by Chuck Hull in 1983

<!--
link: https://www.sculpteo.com/blog/2016/12/14/the-history-of-3d-printing-3d-printing-technologies-from-the-80s-to-today/
FIND: timeline
- https://www.google.cz/search?q=3d+printing+history+timeline&oq=3d+print+history+timelin&aqs=chrome.1.69i57j0j69i64l2.9015j0j7&sourceid=chrome&ie=UTF-8
- https://www.google.cz/search?q=3d+printing+history+timeline&source=lnms&tbm=isch&sa=X&ved=0ahUKEwi36Zj4ps7aAhUGDuwKHRKuC08Q_AUICigB&biw=1855&bih=1110
-->
----

- 1980: first patent by japanese Dr Kodama Rapid prototyping
- 1984: Stereolithography by french then abandoned
- 1986: Stereolithography taken up by Charles Hull
- 1987: First SLA-1 machine
- 1990: First EOS Stereos system
- **<span style="color:yellow">1992: FDM patent to Stratasys</span>**
----
- 2006: An open source project is initiated (Reprap)
- 2009: FDM patents in the public domain
- 2009: MakerBot was founded
- 2011: Cornell University began to build 3D food printer.
- 2013: “3D printing” in Obama’s State of the Union speech
- 2015: Carbon 3D issues their revolutionary ultra-fast CLIP 3D printing machine

---
## FDM schematic
![Hot end extruding](3d-home/fdm-technology.jpg)

----
## Detail
Material Extrusion

![Hot end extruding](3d-home/hot-end-extruding.jpg) <!-- .element width="70%" -->

---
## Models
![](3d-home/print-01-rpi-case.jpg)  <!-- .element width="20%" -->
![](3d-home/print-02-cell-phone-stand.jpg)  <!-- .element width="20%" -->
![](3d-home/print-03-lamp.jpg)  <!-- .element width="20%" -->
![](3d-home/print-04-drone.jpg)  <!-- .element width="20%" -->
![](3d-home/print-05-gramophon-horn.jpg)  <!-- .element width="20%" -->
![](3d-home/print-06-star-wars-lightsaber.jpg)  <!-- .element width="20%" -->
![](3d-home/print-07-go-pro-skateboard-cam.jpg)  <!-- .element width="20%" -->
![](3d-home/print-08-squirtle.jpg)  <!-- .element width="20%" -->

----
## Model download
- thingiverse
- yourmagine
- github

----
## Modeling
- separate presentation

---
## Slicer
Slicer = print planner

![](3d-home/slicer-example.png) <!-- .element width="70%" -->

----
Stl &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; GCode

![](3d-home/file-stl.png) <!-- .element width="32%" -->
![](3d-home/file-gcode.png) <!-- .element width="32%" -->

----
## Slicer settings
- material <span style="color:green">temperature, design</span>
- layer height <span style="color:green">smaller = longer</span>
- speed <span style="color:green">higher speed = lower quality</span>
- print profiles

----
## Slicer settings example
![](3d-home/slicer-slic3r-settings.jpg) <!-- .element width="40%" -->
![](3d-home/slicer-slic3r-settings-advance.png) <!-- .element width="40%" -->

----
## Slicers

Slic3r &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Slic3r PE &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Cura &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Simplify3D

![](3d-home/slicer-logo-slic3r.png)  <!-- .element width="20%" -->
![](3d-home/slicer-logo-slic3r-prusa.png) <!-- .element width="20%" -->
![](3d-home/slicer-logo-cura.png) <!-- .element width="20%" -->
![](3d-home/slicer-logo-Simplify3D.jpeg) <!-- .element width="20%" -->

---
## Materials

![](3d-home/material-lion.jpg) <!-- .element width="80%" -->

----
## Material properties

![](3d-home/material-properties.png) <!-- .element width="45%" -->

----
## Material basics
<img style="float: right; width: 60%" src="3d-home/material-test.jpg">

- PLA
- ABS
- Nylon
   - (moisture)
- PET
- PETG
- ASA
- Carbon fiber

Note: https://www.simplify3d.com/support/materials-guide/   https://blog.tinkercad.com/materialsguide/

----
## Flexible
- TPE, TPU
- 98A, 92A

![](3d-home/material-flexible.jpg) <!-- .element width="40%" -->
![](3d-home/material-flexible2.jpg) <!-- .element width="42%" -->

----
## Supports
- PVA
- HIPS
- (multimaterial printer required)

![](3d-home/material-support3.jpg) <!-- .element width="40%" -->
![](3d-home/material-support2.jpg) <!-- .element width="40%" -->

----
## Mixture - wood

![](3d-home/material-wood.jpg) <!-- .element width="60%" -->

----
## Mixture - metal
- metal: brass, copper, iron
- (weight)

![](3d-home/material-metal.png) <!-- .element width="45%" -->
![](3d-home/material-iron.jpg) <!-- .element width="40%" -->


----
## Special
- color changing
- fire retardant

![](3d-home/material-thermo.jpg) <!-- .element width="40%" -->
![](3d-home/material-fire-retardant.jpg) <!-- .element width="42.5%" -->

----
## Special
- glow in the dark

![](3d-home/material-glow.jpg) <!-- .element width="40%" -->


----
## Filament maker
![](3d-home/filament-maker-strooder.jpg) <!-- .element width="40%" -->
![](3d-home/filament-maker-pellets.jpg) <!-- .element width="40%" -->

---
## Usage
- projects
- home things
- design

---
## Print - overhangs/supports
![](3d-home/overhangs-fail.jpg) <!-- .element width="38%" -->
![](3d-home/overhangs-print.jpg) <!-- .element width="57%" -->

----
## Print issues
![](3d-home/problem-Blobs-And-Zits.jpg) <!-- .element width="20%" -->
![](3d-home/problem-Grinding-Or-Stripped-Filament.jpg) <!-- .element width="20%" -->
![](3d-home/problem-Layer-Shifting.jpg) <!-- .element width="20%" -->
![](3d-home/problem-Layers-Splitting-Or-Cracking.jpg) <!-- .element width="20%" -->
![](3d-home/problem-Over-Extruding.jpg) <!-- .element width="20%" -->
![](3d-home/problem-Over-Heating.jpg) <!-- .element width="20%" -->
![](3d-home/problem-Print-Not-Sticking-To-Bed.jpg) <!-- .element width="20%" -->
![](3d-home/problem-Under-Extruding.jpg) <!-- .element width="20%" -->

---
## Parts
<img style="float: right; width: 60%" src="3d-home/printer-schema.png">
- Type
- Frame
- Electronics
- Extruder
- bed
- auto bed leveling

----
## Type: Cartersian

![](3d-home/printer-prusa-mk2.png) <!-- .element width="40%" -->
![](3d-home/printer-ultimaker.jpg) <!-- .element width="40%" -->

----
## Type: Delta

![](3d-home/printer-SeeMeCNC-Rostock.jpg) <!-- .element width="40%" -->

----
## Electronics
RAMPS <span style="display:inline-block; width: 100px;"></span> Rambo Einsy <span style="display:inline-block; width: 100px;"></span> Duet

![](3d-home/electronics-ramps.jpg) <!-- .element width="30%" -->
![](3d-home/electronics-rambo-einsy.jpg) <!-- .element width="30%" -->
![](3d-home/electronics-duet.jpg) <!-- .element width="30%" -->

----
## Firmware
Marlin

![](3d-home/firmware-marlin-logo.png) <!-- .element width="30%" -->
![](3d-home/firmware-marlin-configuration.jpg) <!-- .element width="60%" -->

----
## Extruder

![](3d-home/parts-extruder-prusa.png) <!-- .element width="40%" -->
![](3d-home/parts-extruder-titan.jpg) <!-- .element width="40%" -->

----
## Hot end
![](3d-home/parts-hotend-e3d.png) <!-- .element width="40%" -->
![](3d-home/parts-hotend-kraken.jpg) <!-- .element width="40%" -->


----
## Nozzle
<img style="float: right; width: 20%" src="3d-home/parts-nozzle-ruby.jpg">
<img style="float: right; width: 20%" src="3d-home/parts-nozzle-015.jpg">

Hole: 0.15-1.2mm

- brass
- copper
<img style="float: right; width: 20%" src="3d-home/parts-nozzle-set.jpg">
<img style="float: right; width: 20%" src="3d-home/print-thick-layers.jpg">
- ruby
- hardened steel
- stainless



---
## 3d pen
![](3d-home/pen-example.jpg) <!-- .element width="40%" -->
![](3d-home/pen-3doodler.jpg) <!-- .element width="40%" -->
---
## Companies in 3d printing
Open source:
- Prusa
- Lutzbot
- BCN3D
- Ultimaker

Commercial:
- Stratasys
- 3D Systems
---
## What to buy - Prusa i3 MK3
![](3d-home/printer-prusa-mk3.jpg) <!-- .element width="40%" -->
![](3d-home/printer-prusa-mk3-mm.jpg) <!-- .element width="40%" -->

speed, low noise, bed leveling, upgrade kits,
magnetic heatbed with replaceable PEI spring steel, ...

----
## China
Creativity CR-10 <span style="display:inline-block; width: 150px;"></span> Anet A8

![](3d-home/printer-cr-10.jpg) <!-- .element width="40%" -->
![](3d-home/printer-anet-a8.jpg) <!-- .element width="40%" -->

----
- https://www.3dhubs.com/best-3d-printer-guide
- https://all3dp.com/1/best-3d-printer-reviews-top-3d-printers-home-3-d-printer-3d/
- Prusa, ...
- Not CRS-10, Tivo Tarrantula, ...

---
## Links
- https://www.3dhubs.com/what-is-3d-printing
- https://www.3dhubs.com/knowledge-base
