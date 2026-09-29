# A6 – Parametric Bracket Design and Drawing

## Objective

For this assignment, I had to parametrically design the bracket that I made in the previous assignment and then create a Multiview drawing in CAD. The bracket was designed to slide over a T Beam and hold 650 lbf. The material is Nylon, with a maximum deflection of 0.005 in and a safety factor of 4. All of the calculations and assumptions for the dimensions were completed in the previous assignment.

## Analyze

For the parametric design, I decided to use measurements from both the stiffness and stress designs. Whenever I had different dimensions from the two designs, I used the bigger value so that the dimension would work with both analyses.

I started by entering my knowns, assumptions, and equations into the SolidWorks equation editor. I also had to account for the fit between the bracket and the T Beam. Since the bracket needed to smoothly slide over the T Beam and strict accuracy was not required, I decided to use an RC7 fit. The RC7 fit is intended for free-running fits where accuracy is not essential.

I added the minimum clearance from the fit to my original dimensions in the parametric table. This allowed the dimensions to be controlled by the parameters instead of manually changing each dimension.

![Multiview Sketch](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/raw/4f1fcd69a5e1b811d8607c33546fbcd03c49b02b/docs/assignments/A06/A6_1.jpg)

Once the parameters were set, I started creating the model. I made the different sections of the bracket in order from Parts A-E.
![Part A](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/raw/4f1fcd69a5e1b811d8607c33546fbcd03c49b02b/docs/assignments/A06/A6_4.jpg)

![Part B](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/raw/4f1fcd69a5e1b811d8607c33546fbcd03c49b02b/docs/assignments/A06/A6_5.jpg)

![Part C](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/raw/4f1fcd69a5e1b811d8607c33546fbcd03c49b02b/docs/assignments/A06/A6_6.jpg)

![Part D](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/raw/4f1fcd69a5e1b811d8607c33546fbcd03c49b02b/docs/assignments/A06/A6_7.jpg)

![Part E](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/raw/4f1fcd69a5e1b811d8607c33546fbcd03c49b02b/docs/assignments/A06/A6_8.jpg)

I also used the equation editor to combine some of the side measurements into one dimension. This helped make the model more organized and allowed the dimension to update with the other parameters.

![Equation Editor](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/raw/4f1fcd69a5e1b811d8607c33546fbcd03c49b02b/docs/assignments/A06/A6_2.jpg)

## Decide

I decided to use the larger dimensions from the stiffness and stress designs because this allowed the bracket to meet the requirements from both analyses. I also decided to use the RC7 fit for the T Beam because the bracket needs to slide over the beam rather than have a very tight fit.

For the drawing, I decided to use a third-angle projection and include the dimensions needed to describe the bracket. I also added tolerances to the gap where the T Beam fits because this is one of the main functional areas of the part.

I added a section view because it makes the inside of the bracket easier to see and shows where the T Beam will be located. I also added a centerline to show the center axis of Part A, which is the feature that will hold the applied force.

![RC7 Thing](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/raw/4f1fcd69a5e1b811d8607c33546fbcd03c49b02b/docs/assignments/A06/A6_3.jpg)

## Communicate

After finishing the CAD model, I created the Multiview engineering drawing. I used third-angle projection and added the required dimensions and tolerances. I also included the tolerance block and the tolerances for the T Beam interface.

![Drawing](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/raw/d747af69ea199a76cd60db06eb3dd82ae21050c2/docs/assignments/A06/A6_10.jpg)

The section view helps show the inside of the bracket while still displaying the important dimensions. The centerline shows the center axis of the part and helps communicate the location of the feature that carries the force.

This assignment took about 2-3 hours to complete. I learned how to take dimensions from my stress and stiffness calculations and use them in a parametric CAD model and Multiview drawing. I also learned that it is important to double check calculations before putting them into a CAD model because an incorrect dimension can affect the rest of the design. Using parametric modeling made it easier to fix these types of errors because the related dimensions could update with the change. I also learned more about using standard fits such as RC7.

## Download CAD Files

[Download Solidworks CAD file](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/raw/c5acb5e1f0bca9fd9595dfa0ffd406518632d836/docs/assignments/A06/A6_GEM.SLDPRT)

[Download Solidworks Drawing file](https://github.com/gmclean04/Mclean-MEGR-2156-Portfolio/raw/c5acb5e1f0bca9fd9595dfa0ffd406518632d836/docs/assignments/A06/A6_GEM.SLDDRW)


