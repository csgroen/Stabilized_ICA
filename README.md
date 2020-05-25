# Stabilized_ICA

This repository proposes a python implementation for stabilized ICA decomposition algorithm. Most of the technical details can be found in the references [1], [2] and [3]

## Experiments

We provide two jupyter notebooks for an illustration with transcriptomic data:
* [ICA decomposition with stabilized ICA](transcriptomic_ICA.ipynb)
* [Stability of ICA components accross several NSCLC cohorts](stability_study.ipynb)

## Data

The data set which goes with the jupyter notebook ["ICA decomposition with stabilized ICA"](transcriptomic_ICA.ipynb) can be found in the .zip file [data.zip](data.zip). Please extract locally the data set before running the notebook.   

For the jupyter notebook ["Stability of ICA components accross several NSCLC cohorts"](stability_study.ipynb) please note that you will have to load the data himself in order to run it.

## Requirements

To run this algorithm as well as the jupyter notebook, one will need the following python packages:
* numpy
* matplotlib.pyplot
* pandas
* scikit-learn
* tdqm 
* networkx
* scipy

## References

[1] "Determining the optimal number of independent components for reproducible transcriptomic data analysis" - Kairov et al. 2017   
[2] "Assessing reproducibility of matrix factorization methods in independent transcriptomes" - Cantini et al. 2019    
[3] "Icasso: software for investigating the reliability of ICA estimates by clustering and visualization" - Himberg et al. 2003