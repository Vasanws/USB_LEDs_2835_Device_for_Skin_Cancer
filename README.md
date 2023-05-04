# USB_LEDs_2835
This is a layout of a USB LEDs with SMD LED component imperial code 2835. 
This is the showcase of the finished layout.  
Version 1:  
![image](https://user-images.githubusercontent.com/65590803/213876217-364791d2-d3b7-464a-af23-6acd757ebaf3.png)

Size of the layout  
Length - 100mm  
Width - 20mm

Circuit layout Version 2  
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

Circuit layout Version 3  
![image](https://user-images.githubusercontent.com/65590803/224206291-dd83e906-76fb-4b8b-b37f-7437919a0ccc.png)
Changelog:  
1. Added two jumper in the layout for touch sensor. 
2. Expend the copper fill between the LEDS. 

Circuit layout Version 4  
![image](https://user-images.githubusercontent.com/65590803/224543723-4ba3fb3a-be8f-4db2-bc5b-2ec5332dd657.png)
Changelog:  
1. Edit LED footprint distance between two pads = 0.61mm. 
2. Route crisscross tracer between LEDs to LED's driver.  
3. Additional tracer for 5V pass through between the LED footprint with tracer size 0.2mm.  
4. Replace R1 footprint from 0402 to 0603.  
  
Schematic diagram of the layout:  
![image](https://user-images.githubusercontent.com/65590803/224089222-8b1b0d83-bec3-474d-9b77-f5e4f085fdd3.png) 

Circuit layout update
Changelog:
1. Added copper fill zone to unconnected footprint of the inverter logic (pin 1). Copper fill zone with settings zone priority level : 1, clearance : 0.2mm, Pad connections : Thermal reliefs, Thermal relief gap : 0.2mm
2. Changed the size of CX1 footprint to 0603 and value to 22uF in schematic diagram.
