# Cancer-Subtype-Classification
## Overview
This project aims to improve the classification accuracy of cancer subtypes through advanced machine learning techniques. Utilizing the gene expression data from the TCGA PAN cancer project, this repository contains methods for robust data preprocessing, feature selection, and classification algorithms to enhance the personalization of cancer treatment.

## Motivation
Identifying accurate cancer subtypes is crucial for personalized cancer treatment. Our project leverages machine learning to overcome the challenges of overlapping clusters in subtype classification, thus improving treatment strategies and outcomes.

## Dataset
dataset download link:
https://archive.ics.uci.edu/dataset/401/gene+expression+cancer+rna+seq

The dataset consists of gene expression data for 800 patients across five cancer types: breast, lung, kidney, colon, and prostate. This data is sourced from the TCGA PAN cancer project.

- **data.csv**: Gene expression data with 20532 columns.
- **labels.csv**: Corresponding labels for each patient.

## Installation
Clone the repository and install the required packages:

```bash
git clone https://github.com/your-username/cancer-subtype-classification.git
cd cancer-subtype-classification
pip install -r requirements.txt
