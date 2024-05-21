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
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
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

4. Python libraries: scikit-learn, numpy, matplotlib

Below is an example of how I download necessary libraries in Google Collaborate. 

* netCDF4
  ```sh
  !pip install netCDF4
  ```
* Rasterio
  ```sh
  !pip install rasterio
  ```
### Installation

Clone the repo
   ```sh
   git clone https://github.com/shannonjames24/GEOL0069_Major_Project.git
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

This project can be used to see how unsupervised learning techniques can be applied to EO image and altimetry data to classify sea ice and lead.

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
