# Tools and Libraries

## 1. PyTorch

**Category:** Deep Learning Framework

**Purpose:**
PyTorch is a machine-learning framework commonly used for developing and training neural networks.

**Use in this research:**

* CNN development
* Transfer learning
* Chest X-ray classification
* VGG/ResNet implementation
* Model evaluation

**Official Website:**
https://pytorch.org/

---

## 2. TensorFlow

**Category:** Deep Learning Framework

**Purpose:**
TensorFlow provides tools for developing, training, and evaluating machine-learning and deep-learning models.

**Use in this research:**

* CNN development
* Image classification
* Model training
* Integration with TensorFlow Federated

**Official Website:**
https://www.tensorflow.org/

---

## 3. TensorFlow Federated

**Category:** Federated Learning Framework

**Purpose:**
TensorFlow Federated (TFF) is an open-source framework for machine learning and computation on decentralized data.

**Use in this research:**

* Federated learning simulation
* Client/server experiments
* Federated model aggregation
* Evaluation of federated algorithms

**Official Documentation:**
https://www.tensorflow.org/federated

---

## 4. Flower

**Category:** Federated Learning Framework

**Purpose:**
Flower is a federated-learning framework designed to bring existing machine-learning workloads into federated settings.

**Use in this research:**

* Federated CNN training
* Multi-client experiments
* PyTorch/TensorFlow integration
* Testing FL strategies

**Official Documentation:**
https://flower.ai/docs/

**GitHub:**
https://github.com/flwrlabs/flower

---

## 5. OpenFL

**Category:** Federated Learning Framework

**Purpose:**
OpenFL is a Python library for federated learning that allows organizations to collaboratively train or evaluate machine-learning models without sharing sensitive information.

**Use in this research:**

* Distributed medical AI
* Federated training
* Privacy-aware collaboration
* Healthcare research

**Documentation:**
https://openfl.readthedocs.io/

---

# Tool Comparison

| Tool                 | Main Purpose       | PyTorch | TensorFlow | Federated Learning |
| -------------------- | ------------------ | ------: | ---------: | -----------------: |
| PyTorch              | Deep learning      |       ✓ |          — |                  — |
| TensorFlow           | Deep learning      |       — |          ✓ |                  — |
| TensorFlow Federated | Federated learning |       — |          ✓ |                  ✓ |
| Flower               | Federated learning |       ✓ |          ✓ |                  ✓ |
| OpenFL               | Federated learning |       ✓ |          ✓ |                  ✓ |

---

# Recommended Tools for This Research

For a student implementation, a practical combination is:

**PyTorch + Flower**

or

**TensorFlow + TensorFlow Federated**

The choice should depend on the model implementation and experimental requirements.
