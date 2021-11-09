# Creating Effective Scientific Figures 
Slides and additional resources for the JHU Data Services Workshop on Creating Effective Scientific Figures

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

## Color

The role of color in data visualization is profound. Choosing the right colors for your data visualization is essential. Some considerations for appropriate color choice include accessibility (ensuring colors are distinguishable, even to those with colorblindness), perceptual uniformity, and format (will the colors be differentiable even when printed in grayscale).  

* [Practical Rules for Using Color in Charts](http://www.perceptualedge.com/articles/visual_business_intelligence/rules_for_using_color.pdf): Stephen Few offers an excellent guide on for choosing colors for data visualizations: 
Arguably the most popular color palette generator is [ColorBrewer](http://www.colorbrewer2.org). ColorBrewer allows for the creation of colorblind safe, print friendly safe, and photocopy safe color palettes so your data visualizations will be accessible and usable to your entire audience. 

[![Color Brewer](ColorBrewer.png)](http://www.colorbrewer2.org)

When working in scientific visualization, pseudocoloring 2D and 3D scalar fields, such as a topographical surface map, choice of color map is important. Color maps should change uniformly in brightness to indicate changes in value. The perceptual changes in commonly used color maps however, such as the rainbow color map ubiquitous in Matlab, do not abide by these rules. This leads to misleading interpretations of scientific figures. 

Kenneth Moreland, PhD at Sandia National Laboratories, offers some useful advice on choosing the appropriate color map for your scientific visualization: 

[Color Map Advice for Scientific Visualization](https://www.kennethmoreland.com/color-advice/)

[![Color Advice](https://www.kennethmoreland.com/color-advice/smooth-cool-warm/smooth-cool-warm-3d.png)](https://www.kennethmoreland.com/color-advice/)

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
