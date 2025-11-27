# Custom Macropad  
![Project Image](/documentation/pcb.pdf)  
 
## 🚀 Overview  
This project is a custom macropad featuring a 4x3 keyboard, 1 rotary encoders.  

## 📂 Repository Structure  
```
📁 PCB/   # KiCad PCB and schematic files
📁 docs/  # PDFs, images, and additional documentation
📁SILK/ # Logos
```
How I Built My Macropad

I designed this macropad by following a mix of online tutorials and Hack Club Blueprint resources. I first watched a few PCB design tutorials to understand how keyboard matrices, diodes, switches, and microcontrollers work together. Using those as a base, I modified the designs to match my needs — including customizing the number of keys, the layout, and the placement of the microcontroller.

- My Process

1. Research & Tutorials
I watched tutorials on KiCad basics, PCB routing, switch footprints, diode direction, and USB power protection. These helped me understand the standard keyboard wiring patterns.

2. Creating the Schematic
I made the key matrix using rows, columns, and diodes. I connected everything to the microcontroller pins according to the firmware requirements.

3. Designing the PCB Layout
Using the tutorials as reference, I arranged the switches, added stabilizing holes, routed traces, and made sure the USB and microcontroller connections followed good design practices.

4. Modifying for My Needs
I changed the layout spacing, optimized the routing, and adapted the components to the specific features I wanted in my macropad.
This included switching some pin assignments, adjusting diode placement, and improving the routing flow.

5. Final Checks
I ran ERC/DRC checks, compared my layout against multiple tutorial examples, and manually verified diode orientation and USB connections.

- Challenges I Faced

1. Learning proper keyboard matrix wiring and diode direction

2. Understanding how to route clean traces without crossing

3. Figuring out microcontroller pin assignments

4. Managing the spacing between switches

5. Ensuring USB and power connections were correct

Plans Ahead

I will start the 3D model design on December 15th

- I will then generate STL files, export renders, and add them to the README

![Schematic Dia](/documentation/schematic.pdf)

### BOM
![BOM](/PCB/BOM.csv)
![Screenshot](/documentation/image.png)
Cost:- https://www.digikey.in/short/rrz541t3
Spent around 6 hours around designing the pcb!

NOTE TO THE REVIEWER:
1. I have my exams upcoming so there might be a delay in designing and uploading the 3d model
2. Requesting to check the pcb connections 
3. I live in India and many parts are either not available or overpriced, it would br better if the blueprint team ship the components and pcb. No funding required them.
4. Pls do initiate tickets as I need to buy tools for the hackpad.
5. Just verify the PCB files...

Thank you,
Shlok vaidya