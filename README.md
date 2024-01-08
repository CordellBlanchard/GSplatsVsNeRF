## Overview

This repository presents a comparative analysis of 3D Gaussian Splatting and Instant NGP for 3D reconstruction, focusing on their performance in complex scenes and with sparse views.

## Experiment Files

### 1. Instant NGP Experiments

- **File:** `instant_ngp_experiments.ipynb`
- **Description:** Contains experiments using Instant NGP with custom datasets for reflective and transparent objects.

### 2. Gaussian Splatting Experiments

- **File:** `gaussian-splatting_experiments.ipynb`
- **Description:** Contains experiments using 3D Gaussian Splatting with custom datasets for reflective and transparent objects.

### 3. Frame Generation for 3D Views

- **File:** `image_sequence_converter.ipynb`
- **Description:** Converts videos into frames, preparing them for input into the models.

### 4. Sparse Views Creation

- **Description:** Deletes every nth image from a dataset to decrease the number of input views into a mode. This can be found in the `gaussian-splatting_experiments.ipynb` notebook.

## Results

Detailed results and analysis can be found in the project report pdf.
