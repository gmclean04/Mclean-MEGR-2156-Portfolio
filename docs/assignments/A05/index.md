# A5 – Bracket Design


## Objective

For this assignment, I had to design a bracket that could smoothly slide over a rigid T beam while holding a horizontal force from a strap. The bracket needed to be designed with a safety factor of 4 and an applied load between 500 lbf and 800 lbf.

![Bracket Reference](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/blob/172d8cd18a1eeb09fdfa45074e4052ced35b4237/docs/assignments/A05/A5_1.jpg)

For my design, I decided to use **ASTM A36 Steel** ( https://beamdimensions.com/materials/Steel/ASTM/ASTM_A36/ ) . I used a design load of **650 lbf** so the bracket would be designed somewhere in the middle of the required load range. I used stress and deflection analysis to determine the dimensions of the different features.

The maximum allowed deflection for the stiffness analysis was **0.005 in**. I also assumed that the bracket would not fail from direct shear stress, as stated in the assignment.

![Bracket Mockup](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/blob/172d8cd18a1eeb09fdfa45074e4052ced35b4237/docs/assignments/A05/A5_0.jpg)

## Analyze

I started by breaking the bracket into five different features and analyzing each one separately. For each feature, I found the known values, unknowns, assumptions, free body diagram, algebraic solution, and numerical solution.

For the stress analysis, I used a safety factor of 4 and worked through the features starting with Feature A. The reaction forces from one feature were then used as the loading for the next feature. This made it possible to work through the bracket instead of trying to analyze the entire part at once.

![Feature A and B](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/blob/172d8cd18a1eeb09fdfa45074e4052ced35b4237/docs/assignments/A05/A5_2.jpg)

For the strap section, I used the strap width of **0.75 in** and gave the feature some additional room instead of making the opening exactly the same size as the strap. I used the dimensions of the rigid T beam as reference dimensions for some of the other features.

![Feature C through E](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/blob/172d8cd18a1eeb09fdfa45074e4052ced35b4237/docs/assignments/A05/A5_3.jpg)

After finishing the stress analysis, I went back through the same five features for the stiffness analysis. This time I used the maximum deflection of **0.005 in** and the appropriate beam deflection equations for each feature. Shear deflection was assumed to be negligible.

The main thing I noticed during this part was that the equation changed depending on the type of feature being analyzed. Some features acted more like cantilever beams, while others could be treated as axial or simply supported members.

![Stiffness Feature A through C](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/blob/172d8cd18a1eeb09fdfa45074e4052ced35b4237/docs/assignments/A05/A5_4.jpg)

![Feature D to E](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/blob/172d8cd18a1eeb09fdfa45074e4052ced35b4237/docs/assignments/A05/A5_5.jpg)

## Decide

I decided to use **ASTM A36 Steel** for the bracket because it gave me a relatively high yield strength while also having a much higher Young's modulus than the Nylon used in the reference example.

My main design values were:

- Applied load: **650 lbf**
- Safety factor: **4**
- Maximum deflection: **0.005 in**
- Material: **ASTM A36 Steel**
- Young's modulus: **29,000,000 psi**
- Yield strength: **36,000 psi**
- Strap width: **0.75 in**

After completing both analyses, I compared the dimensions from the stress calculations with the dimensions from the stiffness calculations. The larger required dimension was used for the final CAD model so that the feature would satisfy both requirements.

I also used the dimensions of the T beam when deciding the final fit and clearances. The goal was to have the bracket slide over the beam without making the fit unnecessarily loose.

![Sketches](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/blob/172d8cd18a1eeb09fdfa45074e4052ced35b4237/docs/assignments/A05/A5_6.jpg)

## Communicate

After completing the calculations, I created the bracket in CAD using the dimensions from the stress and stiffness analyses. I also created separate multiview sketches showing the dimensions from each analysis.

The sketches include an isometric view along with the top, side, and front views. The purpose of these drawings was to show where the calculated dimensions were being used in the final bracket.

I also included the FBDs and calculations for each feature so the design process can be followed from the original load all the way to the final CAD model.


### Lessons Learned

This assignment helped me understand more about how stress and stiffness affect the design of an actual part. The biggest thing I learned was that the dimensions cannot just be based on whether the material will break. The amount that the part deflects can also control the design.

Another thing I noticed was how the force from one feature becomes the force used for the next feature. Because of this, an incorrect calculation early in the process could affect the dimensions of the features later in the bracket.

I also got more practice deciding which equation to use based on how the feature was loaded. This was harder than some of the previous assignments because there were several different types of loading involved.

Overall, the assignment took several hours because I had to go back and forth between the stress calculations, stiffness calculations, sketches, and CAD model. It gave me a better idea of how the calculations actually connect to the physical design.

I also got more practice deciding which equation to use based on how the feature was loaded. This was harder than some of the previous assignments because there were several different types of loading involved.

Overall, the assignment took several hours because I had to go back and forth between the stress calculations, stiffness calculations, sketches, and CAD model. It gave me a better idea of how the calculations actually connect to the physical design.
