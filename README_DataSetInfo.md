Reference Information
=====================

Provenance for this README
--------------------------

* File name: README_FelidDataset.md
* Authors: Julius A. Tabin
* Other contributors: Katherine A. Chiasson
* Date created: 2023-02-15
* Date most recently modified: 2023-02-15

Dataset Version and Release History
-----------------------------------

* Current Version:
  * Number: 1.0.0
  * Date: 2023-02-15
  * Persistent identifier: DOI: 10.5061/dryad.s4mw6m9b0
  * Summary of changes: n/a

* Embargo Provenance: n/a
  * Scope of embargo: n/a
  * Embargo period: n/a

Dataset Attribution and Usage
-----------------------------

* Dataset Title: Data for the article "Evolutionary Insights Into Felidae Iris Color Through Ancestral State Reconstruction"

* Persistent Identifier: https://doi.org/10.5061/dryad.s4mw6m9b0

* Dataset Contributors:

  * Creators: Julius A. Tabin and Katherine A. Chiasson

* Date of Issue: 2023-02-15

* License: Use of these data from Zenodo or GitHub is covered by the following license:
  * Title: GNU General Public License v3.0
  * Specification: https://www.gnu.org/licenses/gpl-3.0.en.html
  
* License: Use of these data from Dryad is covered by the following license:
  * Title: CC0 1.0 Universal (CC0 1.0)
  * Specification: https://creativecommons.org/publicdomain/zero/1.0/
  
* Data Reuse
  * The authors respectfully request to be contacted by researchers interested in the reuse of these data so that the possibility of collaboration can be discussed.

* Suggested Citations:

  * Dataset citation:
    > Tabin J.A. and K.A. Chiasson. 2023. Data for the article "Evolutionary Insights Into Felidae Iris Color Through Ancestral State Reconstruction", Dryad, Dataset, https://doi.org/10.5061/dryad.s4mw6m9b0

  * Corresponding publication:
    > Tabin J.A. and K.A. Chiasson. 2023. Evolutionary Insights Into Felidae Iris Color Through Ancestral State Reconstruction. Systematic Biology. Submitted. 

Contact Information
-------------------

  * Name: Julius A. Tabin
  * Affiliations: Department of Organismic and Evolutionary Biology, Harvard University
  * ORCID ID: https://orcid.org/0000-0002-3591-6620
  * Email: jtabin1@gmail.com
  * Alternate Email: jtabin@g.harvard.edu
  * Address: e-mail preferred

* Contributor ORCID IDs:
  * Julius A. Tabin: https://orcid.org/0000-0002-3591-6620
  * Katherine A. Chiasson: https://orcid.org/0000-0002-9729-1718

- - -

Additional Dataset Metadata
===========================

Acknowledgements
----------------

* Funding sources: This work was supported in part by a graduate stipend from the Department of Organismic and Evolutionary Biology at Harvard University.
* Formatting for this README file is based on the README file of LaPergola, J.B., C. Riehl, J.E. Martínez-Gómez, B. Roldán-Clarà, and R.L. Curry. 2022. Data for the article "Extra-pair paternity correlates with genetic diversity, but not breeding density, in a Neotropical passerine, the Black Catbird", Dryad, Dataset, https://doi.org/10.5061/dryad.2bvq83btg

- - -

Methodological Information
==========================

* Methods of data collection/generation: see manuscript and supplemental methods for details

- - -

Data and File Overview
======================

Summary Metrics
---------------

* File count: 19
* Range of individual file sizes: 1.78 KB - 4.49 MB
* File formats: .csv, .Rmd, .ipynb, .pdf, .xlsx, .docx


Table of Contents
-----------------

* Tabin_Chiasson_Supplemental_Methods_and_Results.docx
* Tabin_Chiasson_Supplemental_Figures.pdf
* Tabin_Chiasson_Supplemental_Table_1.xlsx
* Data_Collection_Script.ipynb
* Color_Presence_Reconstruction.Rmd
* Specific_Color_Reconstruction.Rmd
* Output_Specific_Colors.ipynb
* Find_Correlations.Rmd
* Tip_col_data.csv
* Node_col_data.csv
* general_data_brown_only.csv
* general_data_hazgre_only.csv
* general_data_yelbei_only.csv
* general_data_grey_only.csv
* general_data_blue_only.csv
* general_data_reordered.csv
* col_data.csv
* dom_col_data.csv
* enviro_data.csv


Setup
-----

* Unpacking instructions: n/a

* Recommended software/tools: Python version 3.8.8; RStudio 2021.05.24; R version 4.2.1

* Raw data files used for this analysis can be found at https://github.com/jtabin/Felid-Eyes

Notes
-----
* All cells left empty in any data file are because there is no data present there for that taxon. The programs for analysing the data have been designed with these gaps in mind and the gaps are intentional; data is not missing. 
* For some files below, there are columns  grouped corresponding to each of the five eye colors identified in the study: brown, hazgre (hazel/green), yelbei (yellow/beige), gray, and blue. In the follow data description, an x will stand in for any color name.

