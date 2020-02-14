# Multi-class-and-Multi-label-Classification-using-SVM
Data Set Name: Anuran Calls (MFCCs)
Acoustic features extracted from syllables of anuran (frogs) calls, including the family, the genus, and the species labels.
Number of Instances (records in your data set): 7195

Number of Attributes (fields within each record): 22

Relevant Information:

This dataset was used in several classifications tasks related to the challenge of anuran species recognition through their calls. 
It is a multilabel dataset with three columns of labels. This dataset was created segmenting 60 audio records belonging to 4 different families, 8 genus, and 10 species. 
Each audio corresponds to one specimen (an individual frog), the record ID is also included as an extra column. 
We used the spectral entropy and a binary cluster method to detect audio frames belonging to each syllable. 
The segmentation and feature extraction were carried out in Matlab. After the segmentation we got 7195 syllables, which became instances for train and test the classifier. 
These records were collected in situ under real noise conditions (the background sound). 
Some species are from the campus of Federal University of Amazonas, Manaus, others from Mata Atlântica, Brazil, and one of them from Córdoba, Argentina. 
The recordings were stored in wav format with 44.1kHz of sampling frequency and 32bit of resolution, which allows us to analyze signals up to 22kHz. 
From every extracted syllable 22 MFCCs were calculated by using 44 triangular filters. These coefficients were normalized between -1 ≤ mfcc ≤ 1. 
The amount of instances per class are:

Families:
	 Bufonidae              68 
     Dendrobatidae         542 
     Hylidae              2165 
     Leptodactylidae      4420 

Genus:
     Adenomera          4150 
     Ameerega            542 
     Dendropsophus       310 
     Hypsiboas          1593 
     Leptodactylus       270 
     Osteocephalus       114 
     Rhinella             68 
     Scinax              148 

Species:
     AdenomeraAndre             672 
     AdenomeraHylaedact…       3478 
     Ameeregatrivittata         542 
     HylaMinuta                 310 
     HypsiboasCinerascens       472 
     HypsiboasCordobae         1121 
     LeptodactylusFuscus        270 
     OsteocephalusOopha…        114 
     Rhinellagranulosa           68 
     ScinaxRuber                148 
