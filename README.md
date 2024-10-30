# Optimizers Implementation and Experiments

Welcome to the **Python and PyTorch Optimizers Implementation and Experiments** repository! In this project, I have created various optimization algorithms to help you learn how they work and how to apply them in machine learning. Through this repository, you can explore different optimizers and conduct experiments to analyze their performance.

## Table of Contents

- [Introduction](#introduction)
- [Implemented Optimizers](#implemented-optimizers)
- [Experiments](#experiments)
- [How to Start](#how-to-start)
- [Contribution](#contribution)
- [License](#license)

---

## Introduction

Optimization algorithms are crucial for effectively training machine learning models. In this repository, you will find implementations of popular optimizers and experiments designed to help you understand how different strategies influence training dynamics, model accuracy, and the impact of hyperparameters.

My goal is to enhance your programming skills while deepening your understanding of optimization techniques in machine learning.

## Experiments Overview

In this repository, you will conduct experiments that include:

- **Task**: Implementing and testing optimizers on synthetic datasets using two approaches: one with pure Python and NumPy, and the other with PyTorch.
- **Data**: Exploring how different data sizes affect model performance and training time through experiments on synthetic datasets.
- **Model**: Utilizing a simple linear regression model for all experiments.

### Skills You Will Develop
Through this project, you will gain valuable skills, including:
- Writing Python code using pure **Python** and **NumPy**.
- Implementing optimizers in **PyTorch**.
- Testing the effects of hyperparameters, such as learning rate and momentum, on model performance.
- Comparing results through experiments and visualizations.

## Implemented Optimizers

In this repository, I have implemented the following optimizers:

- **Gradient Descent (GD)**
- **Stochastic Gradient Descent (SGD)**
- **Mini-Batch Gradient Descent (Mini-BGD)**

### Optimizers Under Development

Currently, I am working on the following optimizers:

- **Momentum**
- **Adam**
- **Adagrad**
- **Nesterov Accelerated Gradient (NAG)**
- **RMSprop**

## How to Start

To get started with this repository, please follow these steps:

### Using `venv`

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/pytorch-optimizers-experiments.git
    cd pytorch-optimizers-experiments
    ```

2. Create a virtual environment:

    ```bash
    python -m venv venv
    ```

3. Activate the virtual environment:

    - On Windows:
      ```bash
      venv\Scripts\activate
      ```
    - On macOS/Linux:
      ```bash
      source venv/bin/activate
      ```

4. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

### Using `conda`

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/pytorch-optimizers-experiments.git
    cd pytorch-optimizers-experiments
    ```

2. Create a conda environment:

    ```bash
    conda create --name optimizers-env python=3.9
    ```

3. Activate the conda environment:

    ```bash
    conda activate optimizers-env
    ```

4. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

## Contribution

As this is a personal project, contributions from others are accepted. I welcome any feedback or suggestions for improvement.

## License

This repository is licensed under a **Custom License for Educational Jupyter Notebooks**. You are allowed to use the code and materials for personal learning and educational purposes, but redistribution or commercial use is strictly prohibited. For more details, please refer to the license section in the repository.

