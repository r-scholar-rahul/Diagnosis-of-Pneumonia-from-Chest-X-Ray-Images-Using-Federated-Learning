# Datasets

This file lists datasets relevant to pneumonia detection, chest X-ray analysis, and federated medical-imaging research.

---

## 1. Chest X-Ray Images (Pneumonia)

**Type:** Chest X-ray images
**Task:** Pneumonia classification
**Classes:** Normal / Pneumonia

### Description

This dataset is commonly used for developing and evaluating deep-learning models for pneumonia classification from chest X-ray images.

### Research Application

The dataset can be used for:

* Binary pneumonia classification
* CNN training
* Transfer learning
* Model comparison
* Federated-learning simulations

### Important Note

Before using this dataset in the final repository, verify the exact dataset source, image count, licensing/access conditions, and class distribution from the original dataset provider.

**Official/Original Source:**
[Add verified source]

---

## 2. NIH ChestX-ray14

**Task:** Multi-label chest X-ray disease classification
**Image Type:** Chest radiographs

### Description

ChestX-ray14 is a large-scale chest X-ray dataset containing radiographs associated with multiple thoracic disease labels.

It is particularly relevant to federated learning because chest X-ray research can be distributed across simulated clients or institutions.

### Research Application

Potential applications include:

* Thoracic disease classification
* Federated chest X-ray classification
* Multi-label classification
* Benchmarking CNN models

**Dataset:**
https://nihcc.app.box.com/v/ChestXray-NIHCC

---

## 3. CheXpert

**Task:** Chest X-ray classification
**Image Type:** Chest radiographs

### Description

CheXpert is a large chest-radiograph dataset containing labels for multiple observations and uncertainty labels. It is widely used for research into automated chest X-ray interpretation.

### Research Application

Potential applications include:

* Chest X-ray classification
* Model benchmarking
* Multi-label disease prediction
* Federated medical-imaging experiments

**Official Dataset:**
https://stanfordmlgroup.github.io/competitions/chexpert/

---

# Dataset Comparison

| Dataset                        | Image Type | Main Task                          | Research Relevance          |
| ------------------------------ | ---------- | ---------------------------------- | --------------------------- |
| Chest X-Ray Images (Pneumonia) | CXR        | Pneumonia classification           | Directly relevant           |
| NIH ChestX-ray14               | CXR        | Multi-label disease classification | Federated CXR research      |
| CheXpert                       | CXR        | Chest-radiograph classification    | Large-scale medical imaging |

---

# Dataset Selection for This Research

The primary dataset should be selected according to:

1. Relevance to pneumonia detection
2. Availability
3. Licensing
4. Image quality
5. Class balance
6. Number of images
7. Availability of labels
8. Suitability for federated-learning simulation
9. Reproducibility

> Dataset statistics should be verified from the original dataset source before being used in experimental results.
