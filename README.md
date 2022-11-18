# Ornament and Crime
## General
This is another version of the open-source project Ornament & Crime (o_C), a multi-purpose CV generator module with several firmware versions available.
The module is running on a Teensy 3.2 board.

More details are available on the original website [ornament-and-cri.me](https://ornament-and-cri.me/).

I also uploaded a [Youtube video](https://youtu.be/8bC33xTxlGM) about details and issues of the module built.

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

![OAC](https://user-images.githubusercontent.com/97026614/201452171-8a0f7efd-314b-4ca5-a5a5-de1b3846881c.jpeg)

![OACFront](https://user-images.githubusercontent.com/97026614/201452194-d8dd5a0f-bbde-4ce9-9213-24ea275667e4.jpeg)

![IMG_6799](https://user-images.githubusercontent.com/97026614/202618088-b5275f5b-a1b9-460b-a0eb-39020c6728eb.jpeg)

![IMG_6800](https://user-images.githubusercontent.com/97026614/202618147-adc45a3a-fcca-4fdc-8159-eaeaa2834cb0.jpeg)

![OAC_MainSoldered](https://user-images.githubusercontent.com/97026614/201452241-d339cfeb-dba2-46a2-8628-5870b5b4f6be.jpeg)

<img width="490" alt="Screenshot 2022-11-12 at 11 20 36" src="https://user-images.githubusercontent.com/97026614/201452259-16ad0a46-998c-42b3-8577-d1cd2942a077.png">

<img width="490" alt="Screenshot 2022-11-12 at 11 20 01" src="https://user-images.githubusercontent.com/97026614/201452265-f357d7c6-23db-4dcc-833a-c688afd9d45c.png">

<img width="491" alt="Screenshot 2022-11-12 at 11 21 31" src="https://user-images.githubusercontent.com/97026614/201452272-373a62c8-1cd5-4ab9-ab89-6aa2c9cf3f79.png">

<img width="491" alt="Screenshot 2022-11-12 at 11 21 48" src="https://user-images.githubusercontent.com/97026614/201452282-b2fd95cd-6473-4c22-babc-1578237a0cf0.png">
