# Skin Lesion Notebooks

Experimental notebooks and analysis for multi-class skin lesion classification using CNN and Transformer-based models.

---

## Overview

This repository contains Jupyter notebooks used for:

* Data exploration and visualization
* Model training and experimentation
* Performance comparison
* Result analysis

It uses the core implementation from the `skin-lesion-project` repository.

---

## Usage

This project depends on the core package:

```
conda activate skin-lesion-notebooks
cd skin-lesion-project
python setup.py develop
pip install -e .

```
---

## Dataset

* ISIC 2018 Skin Lesion Dataset
* Multi-class classification (8 classes)

---

## Experiments

* Training from scratch vs pretrained models
* CNN vs Transformer comparison
* Evaluation using:

  * Accuracy
  * Macro F1-score
  * Balanced Accuracy

---

## Results

Results include:

* Performance comparison tables
* Confusion matrices
* Training curves
* Class-wise analysis

---

## Objective

To conduct a structured and reproducible experimental study comparing deep learning architectures for skin lesion classification.

---

## License

For academic and research use only.
