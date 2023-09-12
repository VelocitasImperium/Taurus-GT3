# **TAURUS GT3**

<img src="https://github.com/VelocitasImperium/Taurus-GT3/blob/main/images/TaurusGt3-GuideFront.png" width="600">

**Copyright by VELOCITAS IMPERIUM - All rights reserved**

**Files are intended only for personal use, not commercial or for resale**


* 1 - [Introduction](#1-introduction)
* 2 - [Safety notes](#2-safety-notes)
* 3 - [BOM and parts](#3-bom-and-parts)
* 4 - [Preparing 3D Printed parts](#4-preparing-3d-printed-parts)
* 5 - [PCB Assembly steps](#5-pcb-assembly-steps)
* 6 - [Clutch/Shifter links](#6-clutchshifter-links)
* 7 - [Flashing and Programming the PCB](#7-flashing-and-programming-the-PCB)
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

The BOM is available [**here**](https://docs.google.com/spreadsheets/d/1FHKVDJvTqiSSPm0fXGAgw0jcgytXlTn-GmOWtaGsIfA/edit?usp=sharing) and you can make your own copy to tick off parts as you go.

It's a good idea to order everything before starting so that you don't miss anything or end up with incorrect parts. The BOM also contains some useful tips on what parts to order and recommendations, _as well as some recommended tools for the job!_ We have intentionally left some flexibility with the parts (eg: switches from either AliExpress or Mouser) so you can make the decision on how much you'd like to spend. In general, the extra money does reflect extra quality but if you think you can get a great deal somewhere else, go for it! That's the benefit of DIY 🙂 \*Velocitas Imperium are not endorsing any of these parts, just making helpful suggestions if you are struggling to source the parts yourself\*

We will now cover some specifics for ordering certain items, such as the **Graphics/Adhesives, Alcantara wrap, Carbon Fiber CNC,** and the **PCB**.

## 3.1 Graphics/Adhesives

The front plate graphics can be made through different methods, depending on your tools, we found the best result is achieved with a combination of adhesive yellow vinyl and printed texts and stickers, cutted with a plotter. You will need to provide the sticker sheet and skin file (found in the Taurus Drive you have access to) to your selected sticker manufacturer and also let them know the dimensions listed below. If you are struggling to find someone to print these for you please message us on discord and we can refer you to a particular seller. Alternatively you can order these through Etsy from us.

_ **Sticker Sheet.PDF** _ _dimensions :225.361 X 116.916 mm_

_ **Taurus V2 GT3 Skin.SVG** _ _dimensions : 192.091 x 140.949 mm_


_ **\*\*\*Encoder Circles** _

_There is an alternative option for the_ _ **Encoder Circles** _ _if you'd prefer a more premium feel and also have less difficulty removing them later, which is having them UV printed on plexiglass. Note that this is just for the encoder circles, and the other smaller stickers and skin still need to be printed with the plotter.Double sided tape is used to adhere them to the wheel. A good supplier for these is_ [_michelle@szgdctech.com_](mailto:michelle@szgdctech.com) _(We also recommend to use Michelle for the Carbon Fibre CNC items, so you may be able to bundle shipping through her)_

## 3.2 Alcantara Wrap

Self-adhesive Alcantara Wrap for the grips is the best option here. Try to avoid getting a cheap material (it will look like cardboard just from looking at the listing photos) as it will be difficult with the small details on the grips. We have had success in the past with "Carbins" brand wrap. **info@carbins.net** can give you more information about buying. They sell by the metre, so the minimum order is 1\*1.42m, which is more than enough to make the grips for this project and have plenty left over for other projects 😌

### Suggested alcantara/suede cutouts :

### Top 4 halves : 25x12cm / 10x5 in

### Bottom 2 halves: 18x9cm / 7x3.5 in

## 3.3 Carbon Fiber/CNC

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

<img src="https://github.com/VelocitasImperium/Taurus-GT3/blob/main/images/Guide/TaurusGt3-guidePcb1.png" width="600">

Enable PCB assembly and leave the default options.

<img src="https://github.com/VelocitasImperium/Taurus-GT3/blob/main/images/Guide/TaurusGt3-guidePcb2.png" width="600">

Press **Confirm** to move to the next page.

**NOTE** : You can leave the default stackup as they already use the JLC7628 as the default, but JLCPCB may change this in the future)

Upload both the BOM and CPL as shown in the photo to this new page.

<img src="https://github.com/VelocitasImperium/Taurus-GT3/blob/main/images/Guide/TaurusGt3-guidePcb3.png" width="600">

After hitting process BOM & CPL you will get into the list of all the components needed for the build, it is all pre-configured by us, so you will need to hit **NEXT**.

Once you have confirmed the parts you will have to select the Product description:

<img src="https://github.com/VelocitasImperium/Taurus-GT3/blob/main/images/Guide/TaurusGt3-guidePcb4.png" width="600">

and you're done, you can finish the order.

### Our advice is to use IOSS Fedex International Priority, you will already have paid the customs fees and there will be no unpleasant surprises at the customs office.

**NOTE** : if some components are out of stock JLCPCB will tell you that a component is missing,this should never happen with our PCB, so contact us by email or Discord.

**NOTE** :It should cost around 110e for two pieces(shipping included), if you get a much lower price check if you have done everything correctly.


## 4. Preparing 3D Printed parts

The following settings are intended for use with a 0.4mm nozzle and wall line count (perimeters) of 4 (printing times with an ender 3)
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


## 4.1 Postprocessing

For a better finish, sanding and painting are suggested, the necessary steps are as follows(for grips only sanding is suggested):

1. Spray filler primer
2. Dry sanding from 200 up to 600 grit
3. Wet sanding from 800 to 1000 grit

**NOTE**: Be careful with power tools on plastic, due to risk of melting.

## 5. PCB Assembly steps
In this part of the guide you will need this items:

<table>
  <tr>
    <th>Items needed:</th>
    <th>Quantity</th>
  </tr>
  <tr>
    <td>PCB</td>
    <td>1</td>
  </tr>
  <tr>
    <td>Alps 7-way switch</td>
    <td>2</td>
  </tr>
  <tr>
    <td>Rotary Encoder</td>
    <td>3</td>
  </tr>
  <tr>
    <td>2-Pin Female 90-Deg Connector</td>
    <td>8</td>
  </tr>
  <tr>
    <td>2 Pin female connector</td>
    <td>2</td>
  </tr>
  <tr>
    <td>3 Pin female connector</td>
    <td>2</td>
  </tr>
  <tr>
    <td>4 Pin female 90-Deg connector</td>
    <td>1</td>
  </tr>
</table>

## 5.1 PCB soldering

Solder the encoders and Alps 7-way switches to the front where the smd components are and the connectors to the other side, and solder the 2x3 pin header on the pcb, it will be needed to flash the PCB then you can desolder it.

<img src="https://github.com/VelocitasImperium/Taurus-GT3/blob/main/images/Guide/TaurusGt3-guidePcbSoldering1.png" width="600">

<img src="https://github.com/VelocitasImperium/Taurus-GT3/blob/main/images/Guide/TaurusGt3-guidePcbSoldering2.png" width="600">

**NOTE:** The PCB may be slightly different, so refer to what is written on the PCB.

TIP: Clean the board after finishing as some types of flux or solder with flux may be corrosive.

## 5.2 12mm connector

In this part we will need this parts:

<table>
  <tr>
    <th>Items needed:</th>
    <th>Quantity</th>
  </tr>
  <tr>
    <td>Coiled USB cable</td>
    <td>1</td>
  </tr>
  <tr>
    <td>12mm connector male/female</td>
    <td>1</td>
  </tr>
  <tr>
    <td>Heatshrink</td>
    <td>Optional</td>
  </tr>
</table>

In this section we're going to suggest that you use our connector pinout, we prefer to have the data lines in the furthest position from each other, also following this pinout will ensure compatibility with our past and future steering wheels.

<hr>

### **NOTE:** You can use your own pinout, just make sure that the USB standard is respected at the end of the USB A connector (you can check this by checking the continuity from the USB A male connector to the one on the PCB). 

<img src="https://github.com/VelocitasImperium/Taurus-GT3/blob/main/images/Guide/TaurusGt3-guideUSB1.png" width="300">

<hr>

Solder the 4 pin wires to the GX12, the side with the notch (on the right) goes out and should be used for reference.

<img src="https://github.com/VelocitasImperium/Taurus-GT3/blob/main/images/Guide/TaurusGt3-guideGx1.png" width="300">
<img src="https://github.com/VelocitasImperium/Taurus-GT3/blob/main/images/Guide/TaurusGt3-guideGx2.png" width="300">
<br>
<img src="https://github.com/VelocitasImperium/Taurus-GT3/blob/main/images/Guide/TaurusGt3-guideGx3.png" width="300">
<img src="https://github.com/VelocitasImperium/Taurus-GT3/blob/main/images/Guide/TaurusGt3-guideGx4.png" width="300">

Using the previous reference it is now time to solder the cable, before you start cutting and soldering make sure the cable is thick enough for the connector, otherwise use heat shrink on the last section to increase the diameter.

Strip off 1cm of the black insulation and 4 to 5mm of the internal wires, then solder the USB cable to the GX12 male connector with the notch facing up, before closing the connector, put some hot glue in the middle of the cables.

**Note** : If the cable has different colors, you'll have to use a tester to make sure to respect the usb pinout

## 5.3 12mm Buttons

Solder a 2-pin cable to each, cable orientation is not important, the use of heat shrink tubing is also recommended, otherwise a dab of glue between the contacts will do.

## 6. Clutch/Shifter Links

<img src="https://github.com/VelocitasImperium/Taurus-GT3/blob/main/images/Guide/TaurusGt3-guideShifter1.png" width="600">

### The one shown in the photo is made by [JLCPCB](https://jlcpcb.com/) in Nylon material (SLS).

You should already have all the parts for these as they are specified in the BOM, however these are actually 2 separate Velocitas Imperium projects so I will link their assembly guides here. They can also be use on any other VI project wheels:

## [Shifter Link](https://www.printables.com/model/372871-magnetic-shifter) & [Clutch Link](https://www.printables.com/model/372151-magnetic-clutch) ![](RackMultipart20230721-1-xflpll_html_97f24a0372db1a77.png)

**Note**: Check that the pin/solder doesn't go beyond the shape of the shifter, as this could cause a short on the backplate (carbon is conductive) and give a false reading between the encoder and the shifter.

## 7. Flashing and Programming the PCB

Before finalizing the assembly we want to make sure the buttons work, so we will start by explaining the process for flashing the bootloader. Unlike some other projects, the Arduino board we had you order in the BOM is simply there to flash the chip on the PCB itself and will be removed later. Before starting these steps it is recommended you remove any other arduino devices you may have plugged into your PC and close any programs that may be using/interfering such as SimHub.

## 7.1 Flashing bootloader - Arduino IDE


Flashing the bootloader is mandatory as they come without one, unlike the regular boards you can buy online.

You will need another Arduino for this process (or you can use whatever tools you like, but they are not covered in this guide, I use another Arduino as it's pretty common to have a spare), atmega328p(nano) or 32u4(micro) based boards are the same, you can follow the official guide on the [**Arduino website**](https://docs.arduino.cc/built-in-examples/arduino-isp/ArduinoISP) or you can read on below, but this is just a summary of the Arduino guide.

You can start by uploading the ISP sketch to your Arduino board as shown in the picture:

<img src="https://github.com/VelocitasImperium/Taurus-GT3/blob/main/images/Guide/TaurusGt3-guideFlash1.png" width="600">

Then you need to connect your Arduino board to the Taurus PCB, you need to connect the 5V, GND, MISO, MOSI, SCK, D10 pin to the corresponding pins on the Taurus PCB, D10 goes to RESET.

You can follow the silkscreen on the Taurus PCB as it's self-explanatory.

**NOTE** : If you are having trouble flashing the bootloader, you may have accidentally connected the RESET pin of your Arduino board to the Taurus PCB, the RESET pin on the Arduino board is not needed in this procedure, you will need to use the D10 pin instead.

<img src="https://github.com/VelocitasImperium/Taurus-GT3/blob/main/images/Guide/TaurusGt3-guideFlash2.png" width="600">

You can use this table to understand which pins are MISO, MOSI and SCK on your Arduino board:

<img src="https://github.com/VelocitasImperium/Taurus-GT3/blob/main/images/Guide/TaurusGt3-guideFlash3.png" width="600">

Note:you can use this table with your Pro micro following the Leonardo pinout, or the UNO if you're using an arduino Nano

Here is an example if you're using a Pro micro as programmer 

<img src="https://github.com/VelocitasImperium/Taurus-GT3/blob/main/images/Guide/TaurusGt3-guideFlash4.png" width="600">

Here is another example if you're using an Arduino nano as programmer

<img src="https://github.com/VelocitasImperium/Taurus-GT3/blob/main/images/Guide/TaurusGt3-guideFlash7.png" width="600">


Once you have completed the wiring you can plug the Arduino board into your PC, if you have done everything correctly you will notice that the PWR LED on the Taurus PCB is ON, now you can burn the bootloader:

Select the **Arduino Micro** on the "Board:" section.

Now you have two options depending on your Arduino (Programmer Board)

Select the **Arduino as ISP(Atmega32u4)** option on the "Programmer:" section if you have an arduino board based on that MCU (Such as the **Micro/Pro Micro**)

Select the **Arduino as ISP** option on the "Programmer:" section for the other boards based on the Atmega328p(such as **Arduino nano** )

The image below shows an example of a configuration using an Arduino nano.

<img src="https://github.com/VelocitasImperium/Taurus-GT3/blob/main/images/Guide/TaurusGt3-guideFlash5.png" width="600">

It will take about 2 minutes, you can see the RX TX LED(on the programmer) flashing during this process, don't disconnect until the Arduino IDE says it's done.

Now you can proceed without the Arduino Board and plug your Taurus PCB directly to the USB.

**NOTE** : If it gives an error, check your connection and that the IDE configuration is correct.

## 7.2 Programming (Simhub)

You can choose to use the already proven (strongly recommended) [**DDC code**] (https://github.com/andreasdahl1987/DahlDesignDDC) by Andreas Dahl.
In this section I'll cover the option of using our code, and in the last section there are the instructions if you want to do it yourself or make some modifications.

To program the Arduino you will need to upload the provided hex(Taurus V2.hex). I use Simhub because it's based on the AVRDUDE software and comes with a simple GUI, but you can use whatever you like.

First open simhub(latest version if possible) and go to the arduino page, then click on the blue button that says "Open arduino setup tool", select your board, serial port and click on the bottom toggle, like in this photo(your port may be different).

<img src="https://github.com/VelocitasImperium/Taurus-GT3/blob/main/images/Guide/TaurusGt3-guideFlash6.png" width="600">

Then you can press " **ADVANCED**" and select "Upload hex file to arduino", select the provided hex file and press upload.

It will tell you that your upload was successful, otherwise check the error, close anything that might be interfering with the COM port (like the Arduino IDE) and try again.

Now that the programming is complete the buttons should work. We can test these by opening "Game Controllers" from the control panel in windows and selecting "Properties" on the Taurus. On the "Test" tab we can press each of the buttons which should trigger the light to turn red momentarily. Feel free to test all the buttons/features and move to the next step when comfortable.

**NOTE: The Windows Game Controller only reads the first 32 inputs of the board, so don't worry if some of the buttons don't show up, you'll need another piece of software to read all the rest.

## 7.2.1 Programming (Arduino IDE)

Here is the other way of flashing the board, the classic way with the Arduino IDE, which we strongly recommend using 
[**DDC code**](https://github.com/andreasdahl1987/DahlDesignDDC).
After setting up the matrix and switches in the sketch, you can upload the code with this configuration:

<img src="https://github.com/VelocitasImperium/Taurus-GT3/blob/main/images/Guide/TaurusGt3-guideFlash8.png" width="600">

## 8. Assembly

In this part we will need this parts:

<table>
  <tr>
    <th>Items needed:</th>
    <th>Quantity</th>
  </tr>
  <tr>
    <td>3D printed parts(enclosure)</td>
    <td>1</td>
  </tr>
  <tr>
    <td>M3 Heat insert</td>
    <td>6</td>
  </tr>
  <tr>
    <td>M4 Heat insert</td>
    <td>12</td>
  </tr>
  <tr>
    <td>M4x8 Socket screws</td>
    <td>6</td>
  </tr>
  <tr>
    <td>M4x16 Socket screws</td>
    <td>6</td>
  </tr>
  <tr>
    <td>M4x10 Countersunk screws</td>
    <td>8</td>
  </tr>
  <tr>
    <td>M4x18 Brass standoff</td>
    <td>8</td>
  </tr>
  <tr>
    <td>M3x10 Countersunk screws</td>
    <td>10</td>
  </tr>
  <tr>
    <td>M3x10 Button screws</td>
    <td>4</td>
  </tr>
  <tr>
    <td>M3 Spring washers</td>
    <td>4</td>
  </tr>
  <tr>
    <td>M3 Washers</td>
    <td>4</td>
  </tr>
</table>

## 8.1 Rear shell

<img src="https://github.com/VelocitasImperium/Taurus-GT3/blob/main/images/Guide/TaurusGt3-guideShell1.png" width="600">

Insert the M3 heat inserts from the top, taking utmost care that they are flush with the surface.

## 8.2 Grips

<img src="https://github.com/VelocitasImperium/Taurus-GT3/blob/main/images/Guide/TaurusGt3-guideGrips1.png" width="200">


Do the same with the grips, as shown in the photo (It has to be done on all three front pieces)

They are all M4 and are pretty short, so be sure you get the right ones, you can find the required ones in the BOM.

**NOTE**: Be very careful when inserting the heat inserts as the process is messy, first clean the holes well and line up the inserts correctly, then clean the threads and make sure it's perfectly straight using the front plate hole, otherwise it will never fit.

Once you've finished the grips, I recommend assembling them without the front plate to avoid accidental damage, as it's worth sanding them as smooth as possible with 80-120 grit sandpaper.

TIP: Fit the rear screws now, before you cover the grips with Alcantara. The hole you need to cut to use the Allen wrench will be smaller and less noticeable.

## 8.3 Front plate

<img src="https://github.com/VelocitasImperium/Taurus-GT3/blob/main/images/Guide/TaurusGt3-guideFrontplate1.png" width="600">

Fix the standoffs onto the countersunk screws ( **M4x10 to M4x18 standoff** ) with good force and a dash of threadlocker and wait a few hours before screwing anything to them, otherwise they will turn on themselves. It's important that you make sure these are very secure as they will provide the foundation for the rear plate.

Now you can screw the buttons and the PCB with the help of the encoder nuts.

## Rear Plate

<img src="https://github.com/VelocitasImperium/Taurus-GT3/blob/main/images/Guide/TaurusGt3-guideRearplate1.png" width="600">

Fasten the shifters ( **M3 Washer + M3 Spring Washer + M3x10 Button Screw** ) and the clutches **M3x10 countersunk** screws on the **Rear plate**

**If you are crimping your own cables for the shifters/clutches, 15cm should be sufficient without causing too many issues with excess cable.**

<img src="https://github.com/VelocitasImperium/Taurus-GT3/blob/main/images/Guide/TaurusGt3-guideRearplate2.png" width="600">

Then join the back plate to the enclosure with **M3x10 countersunk** screws and fix in position the GX12 connector

Be careful not to pinch the clutch cables

## 8.4 Final touches

Once this is done, we can connect the shifter, clutch and GX12 connector cables to the PCB, then use **M4x10 countersunk** screws to join both parts together. If you are crimping your own cables for the shifters/clutches, 15cm should be sufficient without causing too many issues with excess cable.

Now you can apply the encoder stickers and knobs using the **M4 grub** screws, same will be done with funky knobs ( **M3 grub** )

Finally fix the grips with the socket screws ( **Socket M4x8 and M4x16** ) (if you already inserted the rear M4x16mm Socket screws just cut a little hole with the exacto knife).

<img src="https://github.com/VelocitasImperium/Taurus-GT3/blob/main/images/Guide/TaurusGt3-guideFinal1.png" width="300">
<img src="https://github.com/VelocitasImperium/Taurus-GT3/blob/main/images/Guide/TaurusGt3-guideFinal2.png" width="250">

## 9. Troubleshooting

One problem we had with one of the builds was that the shifters were shorting out to the rear plate, creating ghost contacts on the PCB. Insulate the pins or cut them shorter.

## 10. Extras

## CUSTOMIZATION

If you want to do some extra customisation to your Taurus, like different software, different encoders or anything else that requires you to write your own code, here is everything you need to write your own code.

<img src="https://github.com/VelocitasImperium/Taurus-GT3/blob/main/images/Guide/TaurusGt3-guideCode1.png" width="600">
<img src="https://github.com/VelocitasImperium/Taurus-GT3/blob/main/images/Guide/TaurusGt3-guideCode2.png" width="600">
