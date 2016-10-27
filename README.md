![](https://raw.githubusercontent.com/marcoalopez/GrainSizeTools/master/FIGURES/header_fig.png)

[GrainSizeTools script](http://marcoalopez.github.io/GrainSizeTools/) is a free open-source cross-platform script written in [Python][1] that provides several tools to characterize the grain size from thin sections. The script is suitable to use for paleopiezometry (paleowattmetry) studies and to derive the actual 3D grain size distribution using the Saltykov and the two-step methods. The script only requires measuring the grain sectional areas from a thin section in advance and **does not require a previous experience with Python programming language** (see [documentation][2]). For users with coding skills, the script is organized in a modular way using Python functions, which facilitates to modify, reuse or extend the code if needed.

Screenshots
-------------
![Figure 1. Screenshots (right)](https://raw.githubusercontent.com/marcoalopez/GrainSizeTools/master/FIGURES/screenshots_fig-01.png)  
[enlarge image](https://raw.githubusercontent.com/marcoalopez/GrainSizeTools/master/FIGURES/screenshots_fig-01.png)

Features at a glance
-------------

- It allows loading and extracting data from txt and csv files generated by the ImageJ or other applications.
- It allows calculating the apparent diameters of the grain profiles via the equivalent circular diameter and to correct, if required, the diameters by adding the perimeter of the grains.
- It allows estimating different 1D grain size measures for paleopiezometry studies, including the mean, the median, the area-weighted mean and the frequency peak of the apparent grain sizes (also the log or square root apparent grain sizes).
- It implements several algorithms to estimate the optimal bin size of histograms and the optimal bandwidth of the Gaussian KDE based on the population features.
- It allows deriving the actual 3D grain size distribution from thin sections (2D data) using the Saltykov method. Similar to what the StripStar script does.
- It returns the volume of a particular grain fraction defined by the user.
- It allows to estimate a complete quantitative description of the 3D grain size distribution using a novel method named the two-step method.
- It produces different ready-to-publish plots, allowing to save the graphical output as a bitmap or vector images (see the image above for examples)

Download
-------------

You can download the script at the following sites (***Latest release 2016/07/08: v1.2***):  
https://github.com/marcoalopez/GrainSizeTools/releases  
http://figshare.com/articles/GrainSizeTools_script/1383130  
https://sourceforge.net/projects/grainsizetools/

Documentation
-------------
Look at the [table of contents](https://github.com/marcoalopez/GrainSizeTools/blob/master/DOCS/tableOfContents.md). You can also download a manual in pdf format [here](http://figshare.com/articles/GrainSizeTools_script_manual/1371025).


Citation guidelines
-------------
If you need to cite the script or the methods, the following references are available:

###Script reference
Lopez-Sanchez, Marco A. (2016): GrainSizeTools script. figshare. http://dx.doi.org/10.6084/m9.figshare.1383130

###Methods:
***Frequency peak grain size based on Gaussian KDE***  
Lopez-Sanchez MA and Llana-Fúnez S (2015) An evaluation of different measures of dynamically recrystallized grain size for paleopiezometry or paleowattmetry studies. *Solid Earth* 6, 475-495. doi:[10.5194/se-6-475-2015](http://dx.doi.org/10.5194/se-6-475-2015)

***Two-step method***  
Lopez-Sanchez MA and Llana-Fúnez. An extension of the Saltykov method to quantify 3D grain size distributions in mylonites. *Journal of Structural Geology*, *In Press, Accepted Manuscript* doi:[10.1016/j.jsg.2016.10.008](http://dx.doi.org/10.1016/j.jsg.2016.10.008).

***Saltykov method***  
The method as implemented in the GrainSizeTools script is described in the Appendix A in Lopez-Sanchez and Llana-Fúnez (*In press*) *J. Struc. Geol.* doi:[10.5194/se-6-475-2015](http://dx.doi.org/10.5194/se-6-475-2015) The procedure is partially based on general formulation developed by Sahagian and Proussevitch (1998) *J. Volcanol. Geotherm. Res.* 84, 173–196. doi:[10.1029/95JB02500](http://dx.doi.org/10.1016/S0377-0273(98)00043-2)

License
-------------
GrainSizeTools script is licensed under the [Apache License, Version 2.0 (the "License")](http://www.apache.org/licenses/LICENSE-2.0)

The documentation of GrainSizeTools script is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.  
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />



 [1]: https://www.python.org/
 [2]: https://github.com/marcoalopez/GrainSizeTools/blob/master/DOCS/tableOfContents.md
