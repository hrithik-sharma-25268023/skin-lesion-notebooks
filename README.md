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

## Dependency

This project depends on the core package:

```
skin-lesion-project
```


## Project Structure

```
notebooks/
│
├── 01_eda.ipynb                  # Data exploration
├── 02_cnn_training.ipynb         # CNN experiments
├── 03_transformer_training.ipynb # Transformer experiments
└── 04_comparison.ipynb           # Model comparison
```

---

## Dataset

* ISIC 2018 Skin Lesion Dataset
* Multi-class classification (7 classes)

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

## Note

This repository focuses on experimentation and analysis. All core implementations are maintained separately in the core repository.

---

## License

For academic and research use only.
