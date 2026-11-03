# A8 – Gears

## Objective

For this assignment, I was tasked with designing a gearbox that could be assembled and disassembled. I was given the gear ratio, output torque and speed, and the diameters and lengths of the input and output shafts. I first had to check if the shafts were strong enough and design journal bearings to support them. After completing the calculations, I moved onto SolidWorks to create the gearbox housing and assemble all the components.

![Gear Figure](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/raw/0fa355c0a0e4485f83de19c8f3e1238828404075/docs/assignments/A08/GearFigure_1.png)

## Analyze

### Design of the Shafts

The first thing I did was determine if the input and output shaft diameters were sufficient. I listed my knowns and unknowns, drew my free-body diagrams, and used the equations from Machinery's Handbook to calculate the maximum shear stress for each shaft. Due to issues with getting a physical copy I had to ask for equations via a classmate.

### Input Shaft (Power-Transmission)

![Inout Shaft](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/raw/0fa355c0a0e4485f83de19c8f3e1238828404075/docs/assignments/A08/InputShaft_2.png)

The calculated maximum shear stress was approximately 1222.3 psi. This was below the allowable stress of 4000 psi, so the input shaft diameter of 0.125 inches was sufficient.

### Output Shaft (Short Shaft)

![Output Shaft](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/raw/0fa355c0a0e4485f83de19c8f3e1238828404075/docs/assignments/A08/OutputShaft_3.png)

The calculated maximum shear stress was approximately 407.1 psi. This was below the allowable stress of 8500 psi, so the output shaft diameter of 0.25 inches was sufficient.

## Design of the Journal Bearings

![Journal Bearing 1](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/raw/0fa355c0a0e4485f83de19c8f3e1238828404075/docs/assignments/A08/JournalBearingPt1_4.png)

After checking the shafts, I moved onto designing the journal bearings. I needed to determine the pressure, surface velocity, and PV rating for each bearing. These calculations helped me decide what material would work best for the application.

## Output Shaft Bearing

![Journal Bearing 2](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/raw/0fa355c0a0e4485f83de19c8f3e1238828404075/docs/assignments/A08/JournalBearingPt2_4.png)


The calculated pressure was approximately 36.4 psi, the surface velocity was approximately 72 ft/min, and the PV value was approximately 2620.4 psi·ft/min.

## Input Shaft Bearing

The calculated pressure was approximately 87.35 psi, the surface velocity was approximately 95.99 ft/min, and the PV value was approximately 8385.3 psi·ft/min. This was the maximum PV value used when selecting the bearing material.

## Journal Bearing Thickness

![Journal Bearing Thickness](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/raw/0fa355c0a0e4485f83de19c8f3e1238828404075/docs/assignments/A08/journalBearingThickness_6.png)

After calculating the PV values, I used the material loading capacity to determine the required thickness of each journal bearing.


## Gearbox Housing Sketch

![Skecth](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/raw/0fa355c0a0e4485f83de19c8f3e1238828404075/docs/assignments/A08/GearSketch_7.png)

Before creating the CAD model, I made a sketch of the gearbox housing and decided to use nuts and bolts to connect the two halves together. This would allow the gearbox to be assembled and disassembled.


## Decide

For the shafts, I kept the original diameters of 0.125 inches for the input shaft and 0.25 inches for the output shaft because the calculated stresses were below the allowable values I used.

For the journal bearings, I selected graphite dry based on its PV rating and loading capacity from the material table. I then used the calculated dimensions to model the bearings. The exact McMaster-Carr bearing component should match the selected material, shaft diameter, bearing length, and required clearance.

For the housing, I used two separate halves connected with nuts and bolts so the gearbox could be assembled and disassembled. I also needed to make sure there was enough clearance around the gears and bearings.

## Communicate

## Parametric CAD Modeling

I started the SolidWorks modeling process by entering the known parameters and equations into the equation editor. I created the shafts and journal bearings first, downloaded the gears from McMaster-Carr, and then modeled the gearbox housing.

<!-- Image 16: SolidWorks equation editor and parameters -->

<!-- Image 17: Input shaft CAD model -->


<!-- Image 18: Output shaft CAD model -->


<!-- Image 19: Journal bearing CAD models -->


<!-- Image 20: Gearbox housing first half -->


<!-- Image 21: Gearbox housing second half -->


<!-- Image 22: Gearbox housing assembled -->


## Final Assembly

After creating the individual parts, I brought everything into a SolidWorks assembly. One issue I had was getting the gears to mesh correctly, so I needed to improve the gear positioning and assembly constraints to make sure the gears worked together properly.

## Engineering Drawings – MEGR 2157

The drawing portion of this assignment requires six individual multiview drawings and one complete assembly drawing. The drawings should use third-angle projection, the required tolerance block, and appropriate tolerancing for critical features.

## Input Shaft Drawing

![InputShaft](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/raw/b68bf448d0cc1e3fcb52bdd3dfaf139b0cf0a4a9/docs/assignments/A08/InputShaftDRW.png)

## Housing Half 1 Drawing

![Top](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/raw/b68bf448d0cc1e3fcb52bdd3dfaf139b0cf0a4a9/docs/assignments/A08/TopBoxDRW.png)


## Housing Half 2 Drawing

![Bottom](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/raw/b68bf448d0cc1e3fcb52bdd3dfaf139b0cf0a4a9/docs/assignments/A08/BottomBoxDRW.png)


## Input Shaft Bearing Drawing

![InputBearing](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/raw/b68bf448d0cc1e3fcb52bdd3dfaf139b0cf0a4a9/docs/assignments/A08/InputBearingDRW.png)


## Output Shaft Bearing Drawing

![OutputBearing](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/raw/b68bf448d0cc1e3fcb52bdd3dfaf139b0cf0a4a9/docs/assignments/A08/OutputBearingDRW.png)


## Complete Assembly

![GearBox](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/raw/b68bf448d0cc1e3fcb52bdd3dfaf139b0cf0a4a9/docs/assignments/A08/FullGearBox.png)

## CAD Files

The SolidWorks part files, assembly, and other necessary CAD files are available below.

![CAD Zip](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/raw/b68bf448d0cc1e3fcb52bdd3dfaf139b0cf0a4a9/docs/assignments/A08/A8%20Gears.zip)

## Lessons Learned

This assignment helped me understand how to check shaft strength, calculate journal bearing pressure and velocity, and use PV ratings to select a bearing material. I also learned more about using parameters in SolidWorks and how important it is to check that all the components fit together correctly.

One issue I ran into was getting the gears to mesh correctly in the assembly. This showed me that making the individual parts is only one part of the process, since the components also need to fit and work together properly. Another thing I learned was that starting earlier would have made the modeling process less stressful, especially because some of the SolidWorks assembly steps were new to me.

This assignment took me about 7-8 hours to complete.
