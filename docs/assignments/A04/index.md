# Assignment 4: Motor Mount

For this assignment, I was instructed to design a motor mount for a Brushed 24V DC Gear Motor with a 99.5:1 planetary gearbox. The mount has two main features. Feature 1 is the part that connects directly to the motor, while Feature 2 is the part that connects the mount to the rigid wall. For both features, I had to design around the yield strength of the material and also make sure the maximum deflection stayed below 0.30 mm at the free end.

![image alt](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/blob/62bd40eac1042e997b12ba6b5766387ac3a66b71/docs/assignments/A04/SS_1.jpg)

For my design, I chose to use Acrylonitrile Butadiene Styrene (ABS). I used a Young's Modulus of 1.79 GPa and a yield strength of 30 MPa for my calculations. A safety factor of 3 was also used, and the weight of the motor was neglected. To simplify the analysis, I treated both features as cantilever beams since the wall connection was assumed to have zero deflection and zero slope.

![image alt](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/blob/1ed98cf1e2f561ccd1bd46b890264422d6674e69/docs/assignments/A04/SS_2.jpg)

The first feature is the part of the mount that connects to the motor. I decided to use a rectangular cross section because it makes the calculations and CAD model simpler. Instead of using the same dimensions as the example, I chose a width of 42 mm and an initial beam length of 20 mm.

## Knowns and Unknowns

### Knowns

- Applied force: $P = 300\text{ N}$
- Beam length: $L = 20\text{ mm}$
- Beam width: $b = 42\text{ mm}$
- Young's Modulus: $E = 1790\text{ N/mm}^2$
- Yield strength: $\sigma_y = 30\text{ MPa}$
- Safety factor: $N = 3$
- Maximum deflection: $\delta_{max} = 0.30\text{ mm}$

### Unknowns

- Bending moment, $M$
- Required height from stress, $h_\sigma$
- Required height from deflection, $h_\delta$
- Final cross-sectional height, $h$

## FBD

For the free body diagram, I modeled Feature 1 as a cantilever beam fixed at the wall. The 300 N force is applied at the free end of the feature. The fixed end contains a reaction force and reaction moment.

![image alt](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/blob/20b3585e121eefba31f2bf84debc4dc610c6aa69/docs/assignments/A04/SS_3.jpg)

After that I solved for the height requirements of the feature using the stress and deflection equations. They simply needed to be rearranged to sole for height which allowed me to use all of my known values. My height calculated from deflection turned out to be higher than expected which lead me to use just stick with that height. After calculating the height of this feature ws 14.12 mm.

![image alt](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/blob/81a17e152c4897a2e1d3530881c267e205e6f2a1/docs/assignments/A04/SS_4.jpg)

# Feature 2

The second feature is the part of the mount that attaches to the rigid wall. The wall is assumed to be strong enough to support the bolts. I used the same ABS material and safety factor from Feature 1.

For this feature, I used a width of 42 mm and a beam length of 112 mm. This length was selected based on the motor and the distance needed for the motor to sit away from the wall. 

## Knowns and Unknowns

### Knowns

- Applied force: $P = 300\text{ N}$
- Beam length: $L = 112\text{ mm}$
- Beam width: $b = 42\text{ mm}$
- Young's Modulus: $E = 1790\text{ N/mm}^2$
- Yield strength: $\sigma_y = 30\text{ MPa}$
- Safety factor: $N = 3$
- Maximum deflection: $\delta_{max} = 0.30\text{ mm}$

### Unknowns

- Bending moment, $M$
- Required height from stress, $h_\sigma$
- Required height from deflection, $h_\delta$
- Final cross-sectional height, $h$

## FBD

I modeled Feature 2 as another cantilever beam. The wall acts as the fixed support and the 300 N force acts at the free end. The length of this feature was calculated by rounding to 90 and subtracting the length of feature 1 from that value which totaled out to  a length of 75.88 mm which would allow the full height of both features to be 90mm once connected. The moment calulations for this faeature was found to be 33600 N*mm.

