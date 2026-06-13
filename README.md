# Pediatric Appendicitis Multimodal AI

Leakage-aware multimodal machine learning framework integrating clinical assessment, laboratory biomarkers, and ultrasound information for pediatric appendicitis diagnosis.

## Authors

* Mahbubul Islam
* Ainur Yerkos
* Zhandos Buribayev

## Overview

This repository contains the code used to develop and evaluate multiple machine learning approaches for pediatric appendicitis diagnosis using the publicly available Pediatric Appendicitis Dataset.

The study evaluates:

1. Image-only ultrasound model
2. Clinical and laboratory model
3. Radiologist-derived ultrasound feature model
4. Multimodal fusion framework integrating clinical and imaging information

The workflow emphasizes:

* Patient-level leakage prevention
* Explainable machine learning
* Calibration analysis
* Decision curve analysis
* Reproducible evaluation

## Repository Contents

### 01_image_only_model.ipynb

Image-only ultrasound classification using transfer learning.

### 02_clinical_lab_model.ipynb

Clinical and laboratory prediction model using structured patient information.

### 03_ultrasound_feature_model.ipynb

Radiologist-derived ultrasound feature model using structured imaging findings.

### 04_multimodal_fusion_model.ipynb

Multimodal fusion framework combining clinical and imaging information.

## Dataset

This study uses the publicly available Pediatric Appendicitis Dataset:

https://zenodo.org/records/7669442

Patient-level data are not redistributed through this repository.

## Reproducibility

Install dependencies:

pip install -r requirements.txt

Run notebooks in numerical order.

## Citation

Citation information will be updated upon publication.

## License

MIT License.
