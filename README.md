# Felid Iris Color Analysis
This repository contains the images and code used for the analysis done in "Evolutionary Insights Into Felidae Iris Color Through Ancestral State Reconstruction".

- Data
  - The "Data" folder contains .csv files needed to run the analyses. All of them were produced through the code presented here, except for "enviro_data.csv" which was collected as represented in the paper.
  - The "Felid Pictures" folder contains subfolders with the original pictures used for each taxa considered in the study.
  - The "Felid Pictures Cut Out" folder contains the same subfolders as above, but with an iris from each image completely isolated.

- Code
  - "Data Collection Script.ipynb" takes a folder of iris images for a species as its input and outputs which colors are present and their various shades. Some of this must be manually determined according to the methods outlined in the paper.
  - "Color Presence Reconstruction.Rmd" is the code for reconstructing which color eyes were present in the populations of each ancestor. This takes the output of "Data Collection Script.ipynb" as its input and outputs the reconstructions at each phylogenetic node, along with figures. 
  - "Specific Color Reconstruction.Rmd" performs the reconstruction for the more specific colors (i.e. not just whether or not a color is present, but what its shades were exactly). This also takes the output of "Data Collection Script.ipynb" as its input and outputs the reconstructions at each phylogenetic node, along with figures. 
  - "Output Specific Colors.ipynb" transforms the RGB .csv output of "Data Collection Script.ipynb" and "Specific Color Reconstruction.Rmd" into colorful images for figure creation. It also takes "shade_bg.png" as an background input, provided in this repository as well.
  - "Find Correlations.Rmd" takes the output of "Data Collection Script.ipynb" and performs phylogenetic and tetrachoric correlations, resulting in raw data, as well as figures.
 
These methods can be applied to any color reconstruction, whether or not phylogenetics are involved. For more detail about the files or code presented here, please see the file "README_DataSetInfo.md" presented here or go to https://doi.org/10.5061/dryad.s4mw6m9b0.

#### I hope this data and analysis is useful! Please do not hesitate to contact me with questions at jtabin1@gmail.com!
