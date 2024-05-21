<h3 align="center">Classification of Cloud Coverage in Satellite Sentinel-3 OLCI Imagery and Sentinel-2 MSI Imagery</h3>

  <p align="center">
    GEOL0069 Major Project
    <br />


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#project outline">Project Outline</a>
      <ul>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#YouTube-Link">YouTube Link</a></li>
      </ul>
    </li>
    <li><a href="#caveats">Caveats</a></li>
    <li><a href="#conclusions">Conclusions</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- PROJECT OUTLINE -->
## Project Outline

This project aims to classify cloud cover using both supervised and unsupervised learning techniques on Sentinel-3 OLCI (Ocean and Land Colour Instrument) satellite imagery and Sentinel-2 MSI (MultiSpectral Instrument) imagery. OLCI capture images with a resolution of 300m and MSI captures images with a resolution of 10-60m. Clouds often obstruct satellite imagery, making their identification important for correctional purposes. For the supervised learning method, I will utilize IRIS, an AI tool, to manually classify pixels as 'Cloud' and 'Ocean'. Then I will use the manually classified pixels as input data for a Convolutional Neural Network (CNN) Model. For the unsupervised learning method, I will employ Gaussian Mixture Model (GMM) clustering. The study will focus on the region surrounding Chapel Hill, NC, where I attended the University of North Carolina at Chapel Hill (UNC) for my year abroad. This region features diverse geographical elements including cloud cover, ocean, and land in Sentinel-3 OLCI imagery and Urban Settings in Sentinel-2 MSI Imagery.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

1. Google Earth Engine (https://earthengine.google.com/)

2. Copernicus Dataspace (https://browser.dataspace.copernicus.eu/)

3. IRIS Software (https://github.com/ESA-PhiLab/iris)

4. Python libraries: scikit-learn, numpy, matplotlib etc...

Below is an example of how I download necessary libraries in Google Colaboratory. 

* netCDF4
  ```sh
  !pip install netCDF4
  ```
* Rasterio
  ```sh
  !pip install rasterio
  ```
### Installation

Clone the repository
   ```sh
   git clone https://github.com/shannonjames24/GEOL0069_Major_Project.git
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### YouTube Link

This link will take you to a video that explains my Google Collab code

https://youtu.be/znjWZF2qcQo

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CAVEATS -->
## Caveats

This study is region-specific, which may pose challenges when applying the methods to areas with sea ice or other unique geographical features. Although the project focuses on IRIS AI classification and GMM clustering, other supervised and unsupervised learning methods might offer higher accuracy. The accuracy of cloud cover classification will be primarily assessed through visual inspection. However, more robust evaluation methods, such as creating a confusion matrix and using ground-truth data, could provide a more comprehensive accuracy assessment.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONCLUSIONS -->
## Conclusions

This project demonstrates the effective application of both supervised and unsupervised learning methods for classifying cloud cover in satellite imagery from the Sentinel-3 OLCI and Sentinel-2 MSI sensors. The results show that the supervised method using IRIS AI classification and the unsupervised method using Gaussian Mixture Model (GMM) clustering both produce visually accurate classifications of cloud cover.

However, when applying GMM clustering to Sentinel-2 MSI imagery, urban areas are sometimes misclassified as cloud cover, particularly in smaller rollout images. In contrast, larger images classified with GMM clustering show visually accurate cloud cover. To improve accuracy, higher resolution images would benefit more from supervised learning methods to minimize mislabeling. Additionally, refining the parameters in GMM clustering could lead to more precise cloud cover classification.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Shannon James

Project Link: [https://github.com/shannonjames24/GEOL0069_Major_Project](https://github.com/shannonjames24/GEOL0069_Major_Project)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [University College London]()

<p align="right">(<a href="#readme-top">back to top</a>)</p>
