# Image_analysis
For a group of objects contained within an image, this MATLAB script evaluates various geometric properties including separation between objects, number of nearest neighbors, etc. This program was used to uncover many-body interactions between colloidal nanocrystals in transmission electron microscopy (TEM) images of close-packed nanocrystal arrays. 

See also J. Am. Chem. Soc. 2015, 137 (13), 4494-4502

This folder contains:
1. Main program ("Image_analysis.m")
2. Ancillary functions: bandpass filter ("bpass.m"), particle detection ("pkfnd.m"), centroid calculator ("cntrd.m"), bond analyzer ("bond_analysis.m"), coordination analyzer ("coordination_analysis.m")
3. Sample electron microscopy images of 2D hexagonal arrays of Au nanocrystals, ("Example_image_1.jpg", ...)

Written by Michael Boles (University of Chicago) in March 2014 and updated in February 2018. I gratefully acknowledge William Irvine (University of Chicago), Eric Dufresne (Yale University), and David Grier (New York University) for providing the initial particle detection code.
