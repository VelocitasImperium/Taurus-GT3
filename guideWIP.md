# **TAURUS GT3**

![](RackMultipart20230721-1-xflpll_html_252114c19b5183ea.png)

![Shape1](RackMultipart20230721-1-xflpll_html_3250f920c94fe518.gif)

**Copyright by VELOCITAS IMPERIUM - All rights reserved**

**Files are intended only for personal use, not commercial or for resale**


* 1 - [Introduction](#1-introduction)
* 2 - [Safety notes](#2-safety-notes)
* 3 - [BOM and parts](#3-bom-and-parts)
* 4 - [Preparing 3D Printed parts](#4-preparing-3d-printed-parts)
* 5 - [PCB Assembly steps](#5-pcb-assembly-steps)
* 6 - [Clutch/Shifter links](#6-clutchshifter-links)
* 7 - [Flashing and programming the PCB(Deprecated)](#7-flashing-and-programming-the-pcb-deprecated-will-be-updated-asap)
* 8 - [Assembly](#8-assembly)
* 9 - [Troubleshooting](#9-troubleshooting)
* 10 - [Extras](#10-extras)



## 1. Introduction

We hope you find the order and assembly process smooth, and a reminder that we are always available to help through the discord. Simply post your questions in the #diy-and-simgear channel and one of our staff (or helpful members) will try to assist. This guide covers all the necessary information to assemble your wheel, as well as links to the required shifters and clutches. Without further ado, let's begin.

## 2. Safety notes

#### With any DIY project we must ensure we are safe at all times to avoid any potential injury or damage. Our recommendations are the following:

1. Always wear safety glasses, particularly when performing steps such as sanding the 3D print
2. Ensure any soldering is done in a well ventilated area, using a fan to pull away dangerous fumes if possible
3. Wear gloves to avoid later contamination when soldering with leaded solder.
4. Find a comfortable position to avoid back pain later on, this wheel takes quite a while to assemble and it is better to do it comfortably.

## 3. Bom and parts

The BOM is available [**here**](https://docs.google.com/spreadsheets/d/1FHKVDJvTqiSSPm0fXGAgw0jcgytXlTn-GmOWtaGsIfA/edit?usp=sharing)and you can make your own copy to tick off parts as you go.

It's a good idea to order everything before starting so that you don't miss anything or end up with incorrect parts. The BOM also contains some useful tips on what parts to order and recommendations, _as well as some recommended tools for the job!_ We have intentionally left some flexibility with the parts (eg: switches from either AliExpress or Mouser) so you can make the decision on how much you'd like to spend. In general, the extra money does reflect extra quality but if you think you can get a great deal somewhere else, go for it! That's the benefit of DIY 🙂 \*Velocitas Imperium are not endorsing any of these parts, just making helpful suggestions if you are struggling to source the parts yourself\*

We will now cover some specifics for ordering certain items, such as the **Graphics/Adhesives, Alcantara wrap, Carbon Fiber CNC,** and the **PCB**.

## Graphics/Adhesives

The front plate graphics can be made through different methods, depending on your tools, we found the best result is achieved with a combination of adhesive yellow vinyl and printed texts and stickers, cutted with a plotter. You will need to provide the sticker sheet and skin file (found in the Taurus Drive you have access to) to your selected sticker manufacturer and also let them know the dimensions listed below. If you are struggling to find someone to print these for you please message us on discord and we can refer you to a particular seller. Alternatively you can order these through Etsy from us.

_ **Sticker Sheet.PDF** _ _dimensions :225.361 X 116.916 mm_

_ **Taurus V2 GT3 Skin.SVG** _ _dimensions : 192.091 x 140.949 mm_


_ **\*\*\*Encoder Circles** _

_There is an alternative option for the_ _ **Encoder Circles** _ _if you'd prefer a more premium feel and also have less difficulty removing them later, which is having them UV printed on plexiglass. Note that this is just for the encoder circles, and the other smaller stickers and skin still need to be printed with the plotter.Double sided tape is used to adhere them to the wheel. A good supplier for these is_ [_michelle@szgdctech.com_](mailto:michelle@szgdctech.com) _(We also recommend to use Michelle for the Carbon Fibre CNC items, so you may be able to bundle shipping through her)_

## Alcantara Wrap

Self-adhesive Alcantara Wrap for the grips is the best option here. Try to avoid getting a cheap material (it will look like cardboard just from looking at the listing photos) as it will be difficult with the small details on the grips. We have had success in the past with "Carbins" brand wrap. **info@carbins.net** can give you more information about buying. They sell by the metre, so the minimum order is 1\*1.42m, which is more than enough to make the grips for this project and have plenty left over for other projects 😌

### Suggested alcantara/suede cutouts :

### Top 4 halves : 25x12cm / 10x5 in

### Bottom 2 halves: 18x9cm / 7x3.5 in

## Carbon Fiber/CNC

You do not necessarily need to order carbon fiber as all the parts \*can\* be 3D printed, however for wheel bases with 5nm or higher torque we really recommend going down the carbon fiber route as it will be significantly more durable and premium feeling. This will also minimize any flex in the wheel.

There are 4 files you need to provide to your chosen Carbon Fiber CNC manufacturer which are found in the CNC\>CF files on the drive.

Specify the following:

### Twill Matte Carbon Fiber

### 1x Front Plate 4mm

### 1x Rear Plate 3mm

### 2x Shifter Paddles 4mm

### 2x Clutch Paddles 4mm

As mentioned earlier we use Michelle from SZGDCTech ([michelle@szgdctech.com](mailto:michelle@szgdctech.com)) for our parts and have found her reliable and good quality.


## 3.4 PCB Order

For the PCB I suggest you use JLCPCB and follow these instructions (if you don't understand a step you can ask for help in our Discord).

Upload the gerber file to their website and leave everything default but the stackup has to be the **JLC7628** for the best result.

![](RackMultipart20230721-1-xflpll_html_48074bdfb0805b28.png)

Enable PCB assembly and leave the default options.

![](RackMultipart20230721-1-xflpll_html_e6895b068a961af3.png)

Press **Confirm** to move to the next page.

**NOTE** : You can leave the default stackup as they already use the JLC7628 as the default, but JLCPCB may change this in the future)

Upload both the BOM and CPL as shown in the photo to this new page.

![](RackMultipart20230721-1-xflpll_html_c687f1260bd3466d.png)

After hitting process BOM & CPL you will get into the list of all the components needed for the build, it is all pre-configured by us, so you will need to hit **NEXT**.

Once you have confirmed the parts you will have to select the Product description:

![](RackMultipart20230721-1-xflpll_html_97a1a2fff3d83e45.png)

and you're done, you can finish the order.

### Our advice is to use IOSS Fedex International Priority, you will already have paid the customs fees and there will be no unpleasant surprises at the customs office.

**NOTE** : if some components are out of stock JLCPCB will tell you that a component is missing,this should never happen with our PCB, so contact us by email or Discord.

**NOTE** :It should cost around 110e for two pieces(shipping included), if you get a much lower price check if you have done everything correctly.


## 4. Preparing 3D Printed parts

The following settings are intended for use with a 0.4mm nozzle and wall line count (perimeters) of 4
<table>
  <tr>
    <th>File Name</th>
    <th>Layer Height</th>
    <th>Infill</th>
    <th>Supports</th>
    <th>Est. print time</th>
    <th>Extra notes</th>

  </tr>
  <tr>
    <td>Backshell</td>
    <td>0,2</td>
    <td>60%</td>
    <td>Yes</td>
    <td>15H</td>
    <td> </td>
  </tr>
  <tr>
    <td>Shifter Mainbody</td>
    <td>0,16</td>
    <td>60%</td>
    <td>Yes</td>
    <td>1,30H</td>
    <td> </td>
  </tr><tr>
    <td>Shifter Lever</td>
    <td>0,20</td>
    <td>60%</td>
    <td>Yes</td>
    <td>30m</td>
    <td>Print on the larger side </td>
  </tr><tr>
    <td>Grips</td>
    <td>0,20/0,24</td>
    <td>60%</td>
    <td>Yes</td>
    <td>5,30H Front <br> 4,30H Rear <br> 3,30H + 2,30H Bottom</td>
    <td> Print closer to the plate <br> to prevent warping </td>
  </tr>
</table>


![](RackMultipart20230721-1-xflpll_html_672efaa9bf2f56cc.png)

## Postprocessing

For a better finish, sanding and painting are suggested, the necessary steps are as follows:

1. Spray filler primer
2. Dry sanding from 200 up to 600 grit
3. Wet sanding from 800 to 1000 grit

**NOTE**** :** Be careful with power tools on plastic, due to risk of melting.

## 5. PCB Assembly steps

## PCB Soldering

Solder the encoders and Alps 7-way switches to the front where the smd components are and the connectors to the other side, and solder the 2x3 pin header on the pcb, it will be needed to flash the PCB then you can desolder it.

| **Items Needed:**
 PCB 3x Rotary Encoders
 2x Alps 7-way switch 8x 2-pin female 90-Deg Connector 2x 2-pin female Connector 2x 3-pin female Connector
 |
| --- |

![](RackMultipart20230721-1-xflpll_html_2961241a6106ae4b.png)

![](RackMultipart20230721-1-xflpll_html_74eb0886b02cfaaa.png)

**NOTE:** The PCB may be slightly different, so refer to what is written on the PCB.

TIP: Clean the board after finishing as some types of flux or solder with flux may be corrosive.

## 12mm Connector

| **Items Needed:**
 Coiled USB cable12mm connector male/femaleHeatshrink (optional) |
| --- |

In this section we're going to suggest that you use our connector pinout, we prefer to have the data lines in the furthest position from each other, also following this pinout will ensure compatibility with our past and future steering wheels.

### **NOTE:** You can use your own pinout, just make sure that the USB standard is respected at the end of the USB A connector (you can check this by checking the continuity from the USB A male connector to the one on the PCB). ![](RackMultipart20230721-1-xflpll_html_27f4409e4d4c2fec.png)

Solder the 4 pin wires to the GX12, the side with the notch (on the right) goes out and should be used for reference.

![](RackMultipart20230721-1-xflpll_html_bb371ff12dff57bd.png) ![](RackMultipart20230721-1-xflpll_html_bda1c25a430585f5.png)

![](RackMultipart20230721-1-xflpll_html_a5b54ccaf5606021.png) ![](RackMultipart20230721-1-xflpll_html_13845194123f182a.png)

Using the previous reference it is now time to solder the cable, before you start cutting and soldering make sure the cable is thick enough for the connector, otherwise use heat shrink on the last section to increase the diameter.

Strip off 1cm of the black insulation and 4 to 5mm of the internal wires, then solder the USB cable to the GX12 male connector with the notch facing up, before closing the connector, put some hot glue in the middle of the cables.

**Note** : If the cable has different colors, you'll have to use a tester to make sure to respect the usb pinout

## 12mm Buttons

Solder a 2-pin cable to each, cable orientation is not important, the use of heat shrink tubing is also recommended, otherwise a dab of glue between the contacts will do.

## 6. Clutch/Shifter Links

![](RackMultipart20230721-1-xflpll_html_ca284bb25806b513.png)

### The one shown in the photo is made by [JLCPCB](https://jlcpcb.com/) in Nylon material (SLS).

You should already have all the parts for these as they are specified in the BOM, however these are actually 2 separate Velocitas Imperium projects so I will link their assembly guides here. They can also be use on any other VI project wheels:

## [Shifter Link](https://www.printables.com/model/372871-magnetic-shifter) & [Clutch Link](https://www.printables.com/model/372151-magnetic-clutch) ![](RackMultipart20230721-1-xflpll_html_97f24a0372db1a77.png)

## 7. Flashing and Programming the PCB (deprecated, will be updated ASAP)

Before finalizing the assembly we want to make sure the buttons work, so we will start by explaining the process for flashing the bootloader. Unlike some other projects, the Arduino board we had you order in the BOM is simply there to flash the chip on the PCB itself and will be removed later. Before starting these steps it is recommended you remove any other arduino devices you may have plugged into your PC and close any programs that may be using/interfering such as SimHub.

## Flashing bootloader - ArduinoIDE


Flashing the bootloader is mandatory as they come without one, unlike the regular boards you can buy online.

You will need another Arduino for this process (or you can use whatever tools you like, but they are not covered in this guide, I use another Arduino as it's pretty common to have a spare), atmega328p(nano) or 32u4(micro) based boards are the same, you can follow the official guide on the Arduino website or you can read on below, but this is just a summary of the Arduino guide.

You can start by uploading the ISP sketch to your Arduino board as shown in the picture:

![](RackMultipart20230721-1-xflpll_html_ea0d74379d9faf9b.png)

Then you need to connect your Arduino board to the Taurus PCB, you need to connect the 5V, GND, MISO, MOSI, SCK, D10 pin to the corresponding pins on the Taurus PCB, D10 goes to RESET.

You can follow the silkscreen on the Taurus PCB as it's self-explanatory.

**NOTE** : If you are having trouble flashing the bootloader, you may have accidentally connected the RESET pin of your Arduino board to the Taurus PCB, the RESET pin on the Arduino board is not needed in this procedure, you will need to use the D10 pin instead.

![](RackMultipart20230721-1-xflpll_html_5687c9a50de9a692.png)

You can use this table to understand which pins are MISO, MOSI and SCK on your Arduino board:

![](RackMultipart20230721-1-xflpll_html_97f453d0f32757b2.png)

Note:you can use this table with your Pro micro following the Leonardo pinout, or the UNO if you're using an arduino Nano

Here is an example if you're using a Pro micro as programmer ![](RackMultipart20230721-1-xflpll_html_9e610ab710c26860.png)

Once you have completed the wiring you can plug the Arduino board into your PC, if you have done everything correctly you will notice that the PWR LED on the Taurus PCB is ON, now you can burn the bootloader:

Select the **Arduino Micro** on the "Board:" section.

Now you have two options depending on your Arduino (Programmer Board)

Select the **Arduino as ISP(Atmega32u4)** option on the "Programmer:" section if you have an arduino board based on that MCU (_Such as the_ _ **Micro/Pro Micro** _)

Select the **Arduino as ISP** option on the "Programmer:" section for the other boards based on the Atmega328p(_such as_ _ **Arduino nano** _)

The image below shows an example of a configuration using an Arduino nano.

![](RackMultipart20230721-1-xflpll_html_5ab8d441c87b5053.png)

It will take about 2 minutes, you can see the RX TX LED flashing during this process, don't disconnect until the Arduino IDE says it's done.

Now you can proceed without the Arduino Board and plug your Taurus PCB directly to the USB.

**NOTE** : If it gives an error, check your connection and that the IDE configuration is correct.

## Programming (SimHub)

In this section I'll cover the option of using our code, and in the last section there are the instructions if you want to do it yourself or make some modifications.

To program the Arduino you will need to upload the provided hex(Taurus V2.hex). I use Simhub because it's based on the AVRDUDE software and comes with a simple GUI, but you can use whatever you like.

First open simhub(latest version if possible) and go to the arduino page, then click on the blue button that says "Open arduino setup tool", select your board, serial port and click on the bottom toggle, like in this photo(your port may be different).

![](RackMultipart20230721-1-xflpll_html_8927551c2aba03fe.png)

Then you can press " **ADVANCED**" and select "Upload hex file to arduino", select the provided hex file and press upload.

It will tell you that your upload was successful, otherwise check the error, close anything that might be interfering with the COM port (like the Arduino IDE) and try again.

Now that the programming is complete the buttons should work. We can test these by opening "Game Controllers" from the control panel in windows and selecting "Properties" on the Taurus. On the "Test" tab we can press each of the buttons which should trigger the light to turn red momentarily. Feel free to test all the buttons/features and move to the next step

when comfortable.

## 8. Assembly

| **Items Needed:**
 3D Printed Parts (Enclosure)6X M3 Heat Inserts12x M4 Heat InsertsM4x8 & 16 Socket screws8x M4x10 Countersunk Screws4x M4x18 Brass Standoff 10x M3x10 Countersunk Screws4x M3x10 Button Screws4x M3 Spring Washers4x M3 WashersM3 & M4 Grub Screws for the Knobs |
| --- |

## Rear Shell

![](RackMultipart20230721-1-xflpll_html_6489866d25b0b73e.png)

Insert the M3 heat inserts from the top, taking utmost care that they are flush with the surface.

## Grips ![](RackMultipart20230721-1-xflpll_html_c80542fb6d332019.png)

Do the same with the grips, as shown in the photo (It has to be done on all three front pieces)

They are all M4 and are pretty short, so be sure you get the right ones, you can find the required ones in the BOM.

Once you've finished the grips, I recommend assembling them without the front plate to avoid accidental damage, as it's worth sanding them as smooth as possible with 80-120 grit sandpaper.

TIP: Fit the rear screws now, before you cover the grips with Alcantara. The hole you need to cut to use the Allen wrench will be smaller and less noticeable.

## Front plate

![](RackMultipart20230721-1-xflpll_html_e777e89c59fa90a.png)

Fix the standoffs onto the countersunk screws ( **M4x10 to M4x18 standoff** ) with good force and a dash of threadlocker and wait a few hours before screwing anything to them, otherwise they will turn on themselves. It's important that you make sure these are very secure as they will provide the foundation for the rear plate.

Now you can screw the buttons and the PCB with the help of the encoder nuts.

## Rear Plate

![](RackMultipart20230721-1-xflpll_html_555c2044865a0a4d.png)

Fasten the shifters ( **M3 Washer + M3 Spring Washer + M3x10 Button Screw** ) and the clutches **M3x10 countersunk** screws on the **Rear plate**

**If you are crimping your own cables for the shifters/clutches, 15cm should be sufficient without causing too many issues with excess cable.**

![](RackMultipart20230721-1-xflpll_html_965137106e6e4323.png)

Then join the back plate to the enclosure with **M3x10 countersunk** screws and fix in position the GX12 connector

Be careful not to pinch the clutch cables

## Final touches

Once this is done, we can connect the shifter, clutch and GX12 connector cables to the PCB, then use **M4x10 countersunk** screws to join both parts together. If you are crimping your own cables for the shifters/clutches, 15cm should be sufficient without causing too many issues with excess cable.

Now you can apply the encoder stickers and knobs using the **M4 grub** screws, same will be done with funky knobs ( **M3 grub** )

Finally fix the grips with the socket screws ( **Socket M4x8 and M4x16** ) (if you already inserted the rear M4x16mm Socket screws just cut a little hole with the exacto knife).

![](RackMultipart20230721-1-xflpll_html_d00674c4c82a2268.png) ![](RackMultipart20230721-1-xflpll_html_bcecb0e42d9c289.png)

## 9. Troubleshooting

### As we haven't (yet) had anyone complain or ask for specific help with this build, this section is empty and will be used for future help.

## 10. Extras

## Clutch Calibration

If you happen to use the clutches on your Taurus you will need to calibrate them to your PCB, we have a special guide [**HERE**](https://docs.google.com/document/d/13853OO-jeRLrVNvK7JNsyt2_sdO_zaZc0swEklrDoDA/edit#).

If you bought a PCB with a pair of clutches from us, they will come calibrated.

## CUSTOMIZATION

If you want to do some extra customisation to your Taurus, like different software, different encoders or anything else that requires you to write your own code, here is everything you need to write your own code. ![](RackMultipart20230721-1-xflpll_html_59a75ff520f02bf1.png)

![](RackMultipart20230721-1-xflpll_html_abe84469b70b9924.png)

[1](#sdfootnote1anc)Grips can be printed at 30% infill, but screw and nut holes have to be reinforced by using (in cura) a support blocker in overlap mode with 60% infill, as shown in the photo.

1
