fMRI
====

This iPython notebook shows some of the analyses done on auditory fMRI data. Analyses outside python include:
- SPM first and second level analysis (con_000*.img are second-level contrast files)
- Freesurfer segmentation and surface reconstruction

From SPM we take the data and perform PCA analyses and project the obtained PCs onto the brain.

Dependencies:
- Numpy/scipy
- Matplotlib
- Nipy
- Nibabel
- Mayavi (outside the notebook)

The last bit shows howto perform a gradient operation on a irregular grid, using n=5 nearest-neighbours (using sklearn.neighbors)
