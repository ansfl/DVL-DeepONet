# DVL-DeepONet

[![arXiv](https://img.shields.io/badge/arXiv-2606.23502-b31b1b.svg)](https://arxiv.org/abs/2606.23502)

Official implementation of:

**DVL-DeepONet: A Physics-Guided Operator Learning for Resilient Underwater Navigation**

DVL-DeepONet is a physics-guided operator-learning framework for robust Doppler Velocity Log (DVL) velocity estimation in Autonomous Underwater Vehicles (AUVs). The framework integrates Deep Operator Networks with DVL measurement physics to provide velocity estimation of AUV under noisy measurements, DVL-only operation, and partial beam-outage conditions.

This repository contains three Jupyter notebook versions of DVL-DeepONet for estimating velocity vector from DVL measurements, with  baseline comparisons.

<p align="center">
  <img src="figures/dvl_deeponet_architecture.png" width="900">
</p>



## Files

- `main_DVL-DeepONet_I.ipynb`  
  DVL-DeepONet using DVL and IMU inputs.

- `main_DVL-DeepONet_II.ipynb`  
  DVL-DeepONet using DVL-only velocity estimation.

- `main_DVL-DeepONet_III.ipynb`  
  Additional DVL-DeepONet experiment/version.

## Description

DVL-DeepONet is a neural-network-based approach for learning velocity from DVL beam measurements. The notebooks include data loading, preprocessing, model training, evaluation, and visualization.


## Usage

Open any notebook in Jupyter Notebook, JupyterLab, or Google Colab and run the cells in order.

## Author

Arup Kumar Sahoo and Itzik Klein
