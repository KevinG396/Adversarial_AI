# Analyzing and Optimizing the Robustness of Neural Networks

This repository contains the final project for **543T**, titled *"Analyzing and Optimizing the Robustness of Neural Networks"*.

We implement various types of **adversarial attacks** and corresponding **defense mechanisms**, and test their performance on different neural networks and datasets. Each `.ipynb` file corresponds to a specific attack method applied to a specific neural network and dataset, along with its defense strategy.

---

## Project Structure

- **FGSM_MLP.ipynb**  
   Implements **FGSM (Fast Gradient Sign Method)** attack on an **MLP** (Multi-Layer Perceptron) trained on the **MNIST** dataset, along with defense strategies against FGSM.

- **PGD_ResNet50.ipynb**  
   Implements **PGD (Projected Gradient Descent)** multi-step attack on a **ResNet50** model trained on the **Fashion-MNIST** dataset, along with defense strategies against PGD.

---

## How to Run

Simply run each `.ipynb` file in a Jupyter Notebook environment.  

For example:
- Run `FGSM_MLP.ipynb` for FGSM attack and defense on MNIST with MLP.
- Run `PGD_ResNet50.ipynb` for PGD attack and defense on Fashion-MNIST with ResNet50.

Executing each file will reproduce the results shown in the project report.

---

## Project Highlights

- **Attacks Implemented**: FGSM (single-step) and PGD (multi-step).  
- **Models Tested**: MLP and ResNet50.  
- **Datasets Used**: MNIST and Fashion-MNIST.  
- **Defense Strategies**: Implemented to evaluate model robustness under adversarial attacks.

---

## Acknowledgment

This project was completed as part of the **543T Final Project**.

