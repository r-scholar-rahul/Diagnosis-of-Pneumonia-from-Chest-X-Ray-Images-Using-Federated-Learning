# GitHub Implementations

This file contains existing GitHub repositories relevant to federated learning, chest X-ray analysis, pneumonia classification, and medical imaging.

> Repositories should be evaluated for documentation, source-code availability, maintenance, reproducibility, examples, licensing, and relevance before final submission.

---

## 1. CXR-FL

**Repository:**
https://github.com/SanoScience/CXR-FL

**Title:**
CXR-FL: Deep Learning-based Chest X-ray Image Analysis Using Federated Learning

**Authors:**
Filip Ślazyk, Przemysław Jabłecki, Aneta Lisowska, Maciej Malawski, Szymon Płotka

**Description:**
This repository implements chest X-ray image analysis using federated learning. It was associated with the International Conference on Computational Science (ICCS) 2022.

**Why it is relevant:**
This is one of the most directly relevant implementations because it specifically combines chest X-ray analysis and federated learning.

**Repository evidence:**
The repository contains classification and segmentation components and reports experiments examining federated-learning parameters and model generalizability.

---

## 2. FL for Smart Healthcare

**Repository:**
https://github.com/BThameur/FL-for-Smart-Healthcare

**Description:**
This project investigates federated learning in smart healthcare using multiple medical datasets, including a pneumonia dataset.

**Federated Strategies:**

* FedAdam
* FedAdagrad
* FedProx
* FedAvg

**Datasets include:**

* Brain tumor
* Pneumonia
* Alzheimer's disease
* COVID-19

**Why it is relevant:**
The repository directly demonstrates federated-learning experiments involving pneumonia data.

---

## 3. Federation-X

**Repository:**
https://github.com/niranjanxprt/federation-x

**Description:**
A privacy-preserving federated-learning project for NIH Chest X-ray classification.

**Main Concept:**
Models are trained locally at participating clients/hospitals while model updates are shared rather than the original chest X-ray data.

**Why it is relevant:**
It directly connects federated learning, chest X-ray classification, privacy, and medical imaging.

---

## 4. Federated Learning over IoMT

**Repository:**
https://github.com/Arjun-08/Federated-learning-over-IOMT

**Description:**
This project demonstrates federated learning using a ResNet-34 model for chest X-ray image classification.

**Framework:**
PyTorch / torchvision

**Dataset:**
NIH Chest X-ray dataset

**Why it is relevant:**
It provides an example of using a deep CNN architecture with federated learning for chest X-ray images.

---

## 5. Medical Imaging Federated Learning Workflow

**Repository:**
https://github.com/pegasus-isi/medical-imaging-fl-workflow

**Description:**
An end-to-end federated-learning workflow for medical imaging using Pegasus workflow management.

**Features:**

* Per-client local training
* Server-side aggregation
* Federated-learning rounds
* Medical imaging datasets
* Flower strategies
* FedAvg
* FedProx
* Reproducibility and provenance

**Why it is relevant:**
The workflow demonstrates how federated-learning experiments can be organized and reproduced across medical-imaging datasets.

---

# Additional Framework Repository

## TensorFlow Federated

**Repository:**
https://github.com/google-parfait/tensorflow-federated

**Purpose:**
Open-source framework for machine learning and computation on decentralized data.

**Why it is relevant:**
Useful for implementing and experimenting with federated-learning algorithms.

---

# Repository Evaluation Checklist

Before including a GitHub project in the final research repository, check:

* [ ] Repository is accessible
* [ ] Source code is available
* [ ] README is understandable
* [ ] Research objective is clear
* [ ] Dataset is identified
* [ ] Model/framework is identified
* [ ] Examples are available
* [ ] Project has meaningful documentation
* [ ] Recent activity is checked
* [ ] License is checked
* [ ] Connection to a research paper/project is identified
* [ ] Repository is genuinely relevant to this research

---

# Recommended Priority

| Priority | Repository                   | Direct Relevance |
| -------: | ---------------------------- | ---------------- |
|        1 | CXR-FL                       | Very High        |
|        2 | FL for Smart Healthcare      | Very High        |
|        3 | Federation-X                 | Very High        |
|        4 | Federated Learning over IoMT | High             |
|        5 | Medical Imaging FL Workflow  | High             |
