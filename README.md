# visualisation-tools

A collection of resources that may be of use for geoscience data visualisation. 

\* Denotes tools that I haven't tried yet myself. 

## Colour

- Nice article on how colour determines what we see https://eos.org/features/visualizing-science-how-color-determines-what-we-see
- A suite of tools and articles on colour in scientific visualisation https://sciviscolor.org/
- Colour blindness simulator https://www.color-blindness.com/coblis-color-oblindness-simulator/
- Colour brewer for maps https://colorbrewer2.org/
- Tool for taking colours from images but also has a converter to change rgb to hex https://lokeshdhakar.com/projects/color-thief/ 
- Beautiful colour pallets using New Zealand native birds https://g-thomson.github.io/Manu/ *
- Check that your colour palette works https://projects.susielu.com/viz-palette
- Colour palette generator https://learnui.design/tools/data-color-picker.html
- Colour maps on seismic sections (includes semi-transparent) https://github.com/lperozzi/Seismic_colormaps *

## 3D visualisation

- Paraview (VTK) https://www.paraview.org/
- PyVista for 3D and mesh (also VTK) https://docs.pyvista.org/ *
- Point cloud visualisation tool https://polyscope.run/py/ *
- Blender https://www.blender.org/ *

## Plotting packages 
These are mostly wrappers around the standard Python plotting tool matplotlib (mpl). Many seek to simplify generating visually appealing/useful plots in one line of code, rather that doing all the formatting work in mpl.  
- Seaborn https://seaborn.pydata.org/
- Altair https://altair-viz.github.io/ *
- Similar to Pandas but with more advanced plotting https://vaex.readthedocs.io/en/latest/tutorial.html#xarray-suppport *
- Ploty https://plotly.com/python/ *
    - https://plotly.com/python/linear-fits/ to make linear trendlines
    - https://link.medium.com/iNSzUe0oy5 plotly fancy plots
    - https://link.medium.com/MQTSVeGDL5 good plotly tutorial
    - https://link.medium.com/ZvdW7rTDL5 interactive maps
    - https://link.medium.com/eK7qYSYDL5 categorical data
    - https://towardsdatascience.com/extraordinary-data-visualisation-circular-chart-fe2d835ef929 circular plots
- Javascript plotting tool https://d3js.org/

## Matplotlib
- Best intro to mpl plt and ax methods https://towardsdatascience.com/clearing-the-confusion-once-and-for-all-fig-ax-plt-subplots-b122bb7783ca

## Complex data plots and machine learning
- Plotting high dimensional datasets with manifold https://www.scikit-yb.org/en/latest/api/features/manifold.html *
- Circular plots to visualise multi-dimensional data sets https://www.scikit-yb.org/en/latest/api/features/radviz.html *

## Open source tools
- Vector graphics https://inkscape.org/
    - https://trichopterology.blogspot.com/2017/05/using-inkscape-for-biological.html
    - https://www.library.auckland.ac.nz/search/inkscape

## Tutorials from the web
- Finessing graphics https://ourcodingclub.github.io/tutorials/dataviz-beautification/

## Code fragment reminders

Colour maps in mpl
```
    countries = df['Country Name']
    color = cm.rainbow(np.linspace(0, 1, len(countries))))
    # length can be an object or get python to test length
```

## Inspiration

- https://urbanmobilityindex.here.com/ beautiful interactive graphics
- https://www.cleverfranke.com/work/chicago-s-mobility more wow vis
- https://informationisbeautiful.net/ collection of infographics