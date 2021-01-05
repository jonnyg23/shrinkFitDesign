# shrinkFitDesign
**University of New Mexico - Mechanical Engineering  
Design V Capstone Project**

This Jupyter Notebook finds the optimal dimensions and materials to use for a ring-plug residual stress assembly.

### Goal:
* Create a residual stress ring-plug assembly that exhibits at/or above the ring's yielding stress, radially, from the interface to the outer radius of the ring. The appropriate dimensions of the ring-plug assembly must be determined to achieve the desired goal with the maximum assembly clearance (ideal clearance is >= 0.0015 radial inches).

### Requirements:
* At least half of the thickness of the ring must exhibit yielding.
Maximum O.D. of the ring is 6 inches to use photolithography for etching coordinates at every 90 degrees.
The plug must have an equal or greater yield strength than the ring to ensure ring yields before/or during the yielding of the plug.

### Solution:
* Use a vectorized implementation of the Lame's Equation with Von Mises Stress Theory of Failure to find the Top 10 designs. These designs will meet the project requirements using a few metallic materials that have very different material properties.

## UPDATE--IT WAS A SUCCESS!!:
* The Capstone Project Goal was successfully fulfilled and presented at the annual UNM ME Design V presentation.
* The final design was a homogeneous assembly of 304L Stainless Steel, this was one of the least expensive options which resulted in optimal ring yielding. This design can be seen as the 16th choice from the algorithm in the jupyter notebook.

**For information on theory:** Refer to the Proof of Concept Document in the corresponding GitHub Repository.

### Details
* Python 3.6 was used in the jupyter notebook. 

### Team Members:
* Hassan Alqahtani
* Joseph Na
* Janghan Park
* Zachary Sanchez
* Jonathan Sanchez
* Rachel Starkweather
* Timothy Santos
* Mychal Taylor
