# MNIST-Dataset-Visualization
This repository contains a Jupyter notebook that demonstrates how to download, load, and visualize the MNIST dataset using PyTorch and Matplotlib. The notebook is a simple example of working with a classic machine learning dataset.

Project Description

The purpose of this notebook is to provide a clear and simple demonstration of a data exploration step for the MNIST dataset. The script downloads the dataset and then generates a visualization of a small sample of images for each of the 10 digits (0-9).

How to Run the Notebook

To run this notebook, you will need to have a Python environment with the necessary libraries installed.

Prerequisites

    Python 3

    Jupyter Notebook or JupyterLab

Dependencies

The following Python libraries are required to run the code:

    torch: A powerful open-source machine learning framework.

    torchvision: A package in the PyTorch ecosystem that provides access to popular datasets, models, and image transformations.

    matplotlib: A plotting library for creating static, animated, and interactive visualizations in Python.

The notebook consists of two main code blocks:

    Dataset Download: This cell imports torchvision and downloads the MNIST dataset to the specified dataset_path.

    Visualization: This cell loads the downloaded dataset and uses matplotlib to plot five sample images for each of the 10 digits (0-9). It creates a 10x5 grid of grayscale images to show the different handwritten digits.

Output

When you run the notebook, the final cell will display a grid of 50 images, showing five examples for each digit from 0 to 9. The plot is generated dynamically from the dataset to provide a clear visual of the data you are working with.
