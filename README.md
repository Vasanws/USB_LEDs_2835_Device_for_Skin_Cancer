# USB LED Device for Skin Cancer  
In this project will show how to made Printed Circuit Board (PCB) for USB LED for Skin Cancer done from software design to transferring onto copper board as a prototype.

# How does USB LED for Skin Cancer works?  
The LEDs light wavelength was chosen specifically by the power of the light intensity it emits. A special cream applys on the affected area of the human skin and once the speical cream expose by the LEDs light, the special cream enter the skin and destroys the cancer cells.  

# How to do it as Prototype?  
There are many methods out there on creating PCB, for the best result is by using heat method with high temperature around 220 degree celcius. The tools can be use are iron or laminated machine (heavy duty). For this project, using laminated machine is one of the best tool to produce consistency in tranferring the circuit onto a copper board.  

# Step 1: Tools and Materials requires
Tools 
- Laminated Machine (heavy duty).
- Cutting mat.
- Cutting knife.
- Overhead projector or torchlight.
- Laser printer.
- Milling machine (drill)
- Gloves.
- Eye protection.
- Etching tray.
- Container for water.
- Container or beaker for PCB tinning.
- Hotplate.
- Kicad 6.
- Inkscape.
- Multimeter.
- Sanding machine.

Materials
- Semi-gloss paper 230gsm or lower gms.
- Etching Solution (Ferric Chloride).
- Thiourea (12.5 grams).
- Tartaric acid (8.8 grams).
- Tin(II) Chloride (1.3 grams). 
- tap water (250ml).
- Acetone.
- Sandpaper.
- Tipped marker pen.
- Aluminium foil.
- Copper board.
- Sponge.
- Soap

