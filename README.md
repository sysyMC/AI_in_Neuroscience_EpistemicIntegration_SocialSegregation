# Epistemic integration and social segregation of AI in neuroscience

 This repository includes the original codes related to the study of the integration of AI in neuroscience provided in the follwing paper: 
 - Fontaine, S., Gargiulo, F., Dubois, M., Tubaro, P. (2023). *Epistemic integration and social segregation of AI in neuroscience*. Available at: https://arxiv.org/abs/2310.01046.

This work relies on the scientometric dataset available on the following Zenodo repository: https://doi.org/10.5281/zenodo.10777508. 

This dataset includes in particular neuroscience papers published in journals both referenced by the *Web of Science* and *SCImago Journal Rank*, which has been extracted from a datadump of the Microsoft Academic Knowledge Graph (version of 2020-05-29 available at https://doi.org/10.5281/zenodo.3936556).

Each notebook is named with a number indicating the chronological order of execution:
1) `dataset_preparation.ipynb`: import the dataset described above (after downloaded it from Zenodo), clean and pre-process the different preliminary databases, and compute some metrics which will be used in the following notebooks. It especially generates some transformed and/or filtered datasets that are also uploaded in the Zenodo repository mentioned below,
2) `citation_network_rankings.ipynb`: perform citational analysis of the whole neuroscience corpus,
3) `journals.ipynb`: study of the AI activity of the neuroscience journals and their related authors,
4) `author_collaboration_network.ipynb`: study of the neuroscientific collaboration network.

Throughout the codes, some paths toward directories of inputs' importation and outputs' saving (notably for data and figures that are heavy or obtained with long-lasting execution) need to be updated at the discretion of the user.
 
