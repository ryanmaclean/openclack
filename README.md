OpenClack.TKL
=========

#####Preface:

This project is licensed under the GPL.  See gpl.md.

This repo contains all the source files needed (minus firmware for the time being) to create a Tenkeyless Mechanical keyboard.  The keyboard is compatible with Cherry MX switches and both Cherry Corp and Costar branded stabilizers.
In order to actually build this keep in mind you'd need access to the following.
- CNC, laser or Waterjet cutting facility for fabrication.
- Soldering iron and supplies.
- A source for your switches, stabilizers and electronic components.
- Somewhere to fabricate your pcb.

#####The keyboard:

A bit of info on what this keyboard actually is. : )
- Tenkeyless layout.
- Supports LEDs for each key.
- Does not require a resistor for each LED.
- N-Key rollover, no ghosting, 1 diode per switch.
- Firmware which allows for custom key mapping, macros, debouncing and LED control.
- Mini-B connector.
- Controller is a Teensy 2.0++.

#####Project files:

- /kicad_files/*
 - Various files which make up the kicad project.  Open the file "toasty_tkl.pro" and the rest of the files will get loaded up by kicad.
- /dxf_plots/*
 - These are DXF plots of layers of the case.
- /notes/*
 - Notes explaining the LED configuration, random bits of stuff, part list.  Info on the boost converter, resitors and general math.
- 3D_mockup.skp
 - I exported all my DXFs to SketchUp and then did some rough modelling.  This isn't 100% accuracte either (pretty close though).  It's meant to give a rough idea and help eyeball some potential problems.
- /inkscape_plots/*
 - These are ready to go files for an online fabrication site: https://www.ponoko.com/
- openclack-tkl_gerberplots.zip
 - These are ready to go files for PCB fabing.  I sent these to: http://www.myropcb.com/
 
#####Progress:

- [X] PCB
- [x] Backplate 
- [x] Case
- [ ] Firmware
- [X] Part List
- [ ] Guide to build (Photos)
- [ ] Prototyping
- [ ] Revision after prototyping.

#####Sources/Thanks:
Thanks to the folks at http://deskthority.net/ for helping out when I had questions about measurements!
Extra big thanks to BathroomEpiphanies.  Wouldn't have been able to do it without your amazing wiki.
[Check it out here!](http://deskthority.net/wiki/KiCAD_keyboard_PCB_design_guide)