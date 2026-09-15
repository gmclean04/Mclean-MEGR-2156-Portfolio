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

I modeled Feature 2 as another cantilever beam. The wall acts as the fixed support and the 300 N force acts at the free end.

**[Insert Feature 2 FBD here]**

## Moment Calculation