![image alt](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/blob/0f980e2fe0b8341158ba76c51d30d9773dece96b/docs/assignments/A04/SS_5.jpg)

After that I did the same rearranged formula technique to begin calculating the additonal measurements of this feature. The same thing happened with the deflection formula providing  a larger height, which again led me to use the calculated value assuring there isn't anything that could exceed the deflection maximum. The height was found to be 41.68 mm.

![image alt](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/blob/f90424d400b1a8d7a2ce5866752bed73da73563b/docs/assignments/A04/SS_6.jpg)

#Isometric Sketch

Before starting my CAD file I had to design a simple handdrawn mount that would carry over to SolidWorks easier. All dimensions of each feature are also provided. This design was inspired by another design with my calculation being different.

![image alt](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/blob/44d7f4bebd8140a59e659b63bfca0d06b58a3b16/docs/assignments/A04/SS%2B7.jpg)

# Parametric CAD Model

After finishing the calculations and sketch, I moved into SolidWorks to create the 3D model. I started by entering my main dimensions into the equation editor so that the important dimensions could be changed without having to completely rebuild the model.

## Global Variables

The main values I used in SolidWorks were:

- `Force = 300 N`
- `Width = 42 mm`
- `Feature1_Length = 20 mm`
- `Feature1_Height = 10 mm`
- `Feature2_Length = 112 mm`
- `Feature2_Height = 43 mm`
- `Bolt_Clearance = 3.4 mm`
- `Material = ABS`

**[Insert SolidWorks equation editor screenshot here]**

I then created the side profile of the motor mount and extruded it to create the basic shape.

**[Insert CAD side profile screenshot here]**

## Motor Mount Holes

The next step was creating the holes that connect the motor to Feature 1. I used the dimensions of the motor to locate the center hole and the four mounting holes.

The motor shaft clearance hole was modeled based on the motor dimensions, while the four mounting holes were made using 3.4 mm clearance holes for the M3 bolts as required by the assignment.

**[Insert motor hole sketch screenshot here]**

## Wall Mounting Holes

After creating the motor mounting holes, I added the holes for attaching the mount to the wall. I used construction geometry to evenly space the four 3.4 mm clearance holes across the wall mounting feature.

This allowed the bolts to be distributed evenly instead of having the holes placed randomly on the feature.

**[Insert wall bolt hole screenshot here]**

# Deflection Reduction Features

After creating the basic motor mount, I added support features between the two main sections of the mount. These supports help reduce bending and deflection by adding material between Feature 1 and Feature 2.

I decided to use triangular gusset-style supports because they are simple to model and add support without completely changing the main shape of the mount.

**[Insert gusset/support screenshot here]**

The supports were also placed symmetrically so that the load would be distributed more evenly across the mount.

# Final CAD Model

After adding the mounting holes and support features, the motor mount was completed in SolidWorks. The final model uses ABS and contains the motor mounting holes, wall mounting holes, and additional supports to help reduce deflection.

**[Insert final CAD model screenshot here]**

# Lessons Learned

This assignment helped me understand how beam stress and deflection equations can be used to determine dimensions for an actual mechanical part. I also learned that the stress requirement and deflection requirement do not always give the same answer. For my design, stress controlled Feature 1 while deflection controlled Feature 2.

I also learned more about using global variables and equations in SolidWorks. Instead of manually changing every dimension, I was able to connect the important dimensions to my calculations. This makes the design easier to change if one of the requirements changes.

Another thing I learned was that adding material in certain areas can help reduce deflection without needing to completely redesign the mount. The gusset supports were added for this reason.

Overall, this assignment gave me more experience taking calculations and turning them into an actual CAD model. The project took approximately 4-5 hours from the initial calculations to the completed CAD model.

# CAD File

**[Insert link to download Motor Mount SLDPRT file here]**

