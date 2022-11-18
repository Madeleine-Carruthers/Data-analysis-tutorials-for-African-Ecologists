
# Geometric-morphometrics
## A practical introduction to geometric morphometrics for ecologists

This folder contains step-by-step tutorials on preparing and analysing morphological data using a landmark-based geometric morphometrics approach.

Geometric morphometrics is a powerful method for quantifying biological shape variation between groups (e.g. between different habitats, populations, species), and can be used to look at how an organisms shape/morphology varies with other biotic or abiotic factors in their environment.

Traditional morphometric analyses are based on linear distance-based measurements between two points, such as head length, body depth, eye diameter (Figure A). While these can be highly informative, they don't provide good coverage of an organism’s overall morphology. Geometric morphometrics uses a set of precisely located landmarks to capture high coverage morphological information (Figure B). We can compare the relative positions of these landmarks configurations to investigate shape variation between individuals or groups, and identify functionally important chnages in morphology associated with different ecological environments.

![Traditional_vs_GM_schematics](https://user-images.githubusercontent.com/74772641/195985251-065f05f4-004a-4f84-815b-b7f88ea27d04.jpg)


In these tutorials we will introduce you to the practical and statistical methods used in geometric morphometrics. 

We will cover:

1.	Collecting and preparing digital images for geometric morphometrics
2.	Selecting and digitising landmarks
3.	Standardising landmark configurations across samples
4.	Visualising shape varaition
5.	Statistical analysis of shape variation

All software used in the tutorials are available for free.

## Software required

ImageJ - free to download from [https://imagej.nih.gov](https://imagej.nih.gov/ij/)

tpsUtil - free to download from [http://www.sbmorphometrics.org/soft-utility](http://www.sbmorphometrics.org/soft-utility.html)

tpsDig2 - free to download from [http://www.sbmorphometrics.org/soft-dataacq](http://www.sbmorphometrics.org/soft-dataacq.html)

MorphoJ - free to download from [https://morphometrics.uk/MorphoJ](https://morphometrics.uk/MorphoJ_page.html)


## Example data

A practice dataset is provided in the folder “Example Data”. This folder contains digital image files (.jpg) for 37 specimens of the East African cichlid *Astatotilapia calliptera* from Lake Masoko, and a metadata file (.csv) containing sample information for all specimens. These data are taken from Carruthers et al. 2022 ([https://doi.org/10.1101/2022.01.07.475335](https://doi.org/10.1101/2022.01.07.475335)). Following the step-by-step guides in the tutorials we will quantify morphological variation in body shape between individuals from the shallow-water littoral and the deep-water benthic populations of *Astatotilapia callipter* in the lake.