# Step 2: Making circuit board design 
In Kicad 6 software is where to design the circuit layout as shown below.
![image](https://github.com/Vasanws/USB_LEDs_2835_Device_for_Skin_Cancer/assets/65590803/506123ea-0bc3-49b8-97a5-fcb4dbbe8ba5) 

# Step 3: Toner Tranfer 
In this step will show the method how to toner transfer the circuit layout from the software onto a physical board. Firstly, printout the circuit layout onto semi gloss paper. For better result, ensure that the ink are darker black after printout and stick on the semi gloss paper and no extras ink act of debris that interfere the layout's connections. If the printout is not good, clean the roller in the printer to remove ink debris or check if enough ink. To printout duplicate circuit layout in a single paper, use Inkscape to duplicate the circuit layout as shown below:

![image](https://github.com/Vasanws/USB_LEDs_2835_Device_for_Skin_Cancer/assets/65590803/8c0275ac-150f-4261-b313-6431896c0b54)  

Before proceed to to transfer the circuit layout on the board, the copper board surface requires to be clean from oxidation and surface debris. To do that, use sandpaper and sand the copper board surface until the surface turns into a shining copper colour. Once it is done, rinse the copper board with tap water apply soap and scrub with a sponge to ensure left no dirt on the copper board surface. Finally, apply acetone on the copper board surface and wipe with cloth or tissue. The picture below shows before and after of the copper board surface. 

Before:

![image](https://github.com/Vasanws/USB_LEDs_2835_Device_for_Skin_Cancer/assets/65590803/3cda587d-1e96-4261-bc12-8dd3d214c3f9) 

After: 

![image](https://github.com/Vasanws/USB_LEDs_2835_Device_for_Skin_Cancer/assets/65590803/6140548e-d04f-4ea8-bdf2-b1b89bf230cf)

Then, place the printed circuit layout on the surface of the copper board. Make sure that the printed circuit layout ink directly touch the copper board surface as shown below.

Before:

![image](https://github.com/Vasanws/USB_LEDs_2835_Device_for_Skin_Cancer/assets/65590803/720d04c2-7f01-4566-885d-ac956dd5da95)

After:

![image](https://github.com/Vasanws/USB_LEDs_2835_Device_for_Skin_Cancer/assets/65590803/59210e29-2cdd-4b8e-a4ca-ca68ea7f4c29)

Place the aluminium foil on the surface where the printout cricuit layout gloss paper is. After few try and error, this way allows the heat transfer across the board evenly for aa large scale printout circuit layout and also for smaller singular printout circuit layout.

![image](https://github.com/Vasanws/USB_LEDs_2835_Device_for_Skin_Cancer/assets/65590803/5254c2e4-b9a5-4bd4-98bc-ea46052f413f)

Then, place the board either front or back of the laminated machine depending on the model features and feed it into the laminated machine with the maximum temperature around 200 degree celcius to 220 degree celcius repeatedly. Lowest count is 35 counts of feed. This is because the laminated machine is moving at a moderate rolling speed so it require to feed it multiple counts. To make it a single count, the motor of the laminated machine requires to be modify to the slowest rolling speed. Ensure that wear gloves to avoid skin burn during the handling.

Set laminated machine temperature to maximum as shown below:

![image](https://github.com/Vasanws/USB_LEDs_2835_Device_for_Skin_Cancer/assets/65590803/0f698eb9-ae72-4fb7-a9c3-d6531fe26f5b)

Here is an example of a trial without the aluminium foil. In this example uses a smaller scale of a singular board as the method shares the same. 

![image](https://github.com/Vasanws/USB_LEDs_2835_Device_for_Skin_Cancer/assets/65590803/5101d9c0-f6d8-4d68-badb-7a2c30a4f37e)

After multiple counts the copper board being feed into the laminated machine, move the copper board away from the laminated machine and cool the copper board. After the copper board is cool off, place the copper board into a container of tap water and let the gloss paper become soft and soggy and safely to peal off for about 10 minutes to 15 minutes. To indicate when will the gloss paper to be peal off, look at the contrast of the circuit layout once it become clear to see through and the gloss paper is soggy that indicates the gloss paper can be peal off and the ink will not be remove from the copper board.

Before:

![image](https://github.com/Vasanws/USB_LEDs_2835_Device_for_Skin_Cancer/assets/65590803/c509b5ed-bfb3-421b-8a69-c3d225a74303)

After:

![image](https://github.com/Vasanws/USB_LEDs_2835_Device_for_Skin_Cancer/assets/65590803/f7ae62d7-e8ca-46ea-a1fa-cf2ecc14337b)

Once the circuit layout can be seen under the water, peal the paper off the from the board.

![image](https://github.com/Vasanws/USB_LEDs_2835_Device_for_Skin_Cancer/assets/65590803/cbdae3b7-fc49-42a6-b24b-c77ee1fb6727)

As the picture above, the toner transfer is not perfect nor close to perfect as some of the tracers or component footprint did not stick on the copper board. This shows that the heat transfer across the board does not reach the same level of heat during the laminating process.

Now with the aluminium foil cover the copper board and repeat the same process here is the result. Do some inspection after the pealing the gloss paper, if there is excessive paper stuck in between the circuit layout or blocking the drilling holes, use wet cloth and gentle scrap off the excessive paper that stuck on the copper board. This will later during the etching process will be easy to etch. Tested where if the excessive paper does not remove, the board will not etch properly and may excessive etching will remove the ink.

![image](https://github.com/Vasanws/USB_LEDs_2835_Device_for_Skin_Cancer/assets/65590803/8600b43e-492b-4653-8db6-5347a09e5cd2)

Laslty, use a tipped marker pen or permanent marker pen to do some touch up if some of the ink does not stick on the copper board. For example highlighting tracks or empty space or component footprints.

In conclusion for Step 3, to reduce extra work from redo if the toner transfer fail, do the following:
- Clean the copper board surface with sandpaper and wash with soap and scrub with sponge.
- Cover the copper board with aluminium foil once the printed circuit layout is place on the copper board.
- During the laminating process, ensure that the copper board go through at least 40 counts consistently.
- Once done, cool the copper board and place the copper board into a container of tap water to soften the gloss paper.
- Once the printed circuit layout can be see through from the gloss paper, slowly peal the gloss paper.
- Clear away any excessive paper on the board.
- Double check if there is any missing ink on the circuit layout and touch up with a tipped marker pen.

# Step 4: Etching
Before etching, recommend to cut the copper board which contains the circuit layout only to reduce waste of copper board and easier for etching for each circuit layout. Use PCB Cutter or PCB Shear or ready cut the size of the copper board of the desire size before implementing Step 3 Toner Transfer.

Steps to do etching:
- Place the copper board into an etching tray.
- Pour an amount Ferric Chloride into the etching tray.
- Tilt the etching tray left and right or vice versa to let the acid reaction active.
- Do this for about 10 to 15 minutes or lesser depending on how strong the acid reaction is.
- Check the copper board time to time whether it is completely etch off the expose copper.
- Use glove or plactic clamp to remove the board once it is done and leaving it for too long may remove the ink protected area.
- Wash the board with tap water to remove the remaining acid on the board's surface.

![image](https://github.com/Vasanws/USB_LEDs_2835_Device_for_Skin_Cancer/assets/65590803/747549d4-1165-4aee-bda7-a814f5a912c5)

![image](https://github.com/Vasanws/USB_LEDs_2835_Device_for_Skin_Cancer/assets/65590803/709bfbde-e074-4352-8ea8-6e4824e1a1a2)

Once the etching is done, use acetone with cloth or tissue to remove the ink.

![image](https://github.com/Vasanws/USB_LEDs_2835_Device_for_Skin_Cancer/assets/65590803/cacd0e18-ccc4-4d45-8e57-4c98807bb40b)

Use multimeter to check each connectivity whether there any copper being etch away. This is to ensure that the board does not have any defects or fixable and reuseable before solder the components on the board. May use lights to place under the board to check the overall copper trace. For example, the board is being place under a overhead projector:

![image](https://github.com/Vasanws/USB_LEDs_2835_Device_for_Skin_Cancer/assets/65590803/cef63fd4-f2d7-434a-996c-4df37fdb5b90)

This way gives a clear view to troubleshoot the copper trace. This method only works for single-sided layout.

# Step 5: Drilling the Holes
For this step, may use a Milling Drill machine or Hand Drill. In this project for the drilling uses Milling Drill machine for better drilling accuracy by hand. Drill all the board's holes.

![image](https://github.com/Vasanws/USB_LEDs_2835_Device_for_Skin_Cancer/assets/65590803/59098fce-08d2-4dd1-b628-290a7aebb61a)

# Step 6: Board Shaping
In this step is more towards on shaping the board following the circuit layout design. In this project the shaping done by using a sanding machine.

Before:

![image](https://github.com/Vasanws/USB_LEDs_2835_Device_for_Skin_Cancer/assets/65590803/b966e9e9-6f10-453b-8c4c-61264302326b)

After:

![image](https://github.com/Vasanws/USB_LEDs_2835_Device_for_Skin_Cancer/assets/65590803/f2fb7ed8-32fa-4746-a577-c73bde80dec2)

# Step 7: PCB Tinning
Why is PCB tinning is needed? PCB tinning protects the expose copper from being oxidation and corrosion. Tinning will prolong the copper tracers to remain in good shape and functionality in its conductivity. Without tinning, the oxidation in the copper can results in difficulties in soldering.

How to create DIY tinning?
- Get a beaker or plastic container.
- Fill in 250ml of tap water.
- Heat the water using hotplate 100 degree celcius.
- Mix the chemical as following: Thiourea = 12.5 grams, Tartaric acid = 8.8 grams, Tin(II) Chloride = 1.3 grams.
- Stir the following chemicals while heating up on the hotplate.
- To know whether the chemical is ready, visual change can be seen when the liquid turns cloudy and if the liquid surface have bubbles, remove from the hotplate.
- Dip the board into the liquid and once the copper is tinned, do the next side of the board.

![image](https://github.com/Vasanws/USB_LEDs_2835_Device_for_Skin_Cancer/assets/65590803/2a314bd3-258e-4543-862f-67de2fee5015)

![image](https://github.com/Vasanws/USB_LEDs_2835_Device_for_Skin_Cancer/assets/65590803/6b6429fc-5feb-4f19-93f8-9cc91295d40a)

Comparison between tinning copper trace and non tinning copper trace.

![image](https://github.com/Vasanws/USB_LEDs_2835_Device_for_Skin_Cancer/assets/65590803/4e315e6f-ce3a-4b9f-a2d4-5016812a6153)

Finishing of tinning copper trace.

![image](https://github.com/Vasanws/USB_LEDs_2835_Device_for_Skin_Cancer/assets/65590803/21cf6752-ba1e-4563-adda-77d1dfdb20e8)


---------------------------------------------------------------------------------------------------------------------
# CHANGELOG OF THE PROTOTYPE TO FINAL CIRCUIT LAYOUT
This is a layout of a USB LEDs with SMD LED component imperial code 2835. 
This is the showcase of the finished layout.  
PCB layout version 1    
![image](https://user-images.githubusercontent.com/65590803/213876217-364791d2-d3b7-464a-af23-6acd757ebaf3.png)

Size of the layout  
Length - 100mm  
Width - 20mm

PCB layout update version 2  
![image](https://user-images.githubusercontent.com/65590803/218314217-64a25081-7922-4ba2-9541-ce352652c7e1.png) 
Changelog: 
1. Added from 28 LEDs to 32 LEDs. 
2. Reposition all LEDs from diagonal positions to horizontal positions.  
3. Moves the components more outwards nearby the edge cut to make room for the LEDs spacing.  
4. Reposition U3 to the right side of the layout. 
5. Reposition other components from diagonal positions to vertical and horizontal positions.  
6. Reduce the radius Front Courtyard for both mounting hole to 0.4mm radius.  
7. The copper filler for the LED connections are set to, Pad connections: Thermal reliefs, Thermal relief gap: 0.2mm, Thermal spoke width: 0.8mm. 
8. All resistor and capacitor have been changed from 0603 to 0402 except Rx1 from 0603 to 1206. 

PCB layout update version 3  
![image](https://user-images.githubusercontent.com/65590803/224206291-dd83e906-76fb-4b8b-b37f-7437919a0ccc.png)
Changelog:  
1. Added two jumper in the layout for touch sensor. 
2. Expend the copper fill between the LEDS. 

PCB layout update version 4  
![image](https://user-images.githubusercontent.com/65590803/224543723-4ba3fb3a-be8f-4db2-bc5b-2ec5332dd657.png)
Changelog:  
1. Edit LED footprint distance between two pads = 0.61mm. 
2. Route crisscross tracer between LEDs to LED's driver.  
3. Additional tracer for 5V pass through between the LED footprint with tracer size 0.2mm.  
4. Replace R1 footprint from 0402 to 0603.  
  
Schematic diagram layout 1      
![image](https://user-images.githubusercontent.com/65590803/224089222-8b1b0d83-bec3-474d-9b77-f5e4f085fdd3.png) 

Circuit layout update   
![image](https://user-images.githubusercontent.com/65590803/236684982-30c755cc-171f-4d77-81c6-281ffcaf84ba.png)     
Changelog:
1. Added copper fill zone to unconnected footprint of the inverter logic U3 (pin 1). Copper fill zone with settings zone priority level : 1, clearance : 0.2mm, Pad connections : Thermal reliefs, Thermal relief gap : 0.2mm
2. Changed the size of CX1 footprint to 0603 and value to 22uF in schematic diagram.
    
PCB layout update version 5    
![image](https://user-images.githubusercontent.com/65590803/236684770-02f4bac5-2452-4966-8312-da291a6a2222.png)   
Changelog:    
1. Custom made footprint SOD-323 for D33 based on the measurement of this model https://www.vishay.com/docs/85751/1n4148ws.pdf    
2. Rearrange the components to be closer and allow some spaces for larger components.   
3. Added copper fill 5V to fill in the empty spaces on the left side of the board.    
4. Retrace the track of the connection for cleaner connection.    
    
Schematic diagran layout 2    
![image](https://github.com/Vasanws/USB_LEDs_2835/assets/65590803/b9ab0257-a2d5-496a-b80c-b55690f03c37)
Changelog:    
1. Added TVS diode conneted to C2.    
    
PCB layout update version 6   
![image](https://github.com/Vasanws/USB_LEDs_2835/assets/65590803/0fdf83da-06e0-4e15-a9d7-156b1a00d7a2)
![image](https://github.com/Vasanws/USB_LEDs_2835/assets/65590803/db07e2b0-2dda-4b8c-9f12-3698f3201148)   
Changelog:    
1. Image 1 modified the testpoint hole with overlapping square pad for soldering.   
2. Image 2 modified L1 according to the specification WHC 0630 https://offer-product.oss-cn-beijing.aliyuncs.com/product/offer/attachment/2140865164/file/subPdf_4274_10144_20210414-212909770.pdf with some adjustment length : 7.7mm, pads size y-axis : 3.5mm.    
3. Remove front solder mask at the right side of the board with together with the L1 to expand soldering of larger or smaller inductor component and expose empty area for power wires.   

PCB layout update version 7   
Changelog:    
1. Update mounting hole size from 2mm to 2.2mm.
2. Slightly move D35 closer to right side mounting hole with distance between each other 0.3mm.   
3. Fix Electrical Rules Error in schemactic symbols by creating and saving custom symbols in project.   

PCB layout update version 8   
![image](https://github.com/Vasanws/USB_LEDs_2835/assets/65590803/385d42d9-322b-485c-99c2-d98c96e6ac0c)   
![image](https://github.com/Vasanws/USB_LEDs_2835/assets/65590803/605b4928-05ca-402f-9e11-93183553d102)   
Changelog:    
1. Cleanup copper fill to make the workspace clean.   
2. Custom resistor footprint for Rx1 combine metrics (1206/0805).

PCB layout update verion 9  
Changelog:  
1. Change R6 resistor value to 990 ohm.
2. Change C5 capacitor value to 33nF.

PCB Paneling  
PCB paneling for fabrication.  
![image](https://github.com/Vasanws/USB_LEDs_2835/assets/65590803/3d24ba3c-cc41-40ca-be24-2986cb22168c)  

Final fabrication  
![image](https://github.com/Vasanws/USB_LEDs_2835/assets/65590803/160613fc-3327-4610-a461-c28c6da2120a)  

-------------------------------------------------------------------------------------------------------------   
How to install Kikit in Kicad6 ?    
1. Open Kicad 6.0   
2. At the menu of Kicad 6.0, search **"Plugin and Content Manager"** under **tools** or can be seen from the right of the menu or **Ctrl + M**.   
3. Select **Plugins** Tab and search for **KiKit** and click install. Select **Libraies** tab and search for **KiKit Library** and click install.   
4. Click Apply Changes to proceed installation.   
5. Open pcbnew and under **Tools** search **External Plugins** and click refresh plugins.   
6. If plugins didn't shown, open **Kicad 6 Command Prompt**.    
7. In Command Prompt, enter **pip install kikit**.    
8. Once done, open pcbnew and refresh plugins.    
Installation guide can be found here: https://pypi.org/project/KiKit/

-------------------------------------------------------------------------------------------------------------
# REFERENCES
- Home-made mixture for chemical PCB tinning (acid bath) - https://robertgawron.blogspot.com/2016/04/galvanic-pcb-tinning-by-using-home-made.html
- Make Homemade PCB Tinning solution ("Liquid Tin") - https://www.reddit.com/r/electronics/comments/77tcpb/make_homemade_pcb_tinning_solution_liquid_tin/
- How to Make Double Sided Circuit Boards at Home - https://www.youtube.com/watch?v=au2ba5gWLWk

