# Invasive Electrodes Identification and Labeling
<img src="https://user-images.githubusercontent.com/1643819/33784517-2d0ba35c-dc2f-11e7-9136-a4290882a79f.png">

[![DOI](https://zenodo.org/badge/113069975.svg)](https://zenodo.org/badge/latestdoi/113069975)

Currently, the implementation is scattered over several repositories:
1) Grids and stips electrodes identification and labeling: 
https://github.com/aestrivex/ielu
2) Depth electrodes identification and labeling: 
https://github.com/pelednoam/mmvt/tree/master/src/misc/dell
3) Electrodes labeling algorithm (ELA):
https://github.com/pelednoam/electrodes_rois
4) Visualization:
https://github.com/pelednoam/mmvt

# Electrode Labelling Algorithm
The electrode labeling algorithm (ELA) main purpose is to estimate the probability that a particular brain region contributes to the source of the signal at each electrode using purely anatomical approaches. Even through electrodes in the brain, whether placed in either white or grey matter, receives a signal from multiple sources, current thought is that the signal is generated from the local field potentials from grey matter (whether cortical or subcortical). We developed a simple and approachable ELA to identify this source by identifying the overlap of an expanding area (cylinder) around each electrode with identified brain structure labels. We are mapping these electrodes to regions in a given location which can be flexibly chosen within Freesurfer. Here we used the DKT atlas in combination with a subcortical mapping enabled through Freesurfer (Desikan et al., 2006; Fischl et al., 2004). 

# Suggested Citation
Peled N, Gholipour T, Paulk AC, Felsenstein O, Eichenlaub JB, Dougherty DD, Widge AS, Eskandar EN, Cash SS, Hamalainen MS, Stufflebeam SM (2017). Invasive Electrodes Identification and Labeling. GitHub Repository. https://github.com/pelednoam/ieil DOI:10.5281/zenodo.1078789