- - -

File Details
===================

Details for: Tabin_Chiasson_Supplemental_Methods_and_Results.docx
---------------------------------------

* Description: a Word document containing the supplemental methods and results for "Evolutionary Insights Into Felidae Iris Color Through Ancestral State Reconstruction"

* Format(s): .docx


Details for: Tabin_Chiasson_Supplemental_Figures.pdf
---------------------------------------

* Description: a .pdf file containing the supplemental figures and figure captions for "Evolutionary Insights Into Felidae Iris Color Through Ancestral State Reconstruction"

* Format(s): .pdf


Details for: Tabin_Chiasson_Supplemental_Table_1.xlsx
---------------------------------------

* Description: an Excel sheet containing Supplemental Table 1 for "Evolutionary Insights Into Felidae Iris Color Through Ancestral State Reconstruction"

* Format(s): .xlsx

* Variables:
  * Rename: Taxon name
  * Common Name: The common name of each taxon
  * Number of Images: The number of images used for data collection


Details for: Data Collection Script.ipynb
---------------------------------------

* Description: a Jupyter Notebook file containing code to take a folder of iris images for a species as its input and outputs which colors are present and their various shades. Some of this must be manually determined according to the methods outlined in "Evolutionary Insights Into Felidae Iris Color Through Ancestral State Reconstruction".

* Format(s): .ipynb


Details for: Color Presence Reconstruction.Rmd
---------------------------------------

* Description: an R Markdown file containing code for reconstructing which color eyes were present in the populations of each ancestor. This takes the output of "Data Collection Script.ipynb" as its input and outputs the reconstructions at each phylogenetic node, along with figures.

* Format(s): .Rmd


Details for: Specific Color Reconstruction.Rmd
---------------------------------------

* Description: an R Markdown file containing code for performing the reconstruction for the more specific colors (i.e. not just whether or not a color is present, but what its shades were exactly). This also takes the output of "Data Collection Script.ipynb" as its input and outputs the reconstructions at each phylogenetic node, along with figures.

* Format(s): .Rmd


Details for: Output Specific Colors.ipynb
---------------------------------------

* Description: a Jupyter Notebook file containing code for transforming the RGB .csv output of "Data Collection Script.ipynb" and "Specific Color Reconstruction.Rmd" into colorful images for figure creation. It also takes "shade_bg.png" as an background input, provided in the https://github.com/jtabin/Felid-Eyes repository.

* Format(s): .ipynb


Details for: Find Correlations.Rmd
---------------------------------------

* Description: an R Markdown file containing code for taking the output of "Data Collection Script.ipynb" and performing phylogenetic and tetrachoric correlations, resulting in raw data, as well as figures.

* Format(s): .Rmd


Details for: Tip_col_data.csv
---------------------------------------

* Description: a comma-delimited file containing the eye color information for the tips of the phylogenetic tree loaded in "Color Presence Reconstruction.Rmd" and "Specific Color Reconstruction.Rmd". This is the input to those files. 

* Format(s): .csv

* Variables:
  * Rename: Taxon name
  * x_col_num: How many distinct shades of a certain color appear for that species/node (determined by "Data Collection Script.ipynb")
  * x_order: The order of shades in the eyes (i.e. which shades are more abundant). This is 1-4 letters (d, m, and l), corresponding to dark, medium, and light shades. Thus, if a cell contained mdl, then the order of shade abundance in the eye of that row's taxon would be medium > dark > light.
  * x_pri and x_sec: The primary and secondary shades in the eye individually. For the mdl example, x_pri would contain m and x_sec would contain d.
  * x_light_R, x_light_G, and x_light_B: The red, green, and blue RGB values, respectively, for the light shade, provided it exists.
  * x_med_R, x_med_G, and x_med_B: The red, green, and blue RGB values, respectively, for the medium shade, provided it exists.
  * x_dark_R, x_dark_G, and x_dark_B: The red, green, and blue RGB values, respectively, for the dark shade, provided it exists.
  * x_excl_R, x_excl_G, and x_excl_B: The red, green, and blue RGB values, respectively, for rare fourth color, if it exists for some species, that was excluded in the comparative analyses.


Details for: Node_col_data.csv
---------------------------------------

* Description: a comma-delimited file containing the output of the phylogenetic reconstructions done by the programs.

* Format(s): .csv

* Variables:
  * Node: The node ID (ordered as the R package ape orders the nodes, with 1 being the common ancestor of the whole tree and 2 being the ancestor to the Felidae, etc.).
  * x_pres: Whether the taxon for each row contains that color eyes in its population (1 for yes, 0 for no).
  * Other columns are identical to those for Tip_col_data.csv above.


