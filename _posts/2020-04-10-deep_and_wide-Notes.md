### Notes

[deep learning remote sensing tutorial](https://blesaux.github.io/courses/JURSE_Deep_Learning_for_Remote_Sensing_Tutorial.pdf)

* Identifying things on the ground is an example of [segmentation](https://medium.com/@sunnerli/simple-introduction-about-hourglass-like-model-11ee7c30138).  Objects can be a rare class.
* Universal Approximation Theorem - any function can be approximated by a MLP (multilayerd perceptron) of sufficient width
* receptive field - values of a layer only depend on a small number of points in the previous layer
* pooling layers - decrease the number of features

![diagram of image recognition](https://github.com/PipCourbois/github.io/blob/master/img/image%20recognition%20NN.png)

* Deep learning on raster images
* [Hourglass](https://medium.com/@sunnerli/simple-introduction-about-hourglass-like-model-11ee7c30138) model for segmentation
* look up "mapping and monitoring marine turtles from UAVs in environmental surveys"

### references
* _Deep Learning for Remote Sensing Data: A Technical Tutorial on the State of the Art_, Zhang, Zhang and Du, IEEE Geosci. and Rem. Sens. Mag, 6 (2) June 2016
* _Deep learning in remote sensing: A comprehensive review and list of resources_, Zhu, Tuia, Mou, Xia, Zhang, Xu, and Fraundorfer, IEEE Geosci. and Rem. Sens. Mag, 5 (4) Dec. 2017
* _Deep Learning for Classification of Hyperspectral Data: A Comparative Review_, Audebert, Le Saux and Lefevre, IEEE Geosci. and Rem. Sens. Mag., 7 (2) June 2019

### tools
* DeepNetsForEO (https://github.com/nshaud/DeepNetsForEO): python code for semantic segmentation of aerial / satellite imagery
* DeepHyperX (https://github.com/nshaud/DeepHyperX): python toolbox for classification of hyperspectral imagery (spectral, spatial-spectral and 3D convolutions)

### Datasets

* ISPRS datasets: semantic labeling, reconstruction https://www.isprs.org/data/
* IEEE GRSS Data Fusion Contests: http://www.grss-ieee.org/community/technical-committees/data-fusion/data-fusion-contest/
* IEEE GRSS: hyperspectral datasets with standard train/test splits (DFC2018, Pavia, Indian Pines) http://dase.grss-ieee.org/
* INRIA Aerial Semantic labeling dataset: buildings https://project.inria.fr/aerialimagelabeling/
* XView: objects in aerial images http://xviewdataset.org/
* DOTA: Detecting Objects in Aerial images https://captain-whu.github.io/DOTA/dataset.html

### NEXT
* Go through the practical steps on colab.  (page 95)
