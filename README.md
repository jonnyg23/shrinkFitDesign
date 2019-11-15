# shrinkFitDesign
This Jupyter Notebook finds the optimal dimensions and materials to use for a ring-plug residual stress assembly.

**Goal:**
Create a residual stress ring-plug assembly that exhibits at/or above the ring's yielding stress, radially, from the interface to the outer radius of the ring. The appropriate dimensions of the ring-plug assembly must be determined to achieve the desired goal with the maximum assembly clearance (ideal clearance is >= 0.0015 radial inches).

**Requirements:**
At least half of the thickness of the ring must exhibit yielding.
Maximum O.D. of the ring is 6 inches to use photolithography for etching coordinates at every 90 degrees.
The plug must have an equal or greater yield strength than the ring to ensure ring yields before/or during the yielding of the plug.

**Solution:**
Use a vectorized implementation of the Lame's Equation with Von Mises Stress Theory of Failure to find the Top 10 designs. These designs will meet the project requirements using a few materials that have very different material properties.

**For information on theory:** Refer to the Proof of Concept Document in the corresponding GitHub Repository.

**Details**
* Python 3.6 was used in the jupyter notebook. 
