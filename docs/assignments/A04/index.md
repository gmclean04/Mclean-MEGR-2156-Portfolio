# Feature 1: Motor Mount Attachment

The first feature is the part of the mount that connects to the motor. I decided to use a rectangular cross section because it makes the calculations and CAD model simpler. Instead of using the same dimensions as the example, I chose a width of 42 mm and an initial beam length of 20 mm.

## Knowns and Unknowns

### Knowns

- Applied force: **P = 300 N**
- Beam length: **L = 20 mm**
- Beam width: **b = 42 mm**
- Young's Modulus: **E = 1790 N/mm²**
- Yield strength: **σ_y = 30 MPa**
- Safety factor: **N = 3**
- Maximum deflection: **δ_max = 0.30 mm**

### Unknowns

- Bending moment, **M**
- Required height from stress, **h_σ**
- Required height from deflection, **h_δ**
- Final cross-sectional height, **h**

## FBD

For the free body diagram, I modeled Feature 1 as a cantilever beam fixed at the wall. The 300 N force is applied at the free end of the feature. The fixed end contains a reaction force and reaction moment.

![Feature 1 Free Body Diagram](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/raw/20b3585e121eefba31f2bf84debc4dc610c6aa69/docs/assignments/A04/SS_3.jpg)

After that I solved for the height requirements of the feature using the stress and deflection equations. They simply needed to be rearranged to solve for height which allowed me to use all of my known values. My height calculated from deflection turned out to be higher than expected which led me to stick with that height. After calculating, the height of this feature was 14.12 mm.

![Feature 1 Calculation Sheet](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/raw/81a17e152c4897a2e1d3530881c267e205e6f2a1/docs/assignments/A04/SS_4.jpg)

# Feature 2

The second feature is the part of the mount that attaches to the rigid wall. The wall is assumed to be strong enough to support the bolts. I used the same ABS material and safety factor from Feature 1.

For this feature, I used a width of 42 mm and a beam length of 112 mm. This length was selected based on the motor and the distance needed for the motor to sit away from the wall.

## Knowns and Unknowns

### Knowns

- Applied force: **P = 300 N**
- Beam length: **L = 112 mm**
- Beam width: **b = 42 mm**
- Young's Modulus: **E = 1790 N/mm²**
- Yield strength: **σ_y = 30 MPa**
- Safety factor: **N = 3**
- Maximum deflection: **δ_max = 0.30 mm**

### Unknowns

- Bending moment, **M**
- Required height from stress, **h_σ**
- Required height from deflection, **h_δ**
- Final cross-sectional height, **h**

## FBD

I modeled Feature 2 as another cantilever beam. The wall acts as the fixed support and the 300 N force acts at the free end. The length of this feature was calculated by rounding to 90 and subtracting the length of feature 1 from that value which totaled out to a length of 75.88 mm which would allow the full height of both features to be 90 mm once connected. The moment calculations for this feature was found to be 33,600 N·mm.

![Feature 2 Free Body Diagram](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/raw/0f980e2fe0b8341158ba76c51d30d9773dece96b/docs/assignments/A04/SS_5.jpg)

After that I did the same rearranged formula technique to begin calculating the additional measurements of this feature. The same thing happened with the deflection formula providing a larger height, which again led me to use the calculated value assuring there isn't anything that could exceed the deflection maximum. The height was found to be 41.68 mm.

![Feature 2 Calculation Sheet](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/raw/f90424d400b1a8d7a2ce5866752bed73da73563b/docs/assignments/A04/SS_6.jpg)



