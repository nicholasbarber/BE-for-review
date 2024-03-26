# BE-for-review

Title: Moisture and material shape microbial communities in the built environment through disturbance–productivity relationships

Summary: Disturbance regime (wet-dry cycling) was manipulated on 3 common building materials to determine how productivity and disturbance interaction to shape alpha and beta diversity of microbial communities in the build environment. 

Files:

metadata_and_counts.csv
Contains experimental design variables (treatments, material types, and sampling time points), measurements of bacterial (Objects.mL, Objects.cm2) and fungal abundance (spore_density, hyphal_length), as well as richness, Chao Shannon diversity, and number of reads for bacteria (16S) and fungi (ITS). 

clean_ITStable.tsv
Fungal read counts of each sample, identified to genus level. Note code around line 785 of script corrects mis-alignment in this datafile.

clean_16Stable.tsv
Bacterial read counts of each sample, identified to genus level. 

itsfeaturetable.tsv
Raw fungal OTU counts by sample. 

16S-features.tsv
Raw bacterial OTU counts by sample. 

Full_BE_manuscript_analysis_anonymized.Rmd
Complete script to reproduce data analysis in manuscript, anonymized for double-blind review. 

Instructions: .Rmd is set to use current diretory as working directory, so having .Rmd and all 5 data files in a single directory or folder will allow the analysis to be reproduced. Either Run All, or Knit to generate html output. 

