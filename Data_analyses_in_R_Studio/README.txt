***Impact of yeast-derived β-glucans on the porcine gut microbiota and immune system in early life***

Hugo de Vries 1,2,$ , Mirelle Geervliet 3,$ , Christine A. Jansen 4 , Victor P. M. G. Rutten 4,5 ,
Hubèrt van Hees 6 , Natalie Groothuis 3, Jerry M. Wells 2, Huub F. J. Savelkoul 3 ,
Edwin Tijhaar 3,$ and Hauke Smidt 1,*,$

1 Laboratory of Microbiology, Wageningen University, 6700 EHWageningen, The Netherlands;
hugo.devries@wur.nl
2 Host-Microbe Interactomics Group,Wageningen University, 6700 AH Wageningen, The Netherlands;
jerry.wells@wur.nl
3 Cell Biology and Immunology Group,Wageningen University, 6700 AH Wageningen, The Netherlands;
mirelle.geervliet@wur.nl; natalie.groothuis@hotmail.com; huub.savelkoul@wur.nl;
edwin.tijhaar@wur.nl
4 Department of Biomolecular Health Sciences, Division of Infectious Diseases and Immunology, Faculty of
Veterinary Medicine, Utrecht University, 3584 CL Utrecht, The Netherlands; c.a.jansen@uu.nl;
v.rutten@uu.nl 
5 Department of Veterinary Tropical Diseases, Faculty of Veterinary Science, University of Pretoria,
Private Bag X04, Onderstepoort 0110, South Africa
6 Research and Development, Trouw Nutrition, 3800 AG Amersfoort, The Netherlands;
hubert.van.hees@trouwnutrition.com

* Correspondence: hauke.smidt@wur.nl

$ Authors contributed equally to this work.
Received: 31 August 2020; Accepted: 9 October 2020; Published: 13 October 2020

***General Introduction***
This dataset contains data collected during an in vivo experiment with piglets as part of the PhD Thesis Projects of Hugo de Vries and Mirelle Geervliet (first authors of the manuscript). 
DOI: 10.4121/12999620
This research project was made possible by The Netherlands Organisation for Scientific Research and Vereniging Diervoeders Nederland (VDN).

***Purpose of the study***
In this study, we investigated whether early life supplementation of yeast-derived β-glucans affects the gut microbiota as well as the immune system. 
In addition, we examined the temporal dynamics of these complex systems. 
We hypothesized that early life consumption of yeast-derived β-glucans alters gut microbiota development (composition) and the immune system. 
A more developed and mature gut microbiota and immune system in early life could make the animals more resilient against invasive pathogens during the weaning phase and later in life.

***Structure***
Data_analyses_in_R_Studio/ # Main data analysis folder.
				|---- Figures # folder where raw figures are placed when generated in R-Studio.
				|---- input_data # this folder contains data files that are imported into R-Studio for microbiota related analyses, such as the .biom, .tre and metadata files.
				|---- input_data_flow_cytometry # this folder contains data files that are imported into R-Studio for flow cytometry related analyses.
				|---- Input_data_restimulation_assay # this folder contains data files that are imported into R-Studio for restimulation assay related analyses.
				|---- input_data_vaccination_response # this folder contains data files that are imported into R-Studio for vaccination response related analyses.
				|---- output_data # two data files were generated in the R code, which are placed into this folder.
				|---- phyobjects # phyloseq objects that were generated in the R code are placed into this folder. these .rds files are frequently imported into R (with every new analysis they are re-imported).
				|---- Porcine_study_Y_glucan_R_analyses_july2020.Rproj # Rproject file.
				|---- Porcine_study_Y_glucan_R_analyses_july2020_markdown_file.html # HTML file that was generated using the knitr function in R-Studio. This file has been copied to the master folder, as it contains a complete overview of the analyses performed.
				|---- Porcine_study_Y_glucan_R_analyses_july2020_markdown_file.rmd # Codes used during the analyses.
				
***Instructions***
1. Open 'Porcine_study_Y_glucan_R_analyses_july2020.Rproj' in R-Studio.
2. Open 'Porcine_study_Y_glucan_R_analyses_july2020_markdown_file.RMD' and click knit to reproduce the analyses and re-create the HTML file.
3. If an error occurs, make sure to use the same version of R and install the same versions of the R packages used. This info can be found at the end of the HTML file.

The final figures in the manuscript were adjusted using Adobe Illustrator to improve their clarity (i.e. label font/direction).
			