# USB LED Device for Skin Cancer  

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
