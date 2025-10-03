# PiicoDev-FritzingParts

This repository contains **custom Fritzing parts for PiicoDev modules** from Core Electronics. It also contains the PiicoDev expansion board and build platform for Raspberry Pi Pico (micro:bit and Raspberry Pi to come). I am not a graphics designer nor an electrical engineer, and am not affiliated with Core Electronics, although I am a big fan of their products. I am creating these primarily to use the parts to generate graphical representations of circuits incorporating PiicoDev products, making it easier for beginning students to create and follow circuit diagrams. It is not my intention to create files that could be used to make PCBs.

## How to install

### Option 1. Install the parts in the "My Parts" bin

- Download the parts that you want from the **parts** folder. Each *.fzpz* file contains everything needed to create circuit diagrams. 
- Open Fritzing.
- If you don't see the **Parts** window on the right side of the Fritzing interface, go to the **Window** drop down menu and check that **Parts** is ticked.
- With the **My Parts** bin selected, go to the dropdown menu in the upper right and select **Import...**
- Navigate to the folder where you downloaded the parts and select an individual *.fzpz* file. 
- The part will now be available in your **My Parts** bin.
- Repeat this for each part that you wish to use.

### Option 2. Install the parts in a custom bin

If you want all PiicoDev parts grouped together in their own bin:

- Open Fritzing.
- Within the **Parts** window on the right side of the Fritzing interface, go to the dropdown menu and select **New Bin...**
- Name the bin (e.g. ***PiicoDev***) and click on **OK**.
- Follow the instructions as above, but do it from within your custom bin.

If you want to include a Core Electronics icon to identify the PiicoDev bin in Fritzing, you will need to download and save the **CoreElectronicsSymbol.png** (or create your own custom symbol) to the same folder that contains the custom bin, then edit the custom ***.fzb*** file (e.g. ***PiicoDev.fzb***) by opening it in a text editor. On the first line, replace ***Custom1.png*** with ***core-electronics-symbol.png*** or whatever image file you wish to use.

This repository does not contain a Fritzing part for the Raspberry Pi Pico. 

For:

- Raspberry Pi Pico  and Raspberry Pi Pico W - Go to this this Fritzing Forum conversation ([Looking for Raspberry Pi PICO part - #49 by vanepp - parts help - fritzing forum](https://forum.fritzing.org/t/looking-for-raspberry-pi-pico-part/11915/49)).
- Raspberry Pi Pico 2W -  Go to this Fritzing Forum conversation ([Looking for Raspberry Pi PICO part - #7 by vanepp - parts help - fritzing forum](https://forum.fritzing.org/t/raspberry-pi-pico-2w/27192/7)).
