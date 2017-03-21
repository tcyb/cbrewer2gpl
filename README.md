# cbrewer2gpl

An GIMP/Inkscape compatible color palette from Cynthia Brewer's ColorBrewer project.

## Use

Download the `cbrewer.gpl` file and place it in the Palette directory of either Inkscape or GIMP.

## About

The notebook in this repository simply reads in the ColorBrewer spec, finds the largest map for each defined colormap, and outputs the colors to the (very simple) `.gpl` palette format defined by GIMP.
It's nothing novel, but hopefully convenient for those doing data representation in software like Inkscape.

You can find the original color specs and the JSON file, which is all the actual hard work, at [http://colorbrewer2.org](http://colorbrewer2.org).

## License

The color schemes used here (and thus the included `colorbrewer.json` and `cbrewer.gpl` files) are covered by an Apache 2.0 license. That text is here:

> Apache-Style Software License for ColorBrewer software and ColorBrewer Color Schemes
>
> Copyright (c) 2002 Cynthia Brewer, Mark Harrower, and The Pennsylvania State University.
>
> Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. 
> You may obtain a copy of the License at 
>
> http://www.apache.org/licenses/LICENSE-2.0 
>
> Unless required by applicable law or agreed to in writing, software distributed 
> under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR 
> CONDITIONS OF ANY KIND, either express or implied. See the License for the 
> specific language governing permissions and limitations under the License.

You can find further information at [Cynthia Brewer's website](http://www.personal.psu.edu/cab38/ColorBrewer/ColorBrewer_updates.html)