Details for: general_data_brown_only.csv, general_data_hazgre_only.csv, general_data_yelbei_only.csv, general_data_grey_only.csv, general_data_blue_only.csv, and general_data_reordered.csv
---------------------------------------

* Description: comma-delimited files containing subsets of the "Tip_col_data.csv" file, which are better for comparisons using "Specific Color Reconstruction.Rmd".

* Format(s): .csv

* Variables:
  * Columns are identical to those for Tip_col_data.csv above.


Details for: col_data.csv and dom_col_data.csv
---------------------------------------

* Description: comma-delimited files containing just the presence or absence of each overall eye color for each felid taxon considered in the study. dom_col_data.csv just contains the most common eye colors, determined using our experimental methods. 

* Format(s): .csv

* Variables:
  * x_pres: Whether the taxon for each row contains that color eyes in its population (1 for yes, 0 for no).


Details for: enviro_data.csv
---------------------------------------

* Description: a comma-delimited file containing the environmental/morphological data collected and made into parameters using our methods and supplemental methods.

* Format(s): .csv

* Variables:
  * Pupil_type: The pupil information for each species looked at in the study (i.e. whether they have round, vertical, or subcircular pupils).
  * Pupil_type_bin: The pupil information as numbers: 0 = vertical, 1 = subcircular, and 2 = round.
  * Pupil_type_revised: The pupil information for each species looked at in the study with subcircular pupils considered vertical (i.e. whether they have round or vertical pupils).
  * Pupil_type_revised_bin: The pupil information, with subcircular pupils considered vertical, as numbers: 0 = vertical, 1 = round.
  * Activity_type: The animal's observed activity habits (diurnal, nocturnal, and/or crepuscular) from the University of Michigan Animal Diversity Web.
  * Nocturnal, Crepuscular, Diurnal: Each corresponds to one activity mode with a 1 if that activity mode is present and a 0 if it is absent.
  * Nocturnal_prop: A metric for how nocturnal the animal is with a 3 for fully nocturnal, 2 if there is one other activity mode, 1 if there are two others, and 0 if the animal isn't nocturnal.
  * Region: Data on the zoogeographical region that each species is mainly found in (ethiopian, oriental, palearctic, nearctic, or neotropical). The regions and names are from the paper Johnson WE., Eizirik E, Pecon-Slattery J, Murphy WJ, Antunes A, Teeling E, O'Brien SJ. 2006. The late Miocene radiation of modern Felidae: a genetic assessment. Science 311(5757):73-77.
  * Ethiopian, Oriental, Palearctic, Nearctic, Neotropical: Each corresponds to one zoogeographical region with a 1 if the animal is present in the area and a 0 if it is absent. 
  *  Habitat: The animal's main habitat(s), determined by the University of Michigan Animal Diversity Web. Non-mutually exclusive possible options are desert, forest, savanna, mountains, rainforest, swamp, marsh, tundra, and taiga.
  * Desert, Savanna, Forest, Rainforest, Forest_Rainforest, Mountains: Each corresponds to one habitat with a 1 if the animal is present in the habitat and a 0 if it is absent. Forest_Rainforest is either/or Forest and Rainforest.
  * Habitat_num: The number of different habitats occupied by the animals.
  * Low_elevation_m, High_elevation_m: The lowest and highest elevation each taxon has been observed in (in meters). IMPORTANT: THIS DATA IS INCOMPLETE!
  * Length_low_cm, Length_high_cm, Length_avg_cm: Low, high, and average body length in cm. IMPORTANT: THIS DATA IS INCOMPLETE!
  * Skull_Length_mm: The skull length in mm. IMPORTANT: THIS DATA IS INCOMPLETE!
  * Mating: The mating system (promiscuous, polygynous, and/or monogamous).
  * Coat_pattern: Data on the coat pattern of each taxon: flecks, uniform, stripes, sblotch (small blotches), rosettes, and/or blotches. This is based on Werdelin L, Olsson L. 1997. How the leopard got its spots: a phylogenetic view of the evolution of felid coat patterns. Biol. J. Linn. Soc. 62(3):383-400.
  * Flecks, Uniform, Stripes, SBlotch, Rosettes, Blotches: Each corresponds to one coat pattern with a 1 if the animal has that pattern and a 0 if it doesn't.
  * Black_body_morethaneye: This has a 1 if there is black fur on the animal's body of greater area than the animal's eye and a 0 if it doesn't have that.
  * Black_tail_morethaneye: This has a 1 if there is black fur on the animal's tail of greater area than the animal's eye and a 0 if it doesn't have that.
  * Nose_color: Whether the animal has a black or pink nose.
  * Nose_black, Nose_pink: Each corresponds to one nose color with a 1 if the animal has that color and a 0 if it doesn't.
  * Hybridization: A list of the species that each animal has been seen to hybridize with in the modern day.
  * Ancient Hybridization: A list of the species that each animal is hypothesized to have hybridized with historically. 

- - -
END OF README