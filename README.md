# arxiv_2008.01843
Code repo for manuscript https://arxiv.org/abs/2008.01843

<a href="https://doi.org/10.5281/zenodo.4316395"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.4316395.svg" alt="DOI"></a>


## Files

  1. `simulatedDiffraction.ipynb`: The Jupyter notebook to generate the images in the manuscript.
  1. `ExperimentalGeometry.py`: Module for coordinate conversions for BCDI. Originally appears in the [Phaser](https://git.io/Jk5Ai) code base. 
  1. `PlotLikeMatlab.py`: Basic 3D isosurface plotting routines for recovering Matlab addicts like myself. Uses [PyVista](https://docs.pyvista.org/).
  1. `Pyramid.py`: Routines for generating a 3D array containing a discretely sampled pyramid.
  1. `skewedDetectorImage.py`: Script for generating the tilted detector schematic in Figure 3.
  1. `TiilePlot.py`: Custom routine for producing subplots in Matplotlib. First appears in the [Phaser](https://git.io/Jk5Ai) code base.
  1. `aps.mplstyle`: My custom Matplotlib style file for APS journal submissions (Times font, etc.)
  
  Make sure the Jupyter notebook can see all these files when it is running.
  
