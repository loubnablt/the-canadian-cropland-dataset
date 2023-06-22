---
layout: default
title: How we created it 
---

### Image and Label Collection

___


### Data Cleaning

___


### Dataset Statistics 

<style>
    .image-container {
      display: flex; /* Utiliser le flexbox pour aligner les images horizontalement */
      justify-content: space-between; /* Espacement égal entre les images */
    }
    
    .image-container figure {
      width: 50%; /* Chaque figure prend 50% de la largeur du conteneur */
      text-align: center; /* Centrer le contenu de la figure */
    }
    
    .image-container img {
      width: 100%; /* L'image occupe toute la largeur de la figure */
    }
  </style>
<!--  <style>
    h4 {
        text-align: center;
    }
  </style>
  --->

<h4>Count of the number of images for each crop type</h4>

  <div class="image-container">
    <figure>
      <img src="figures/crop_counts_all_years(2016-2019).png" alt="crop counts all years" width="700" height="400">
      <figcaption>Figure 4: Representation of the crop counts from year 2016 to 2019</figcaption>
    </figure>
    <figure>
      <img src="figures/crop_counts_all_years_individual.png" alt="crop counts all years individual" width="700" height="400">
      <figcaption>Figure 5: Representation of the crop counts all years (from 2016 to 2019) individually</figcaption>
    </figure>
  </div>


<h4>Count of the number of sets for each image in a set</h4>


<div class="image-container">
<figure>
    <img src="figures/image_counts_all_years(2016-2019).png" alt="image counts all years" width="700" height="400">
    <p>Figure 6: Representation of the image counts from year 2016 to 2019</p>
</figure>
<figure>
<img src="figures/image_counts_all_years_individual.png" alt="image counts all years individual" width="700" height="400">
<p>Figure 7: Representation of the image counts all years (from 2016 to 2019) individually</p>
</figure>
</div>


<h4>Count of the number of images for each month</h4>

<div class="image-container">
<figure>
<img src="figures/month_counts_all_years(2016-2019).png" alt="month counts all years" width="700" height="400">
<p>Figure 8: Representation of the month counts from year 2016 to 2019</p>
</figure>
<figure>
<img src="figures/image_counts_all_years_individual.png" alt="month counts all years individual" width="700" height="400">
<p>Figure 9: Representation of the month counts all years (from 2016 to 2019) individually</p>
</figure>
</div>

<h4>Count of the number of images for each province</h4>

<div class="image-container">
<figure>
<img src="figures/province_counts_all_years(2016-2019).png" alt="province counts all years" width="700" height="400">
<p>Figure 10: Representation of the province counts from year 2016 to 2019</p>
</figure>
<figure>
<img src="figures/province_counts_all_years_individual.png" alt="province counts all years individual" width="700" height="400">
<p>Figure 11: Representation of the province counts all years (from 2016 to 2019) individually</p>
</figure>
</div>

___

### Features

- PNG files
  - RGB images
  - Vegetation indices (Notes: make tables less wide, and remove border around equation if possible?)
						
- .zip folders (RAW data) (Note for Amanda): Add Table with link to Google Earth Engine (Sentinel-2) band description.
  
___
