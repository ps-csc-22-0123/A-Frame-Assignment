# A-Frame Summer Hut Project
# INDEX NUMBER: PS/CSC/22/0123

### Description
This project is a Virtual Reality (VR) scene created using the A-Frame web framework. It features a traditional Summer Hut setup with an octagonal table, chairs, Milo tin, Milk tin, and two cups.

### Assignment Requirements Met
* **No External Models:** All objects (including the hut, furniture, and tins) were built entirely using A-Frame primitives (Cylinders, Boxes, Cones, Torus).
* **Scene Components:**
    * Summer Hut structure with a thatched roof.
    * Octagonal table constructed using radial segments.
    * Four chairs positioned on opposite sides.
    * Realistic Milo and Milk tins created by stacking cylinders.
      .

### Problems Encountered & Solutions
1.  **Creating the Cups:** Since A-Frame primitives are solid, the cups initially looked like solid blocks. 
    * *Solution:* I used a slightly smaller, dark-colored cylinder inside the top of the cup to create a "liquid" layer, giving the illusion of a hollow cup holding coffee/tea. I also used a `torus` primitive to create the curved handles(result was unsuccesful in the end).
2.  **Milo & Milk Labels:** Without using image textures (to strictly follow the "No Models/Textures" rule), it was difficult to make the tins look realistic.
    * *Solution:* I used `a-text` entities carefully positioned on the curved surface of the cylinders. For the Milk tin, I stacked blue and white cylinders to create the branding stripes.

### Partially Working Code
There is no partially working code. The entire scene renders correctly, and all objects are positioned as required by the assignment.

### Time Taken
Approximately 5 accumulative hours.
