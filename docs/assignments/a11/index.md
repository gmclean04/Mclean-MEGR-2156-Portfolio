# A11 – Motor Selection

## Objective
For this assignment this is a continuation of our work on the leadscrew design from A10. This week we  were in charge of selecting, calculating, and adding a motor to the tester as well as designing a frame and a floating bearing. In this assignment we will be required to utilize an FEA analysis to ensure the frame can hold. As this assignment progresses the bill of materials and labor cost will be presented as well as our process for this assignment.

Team composed of George Mclean Jr, Eva Stewart, Isabella Alzamora

<img width="891" height="948" alt="13final assembly-1" src="https://github.com/user-attachments/assets/1430945f-173c-47e3-abbd-f77c22410de7" />

## Analyze
### Motor Selection and Attachment: George Mclean Jr

For this part of the assignment, I was responsible for selecting a motor based on the torque and speed requirements calculated in the previous assignment. Our leadscrews required a maximum torque of 8.76 lbf·in, which converts to 140.16 ozf·in. The required RPM range was 4.5–226.5. After looking through the available options on McMaster-Carr, I decided on the NEMA 23 Stepper Motor  with a Square Motor Body (6627T271)  (https://www.mcmaster.com/6627T271). This motor has a maximum holding torque of 205 ozf·in and a maximum rotational speed of 750 RPM. It also operates at 24V DC with a maximum current of 2.8 A per phase. We decided to use the parallel wiring configuration because, as shown in the torque-speed curve below, it allows the motor to operate within the continuous operating range discussed in class.

<img width="997" height="475" alt="MotorandAttachment" src="https://github.com/user-attachments/assets/ee93780e-f7c6-45ca-ad7c-ae67a747d6d6" />
<img width="2536" height="1324" alt="MotorSelected" src="https://github.com/user-attachments/assets/9c362b79-cfc3-45ed-a2e0-a2e7fb56e790" />
<img width="752" height="573" alt="MotorDiagram" src="https://github.com/user-attachments/assets/744e43dd-5558-4c6d-88bf-04b8699380d1" />
<img width="749" height="568" alt="Torque-Speed Chart" src="https://github.com/user-attachments/assets/3a490218-e419-4e8f-9176-2bb896ee0262" />


With the motor selected, the next step was to design a mounting bracket that would allow it to securely attach to the tensile tester. To start, I listed all of the knowns and unknowns that would be needed for the design. I also decided to use the same material as the leadscrews, which was 1018 Carbon Steel. After doing some research ( https://www.amardeepsteel.com/blog/sae-1018-steel-composition-properties.html ), I found that the modulus of elasticity for this material was 205 GPa, which converts to 29,700 ksi. Using the motor's dimensions as my known values, I created an initial sketch of what I wanted the bracket to look like. One thing to note is that after creating the design in CAD, I decided to change the bracket dimensions from 4 in × 4 in to 4 in × 3 in. This adjustment allowed the frame to fit over the bracket properly later in the design process.

<img width="992" height="782" alt="DesignMotorMount" src="https://github.com/user-attachments/assets/56613862-cca2-44e2-a06d-0f253ee5fdc9" />
(After more consideration I decided to make a simpler design via Solidworks)


Using one of the deflection equations from Machinery's Handbook, I was able to calculate the minimum thickness needed for the bracket to be 0.20 in. As shown below, I first rearranged the equation algebraically to solve for thickness before plugging in my known values. After making the dimension changes in SolidWorks, I found that the new minimum thickness was actually 0.17 in. I decided to keep the original design calculation and move forward with a slightly thicker bracket. In the end, I settled on a thickness of 0.30 in to give the design some additional support and a larger safety margin. This process helped reinforce the importance of parametric design and how changing one dimension can affect other parts of the design.

<img width="997" height="612" alt="ModelEqn" src="https://github.com/user-attachments/assets/4ad5eb90-3b86-4a3a-bc27-46f01498de20" />


After completing the calculations, I added my equations and values to the SolidWorks equation editor and began creating the model. I started by sketching and extruding the square plate, then added the holes for the motor and the bolts used to attach the bracket to the frame. During this process, I realized that the original motor mount was too wide for the frame it needed to sit on. To fix this, I went back into my parametric equations and adjusted the dimensions accordingly. Once the changes were made, the bracket fit properly on top of the frame, allowing us to move forward with the rest of the design.

<img width="1106" height="646" alt="GlobalEqns" src="https://github.com/user-attachments/assets/8999fdea-0ef6-4c91-a0a5-3136699403da" />
<img width="1496" height="920" alt="BeginningModel" src="https://github.com/user-attachments/assets/db5a8381-21d3-4efa-9caf-3c0fe875b9e3" />
<img width="645" height="592" alt="FinalBracket" src="https://github.com/user-attachments/assets/c036a7df-7a52-4ed1-8305-8c92cdb77ca9" />




After finishing the motor mount bracket, I moved on to designing and selecting the coupler that would connect the motor to the leadscrew. I started by listing all of my knowns and unknowns and drawing the necessary free-body diagrams (FBDs). From there, I used shear stress in torsion analysis to determine the required inner and outer diameters of the coupler.
Using the torsion equations, I first rearranged the equation algebraically to solve for the required thickness before plugging in my values. After completing the calculations, I found that the required thickness was 0.7046 in and the outer diameter was 1.0795 in. Based on these results, I decided to go with the Servomotor Precision Flexible Shaft Coupling from McMaster-Carr. This coupler has a 3/8 in by 1/2 in shaft bore and an outer diameter of 1-1/16 in ( https://www.mcmaster.com/6854N105/ ). I chose this option because its outer diameter was very close to my calculated value, and the 3/8 in bore was suitable for connecting to the leadscrew. After comparing the selected coupler to my calculations, I determined that it would be able to handle the applied torque.

<img width="746" height="817" alt="CouplerSelection" src="https://github.com/user-attachments/assets/63c2558f-7f6b-44e2-abce-f84cf61d887a" />
<img width="1912" height="995" alt="Coupler (1)" src="https://github.com/user-attachments/assets/e8b19e53-bc1f-44b1-b754-a8a47fce9683" />



## Decide
_Reference your concept selection (Pugh matrix) here. How does this design follow from that decision?_

## Communicate
