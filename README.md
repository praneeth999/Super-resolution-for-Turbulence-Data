# Super-resolution-for-Turbulence-Data


This code is to create super-resolution models capable of reconstructing high-resolution versions of low-resolution 2D flowfield images. The key of my model is to enhance resolution while preserving fine details and structures, which is essential for maintaining the accuracy of simulations and analyses.

## Dataset

The dataset used for this model contains pairs of low-resolution and high-resolution 2D slices of 3D direct numerical simulation data. These flowfields are represented as four channels, including density and three velocity components. The dataset is used in this model is from the Kaggle 2023 Flame AI challenge.

## Evaluation Metric

The metric used for this model are Mean Squared Error (MSE), Structural Similarity Index (SSIM) of pixels and subgrid-scale stress evaluations 

