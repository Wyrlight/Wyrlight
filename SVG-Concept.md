
 SVG: Data as Art
Minimalist design is not only visual — it is also about clean, structured data. SVG (Scalable Vector Graphics) plays an important role in Wyrlight’s workflow because it combines aesthetics and mathematics into a single, precise format.

---

 Why SVG?
SVG is not a pixel image. It is a mathematical description that the browser or device draws in real time.
This gives several advantages:
extremely small file sizes
infinite scalability without quality loss
styles and shapes can be edited directly in code
version control stays clean (text, not binary)
For Wyrlight, this means control, precision, and long‑term reliability.

---

 SVG in the Workflow
Every shape begins as a vector.
Even if the final output becomes a PNG or a mockup, the source file is always text‑based geometry, not raster pixels.
This document collects examples, concepts, and workflows that show how Wyrlight uses SVG as:
a visual prototype
a data container
a reusable design component

---

 Technical Example (Plain SVG)
Below is a pure SVG export from Inkscape.
This “Hiking trail marker” concept demonstrates how vector data looks in its raw form.

```xml 
<svg
   version="1.1"
   id="svg1"
   width="745.51569"
   height="833.52539"
   viewBox="0 0 745.51571 833.52542"
   xmlns="http://www.w3.org/2000/svg"
   xmlns:svg="http://www.w3.org/2000/svg">
  <defs
     id="defs1" />
  <g
     id="layer1"
     transform="translate(-314.05074,-258.17187)">
    <path
       id="path"
       style="fill:#000000;fill-rule:evenodd;stroke:#000000;stroke-width:8.00003;stroke-linejoin:round;stroke-miterlimit:1"
       d="m 682.14258,262.17188 c -28.91081,0 -52.18555,23.27472 -52.18555,52.18554 v 74.73438 h 104.37109 v -74.73438 c 0,-28.91082 -23.27472,-52.18555 -52.18554,-52.18554 z M 455.375,413.31641 V 658.44336 H 901.05078 L 1022.9102,536.09375 v -0.42969 L 901.05078,413.31641 Z m 174.58203,269.34961 v 164.63867 c 40.72028,13.27542 81.79048,36.88013 109.3418,68.24609 L 734.32812,682.66602 Z M 553.51367,864.53516 A 235.46286,223.16257 0 0 0 318.05078,1087.6973 H 788.97656 A 235.46286,223.16257 0 0 0 553.51367,864.53516 Z m 337.58008,68.52929 a 164.47179,154.6322 0 0 0 -109.93164,40.04102 235.46286,223.16257 0 0 1 33.66992,114.59183 H 1055.5664 A 164.47179,154.6322 0 0 0 891.09375,933.06445 Z" />
  </g>
</svg>
```
