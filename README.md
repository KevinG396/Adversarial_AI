# Analyzing and Optimizing the Robustness of Neural Networks

Various types of **adversarial attacks** and corresponding **defense mechanisms** are implemented in this project, and their performance on different neural networks and datasets are tested. Each `.ipynb` file corresponds to a specific attack method applied to a specific neural network and dataset, along with its defense strategy.

---

## Project Structure

- **AttackMethod_NeuralNetwork.ipynb**  
   Implements **FGSM or PGD** attack on a neural network (MLP, AlexNet or ResNet50) trained on the **MNIST or Fashion-MNIST** dataset, along with defense strategies.


---

## How to Run

Simply run each `.ipynb` file in a Jupyter Notebook environment.  

For example:
- Run `FGSM_MLP.ipynb` for FGSM attack and defense on MNIST with MLP.
- Run `PGD_ResNet50.ipynb` for PGD attack and defense on Fashion-MNIST with ResNet50.

You can change the attack coefficients--epsilon in each file to see the differences. Executing each file will reproduce the results shown in the project report.

---

## Project Highlights

- **Attacks Implemented**: FGSM (single-step) and PGD (multi-step).  
- **Models Tested**: MLP, AlexNet and ResNet50.  
- **Datasets Used**: MNIST and Fashion-MNIST.  
- **Defense Strategies**: Implemented to evaluate model robustness under adversarial attacks.

---

