# Row-20-Leds
This is a very practical board that I always use, it has different purposes for example: Fast board to test our codes, board output checker and led sequence maker. The board is compatible with Arduino (any arduino board), but you can use it with a breadboard and in this way also able to work with the microcontroller that you prefer or you are familiar with. We are going to build it from scratch to the pcb. From idea to desing.

# MAIN FEAUTURES
- In total 20 digital outpus, which means 20 diodes led, ready to use.
- Common components, very easy to find in our local electronic store.
- Contains a row of male header for the practical conection.
- Compatible with all Arduino board (The same pinout)
- Possible to use in a breadboard and work with other microcontrollers.
- Save a lot of time for making the conections the board is ready.
- Very practical to see the function of your codes.

# SCHEMATIC DIAGRAM
The schematic diagram is very simple and flexible. For example in the case of the resistors you can use values from 220 Ohms until 10k Ohms, if you are planning to make a video with the board, I recommend you to use 10k Ohms value so the led will not shine a lot. In the oposive situation if you want the diode led shines a lot, so use the low value 220 Ohms.
In the case of the diode led 3mm, you can choose different colors (red, blue, yellow, orange or other), the point is that the dimension has to be 3mm, there is no space for diode led 5mm. the pcb is very compact.Also We have the pin headers, the original desing is with male pin header so the pcb will a shield for Arduino or Breadboard, but the option to use cables or female pin header is also welcome and will work efficiently.

# PCB LAYOUT
Before We continue with the PCB layout, it is important to indicate that You can use any software for PCB Desing, believe me there are many options, even if you use the best software it will not mean that you are the best pcb desinger, so in this case We are going to use The Altium Designer highly recommended if you want to enter in the pcb desing world like a professional. So after We finished and check our schematic circuit We need to switch from schematic to PCB layout. We can see the PCB with the Ground Plane, this helps for noise filter on the pcb.

Here after we finish the pcb layout We can get the Gerber files, there are two kind of gerber files we have to pay attention to it, the first GerberX2 and the other Gerber RS274X, most of the manufacturer use the second one Gerber RS274X, in some software we can get both GerberX2 and Gerber (In the case of Altium Designer).

# 3D MODEL
One of the features of Altium Designer is the 3D visualization, the 3d visualization is important and it give us the posibility to see and check our PCB and how it would be in real, also it can show us the components distribution and dimensions. Before I did not consider this feature so important at all, but the 3d visualization can show us if our footprint dimensions are ok, if all the components will be places without touching each other by mistake, it does not matter if your components are SMT or PTH (small or big), it is always better to see that every component will fit correctly.
► Also very important to remember, if you are going to add 3d models, be carefull that you add in the Step AP214 format, the others extensions and formats can not work correctly.

# PDF 3D
According to the software that you are using, You can also get the 3d Models, as I commented you before, this board was desinged On the Altium Designer Software which has this nice option to get the 3d pdf, so later you can share with your coworkers or clients to show the advances of the pcb, without the software installed. After generating the pdf3d, just you need to open with Adobe reader and you will see your 3d board, and also rotate, show or hide layers.

# PCB MANUFACTURE
Once we finished our shield board; it is time to bring it to life. In order to manufacture our board, We are going to use JLCPB Services.In case that you do not have an account yet, check out the bellow link►JLCPCB: https://jlcpcb.com/IAT

** How to Order our PCB in JLCPCB ?
Once We are register, and We logged in our account, We are ready to submit an order and receive our board in a very short time. In this case We need to update first the gerber files, which contains all the necesary information to build the pcb, You can get the gerber files in the link bellow.
