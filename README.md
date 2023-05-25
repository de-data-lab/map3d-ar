# map3d-ar
Mapping application in 3D.
<br />
<br />

## Live Demo
View the live demo of [3D map of intersections and crashes](https://de-data-lab.github.io/map3d-ar/build-html/map_traffic.html)
<br />
<br />

## Overview
This application maps point data as 3D towers with variable height, positioned across the state of Delaware.

   Each tower represents a cluster of data points, and the height of the tower corresponds to the number of points.  
   In a typical 2D map with clustering, the greater the number of points within an area, the larger the circle,  
   but in this map, the greater the number of points, the taller the tower.  

In this map, there are two datasets:
* Roadway intersections data in Delaware as of August 2021 - from the DE Open Data Portal (<https://opendata.firstmap.delaware.gov/datasets/delaware::delaware-intersections-2-0/explore>)
* Vehicular crashes data within 2022 - from the DE Open Data Portal (<https://data.delaware.gov/Transportation/Public-Crash-Data/827n-m6xc>)

Either, both, or neither of these datasets can be toggled on and off using the tool panel at the right edge of the screen.
Just click the '>' arrow on the right edge of the screen, and the tool panel will slide out.
<br />
<br />

## Under the Hood
This project harnesses the power of various libraries, including:
* Mapbox GL JS (v2.9.1)
  * Read the docs [here](https://docs.mapbox.com/mapbox-gl-js/guides/)
* Mapbox GL Directions (v4.1.1)
  * Source code [here](https://github.com/mapbox/mapbox-gl-directions)
  * Read the docs [here](https://docs.mapbox.com/help/glossary/directions-api/)
* Mapbox Polyline (v1.1.1)
* Turf.js
  * Read the docs [here](https://turfjs.org/docs/)
* Three.js (r126)
  * Official website [here](https://threejs.org/)
  * Source code [here](https://github.com/mrdoob/three.js/)
* Threebox (v2.2.7)
  * Source code (forked from original repository) [here](https://github.com/jscastro76/threebox)
  * Original repository, now read-only [here](https://github.com/peterqliu/threebox)

For information about the licenses of these softwares, see the section below.
<br />
<br />

## Licensing

### Mapbox GL JS
Copyright © 2021 - 2023 Mapbox, Inc.  
All rights reserved.

The software and files in this repository (collectively, "Software") are
licensed under the Mapbox TOS for use only with the relevant Mapbox product(s)
listed at www.mapbox.com/pricing. This license allows developers with a
current active Mapbox account to use and modify the authorized portions of the
Software as needed for use only with the relevant Mapbox product(s) through
their Mapbox account in accordance with the Mapbox TOS.  This license
terminates automatically if a developer no longer has a Mapbox account in good
standing or breaches the Mapbox TOS. For the license terms, please see the
Mapbox TOS at https://www.mapbox.com/legal/tos/ which incorporates the Mapbox
Product Terms at www.mapbox.com/legal/service-terms.  If this Software is a
SDK, modifications that change or interfere with marked portions of the code
related to billing, accounting, or data collection are not authorized and the
SDK sends limited de-identified location and usage data which is used in
accordance with the Mapbox TOS. [Updated 2023-01]

-------------------------------------------------------------------------------

<br />

### Mapbox GL Directions
ISC License  
Copyright (c) 2015, Mapbox

Permission to use, copy, modify, and/or distribute this software for any
purpose with or without fee is hereby granted, provided that the above
copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR
ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN
ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF
OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.

-------------------------------------------------------------------------------

<br />

### Mapbox Polyline
BSD 3-Clause License  
Copyright (c), Development Seed  
All rights reserved.

Redistribution and use in source and binary forms, with or without modification,
are permitted provided that the following conditions are met:

- Redistributions of source code must retain the above copyright notice, this
  list of conditions and the following disclaimer.
- Redistributions in binary form must reproduce the above copyright notice, this
  list of conditions and the following disclaimer in the documentation and/or
  other materials provided with the distribution.
- Neither the name "Development Seed" nor the names of its contributors may be
  used to endorse or promote products derived from this software without
  specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR
ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON
ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

-------------------------------------------------------------------------------

<br />

### Turf.js
MIT License  
Copyright (c) 2019 Morgan Herlocker

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

-------------------------------------------------------------------------------

<br />

### Three.js
MIT License  
Copyright © 2010-2023 three.js authors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

-------------------------------------------------------------------------------

<br />

### Threebox
v.2.0.1 - v.2.2.6  
MIT License  
Copyright (c) 2020 Jesus Serrano

v.0.3.0  
MIT License  
Copyright (c) 2017 Peter Liu

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

-------------------------------------------------------------------------------

<br />

### Other Assets
3D Radar model
Attribution, no License specified: 
   Model by https://github.com/nasa/ from https://nasa3d.arc.nasa.gov/detail/jpl-vtad-dsn34  