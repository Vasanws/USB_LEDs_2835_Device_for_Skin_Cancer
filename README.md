# USB LED Device for Skin Cancer  
In this project will show how to made Printed Circuit Board (PCB) for USB LED for Skin Cancer done from software design to transferring onto copper board as a prototype.

# How does USB LED for Skin Cancer works?  
The LEDs light wavelength was chosen specifically by the power of the light intensity it emits. A special cream applys on the affected area of the human skin and once the speical cream expose by the LEDs light, the special cream enter the skin and destroys the cancer cells.  

# How to do it?  
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

Before proceed to to transfer the circuit layout on the board, the copper board surface requires to be clean from oxidation and surface debris. To do that, use sandpaper and sand the copper board surface until the surface turns into a shining copper colour. Once it is done, rinse the copper board with tap water apply soap and scrub with a sponge to ensure left no dirt on the copper board surface. The picture below shows before and after of the copper board surface. 

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

Then, place the board either front or back of the laminated machine depending on the model features and feed it into the laminated machine with the maximum temperature around 200 degree celcius to 220 degree celcius repeatedly. Lowest count is 35 counts of feed. This is because the laminated machine is moving at a moderate rolling speed so it require to feed it multiple counts. To make it a single count, the motor of the laminated machine requires to me modify to the slowest rolling speed.

Set laminated machine temperature to maximum as shown below:

![image](https://github.com/Vasanws/USB_LEDs_2835_Device_for_Skin_Cancer/assets/65590803/0f698eb9-ae72-4fb7-a9c3-d6531fe26f5b)

Here is an example of a trial without the aluminium foil. In this example uses a smaller scale of a singular board as the method shares the same. 

![image](https://github.com/Vasanws/USB_LEDs_2835_Device_for_Skin_Cancer/assets/65590803/5101d9c0-f6d8-4d68-badb-7a2c30a4f37e)

After multiple counts the copper board being feed into the laminated machine, move the copper board away from the laminated machine and cool the copper board. After the copper board is cool off, place the copper board into a container of tap water and let the gloss paper become soft and safely to peal off for about 10 minutes to 15 minutes. To indicate when will the gloss paper to be peal off, look at the contrast of the circuit layout once it become clear to see that indicate the gloss paper can be peal off.

Before:

![image](https://github.com/Vasanws/USB_LEDs_2835_Device_for_Skin_Cancer/assets/65590803/c509b5ed-bfb3-421b-8a69-c3d225a74303)

After:

![image](https://github.com/Vasanws/USB_LEDs_2835_Device_for_Skin_Cancer/assets/65590803/f7ae62d7-e8ca-46ea-a1fa-cf2ecc14337b)




















 
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
