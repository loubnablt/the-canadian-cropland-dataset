
<h1 style="text-align: center;"> Website Content </h1>

<h1 style="text-align: center;"> Dataset Description </h1> 

### Abstract 

The *Canadian Cropland Dataset* is a temporal patch-based dataset of remote sensing images of Canadian croplands retrieved from the Sentinel-2 satellite constellation. The dataset contains 78,536 manually verified and curated high-resolution (10 m/pixel, 640 x 640 m) geo-referenced images from 10 crop classes collected over four crop production years (2017-2020) and five months (June-October) which were extracted using [Google Earth Engine](https://earthengine.google.com/  "Google Earth Engine") (GEE) and were automatically labelled with the [Canadian Crop Inventory](https://www.agr.gc.ca/atlas/aci "Canadian Crop Inventory") Each instance contains 12 spectral bands, an RGB image, and additional vegetation index bands. Individually, each crop category contains at least 4,800 samples. In perspective, we expect this evolving dataset to propel the creation of robust agro-environmental models that can accelerate the comprehension of complex agricultural regions by providing accurate and continuous monitoring of land cover.

**Keywords :** satellite imagery, remote sensing, dataset, agriculture, cropland, supervised learning, image classification, deep learning.

___

### Key Features

- **Multitemporal remote sensing dataset spanning multiple years :** . More than 70% of geolocations have an image collection of at least 10 images (over 4 years), allowing a temporally rich monitoring of a field through a multi-year, multi-crop rotation
- **Transformed .PNG images ready to be directly used with existing deep learning benchmarks :** Each field instance contains an RGB image as well as common vegetation index images (NDVI, GNDVI, OSAVI, etc.) in .PNG format.
- **High spectral resolution images :** We also supply a .zip folder with the original Sentinel-2 bands (12) and 6 additional vegetation index bands as georeferenced .TIF files. 
- **Pre-constructed train / val / test sets :** The dataset comes prepackaged in dedicated training (70%), validation (15%) and testing sets (15%) suitable for use with Keras or Tensorflow image data generators. These sets remain the same for each individual year and image type (i.e NDVI, PSRI, etc.). Images belonging to the same geographical coordinates were kept together during the dataset splitting process

___

### Download Link

Both the cleaned and RAW versions of the dataset and can be downloaded from this [Google Drive ](https://drive.google.com/drive/folders/1mNI8B5EMk0Xgvx2Pc9ztnQRaW9pXh8yb?usp=sharing "Link to dataset") link. 

___

### License 

**The dataset** is released under the [*Montreal Data License*](https://github.com/bioinfoUQAM/Canadian-cropland-dataset/blob/main/DATA_LICENSE) which is a [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) creative commons license. The dataset is available for researchers, principal investigators, individuals, government workers that will use the dataset purely for discovery and **not for commercial purposes**. 

**The software** for benchmarking is available under the [MIT](https://github.com/bioinfoUQAM/Canadian-cropland-dataset/blob/main/CODE_LICENSE) license.

___

<h1 style="text-align: center;"> How we created it </h1>

### Image and Label Collection

___


### Data Cleaning

___


### Dataset Statistics 

___


<h1 style="text-align: center;"> Benchmarking </h1>

We present two classification experiments performed using the 2019 version of the dataset to infer the main crop types present in each image. In the first experiment, *static classification*, we treated each individual image as a training instance (static image classification). In the second experiment, *dynamic classification* we explored the use of a temporal image series as an input. 






Results for both experiments are figured below. 


### Static Classification 

___


### Dynamic Classification 

___


### Results

___



<h1 style="text-align: center;"> Downloads </h1>

### Data and Datasheet 

Both the cleaned and RAW versions of the dataset and can be downloaded from this [Google Drive ](https://drive.google.com/drive/folders/1mNI8B5EMk0Xgvx2Pc9ztnQRaW9pXh8yb?usp=sharing "Link to dataset") link. The *Datasheet* associated with this dataset can be downloaded as a .pdf [here](TBA). 
<!--- # COMMENT: (Eventually these links will be replaced with a link to the OSF.) -->
___


### Paper

The paper associated with this dataset can be found on [ArXiv](https://arxiv.org/abs/2306.00114). If you find this dataset or the benchmarks useful in your research, please cite the paper as: 

> ``` @misc{boatswainjacques2023canadian,
      title={The Canadian Cropland Dataset: A New Land Cover Dataset for Multitemporal Deep Learning Classification in Agriculture}, 
      author={Amanda A. {Boatswain Jacques} and {Abdoulaye Baniré} Diallo and Etienne Lord},
      year={2023},
      eprint={2306.00114},
      archivePrefix={arXiv},
      primaryClass={cs.CV}} ```

___

<h1 style="text-align: center;"> Contact </h1>


## Collaborators

### UQAM 
<!--- # Add UQAM and Bioinformatics Lab Logo -->   
**Bioinformatics Laboratory**   
Amanda A. Boatswain Jacques, Abdoulaye Baniré Diallo, Loubna Bellatreche

### AAFC 
<!--- # Add AAFC Logo -->
**Digital Agronomy and Geomatics research group**   
Etienne Lord, Samuel de Sablonnière 


## Contact

For inquiries, contact Amanda Boatswain Jacques (boatswain_jacques.amanda@courrier.uqam.ca). 
		
___



# Website footer 

To be adjusted **in the layout**.

Website hosted on [Github](https://github.com/). Last Updated 2023-07-XX.
