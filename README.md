# Ornament and Crime
## General
This is another version of the open-source project Ornament & Crime (o_C), a multi-purpose CV generator module with several firmware versions available.
The module is running on a Teensy 3.2 board.

More details are available on the original website [ornament-and-cri.me](https://ornament-and-cri.me/).

I also uploaded a [Youtube video]() about details and issues of the module built.

## Module Built and PCBs
The original design is mainly using SMD components, so there is only one PCB housing all components and front panel control parts.

I replaced several components with through-hole versions to make the built a bit easier. Consequently, there are two PCBs required, a main board and a control borad, making the module deeper (42mm) than the original one (25mm). But still there are several SMD components in the design.

If you want to build the module yourself, I uploaded the schematic, the BOM and the Gerber files for the PCB.

There are two different versions for the control board, an "original" and a "Thonk" version.
Reason is that for my own module, I am using specific  3.5mm jack sockets - MJ-355 from Marushin - and switches available at my local electronics shop.

However, since most DIY projects for Eurorack modules out there are using so-called THONKICONN jacks, as they are provided by Thonk in the UK, and a different set of switches, I also created a version with footprints for those components. Details are given in the BOM.
Choose the one you need.

I created the Gerber files with the online tool EasyEDA and ordered it at JLCPCB.
I cannot guarantee, if this set of zipped Gerber files works also for other providers, like e.g. PCBWay. I have not tried that. But I saw online, that others did it.

If you want to know about my DIY building process, take a look at those two YouTube videos:
- [How I design PCBs for my Eurorack Synth Modules](https://youtu.be/pXtuV9Pv-m4)
- [Eurorack Module Synth - Building an Electric Druid Wavetable Oscillator Module](https://youtu.be/ECpdo4HfqLg)

## Panel Layout
I added the information about hole coordinates for the front panel in the folder PanelLayout, refering to the component layout in the Gerber files. The layout is the same for both versions.

## Calibration
Details about the calibration procedure are available on the orginal [o_C website](https://ornament-and-cri.me/).
