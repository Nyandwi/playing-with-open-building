# Playing with Open Buildings Dataset

Open Buildings is a large scale dataset that contains the outlines(or segmentation maps) of buildings that are extracted from the satellite images in Africa(64% of the continent).

The dataset contains 516M buildings maps. Quoting the dataset [homepage](https://sites.research.google/open-buildings/), "*for each building in this dataset we include the `polygon` describing its footprint on the ground, a `confidence score` indicating how sure we are that this is a building, and a `Plus Code` corresponding to the centre of the building. There is no information about the type of building, its street address, or any details other than its geometry.*"


The dataset can be used for:
- Estimating the population density(number of people per unit area) that can potentially facilitate `planning` and `statistics`(estimates).
- To predict the number of affected buildings caused by natural disasters(floods, drought) in a given area.
* Facilitating digital systems/services in areas that don't have recognized street addresses such as [PlusCode](https://maps.google.com/pluscodes/)(I didn't know that I have a free code that holds my location until learning about this data)!

* The dataset can also assist national activities that require knowledge of pupulation density and settlement density or infrastructure usage such as vaccination plannings, mosquito-net distribution, school and health centres, transportations, etc..More about those use-cases [here](https://sites.research.google/open-buildings/).


## Quick Links/Further Reading:

* [Dataset Home](https://sites.research.google/open-buildings/
)
* [Continental-Scale Building Detection from High Resolution Satellite Imagery](https://arxiv.org/abs/2107.12283)
* [Colab notebook](https://colab.research.google.com/github/google-research/google-research/blob/master/building_detection/open_buildings_spatial_analysis_examples.ipynb)

## To do:
* Play with the data
* Read the dataset release paper
* Think about other use-cases?


```
W. Sirko, S. Kashubin, M. Ritter, A. Annkah, Y.S.E. Bouchareb, Y. Dauphin, D. Keysers, M. Neumann, M. Cisse, J.A. Quinn. 
Continental-scale building detection from high resolution satellite imagery.
arXiv:2107.12283, 2021.
```

