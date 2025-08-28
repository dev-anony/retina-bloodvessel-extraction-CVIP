# Retinal Blood Vessel Extraction
(The Project is incomplete)
## Overview

This project focuses on **extraction and segmentation of blood vessels from retinal fundus images** using Computer Vision and Image Processing techniques.  

The main objective is to assist in **early diagnosis of eye-related diseases** such as Diabetic Retinopathy, Glaucoma, and Hypertension.

## Features

- Preprocessing of retinal fundus images (grayscale conversion, normalization, enhancement).
- Extraction of blood vessels using **classical CVIP techniques** (filters, morphological operations, thresholding).
- Segmentation results highlighting vessel structures.
- Modular Jupyter Notebooks for different tasks:

  - `blood_vessels.ipynb` → Blood vessel extraction  
  - `exulatecell.ipynb` → Exudate cell detection  
  - `OD.ipynb` → Optic disc localization  

  
## Project Structure

├── blood_vessels.ipynb # Extraction of retinal blood vessels
├── exulatecell.ipynb # Exudate detection
├── OD.ipynb # Optic Disc localization
├── results/ # Output images and masks
└── README.md


## Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib
- Scikit-Image

## Dataset

The project uses publicly available retinal fundus image datasets such as:
- **DRIVE** (Digital Retinal Images for Vessel Extraction)  
- **STARE** (Structured Analysis of the Retina)  
- **DIARETDB1**    

> Please download datasets from their official sources.

## How to Run

1. Clone the repository:

  ```
   bash

   git clone https://github.com/dev-anony/retina-bloodvessel-extraction-CVIP.git

   cd retina-bloodvessel-extraction-CVIP

  ```

2. Install dependencies:

`pip install -r requirements.txt`

  3.Open Jupyter Notebook:

  `jupyter notebook

3. Run `blood_vessels.ipynb` to start the extraction process.

## Applications

- Early detection of **Diabetic Retinopathy**
- Ophthalmic disease research
- Automated medical diagnostic tools

## Future Work

- Improve the Algorithm
- Fix the irregularities in BloodVessel Extraction
- Find Correct Scale for the output Image