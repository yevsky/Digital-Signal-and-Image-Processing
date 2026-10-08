# Digital Image Processing

This project focuses on the analysis and digital processing of images in the spatial domain.

The purpose of the project was to explore and compare different image-processing techniques, including intensity transformations, histogram-based enhancement, local contextual processing, noise reduction, smoothing, edge detection, sharpening, and multi-stage image enhancement.

## Contents

The main work is presented in the Jupyter Notebook:

**`image_processing.ipynb`**

Open the notebook to see the complete analysis, including explanations, source code, visualizations, and results.

The notebook covers:

* loading grayscale images and analyzing intensity profiles;
* applying point transformations for brightness and contrast adjustment;
* performing logarithmic and gamma transformations;
* applying histogram equalization and local histogram enhancement;
* enhancing local contrast using neighborhood statistics;
* reducing salt-and-pepper noise using different spatial filters;
* comparing mean and Gaussian smoothing;
* detecting edges using the Sobel operator and Laplacian;
* sharpening images using unsharp masking and high boost filtering;
* combining multiple enhancement techniques into a multi-stage processing pipeline.

Figures and processed images generated during the analysis are automatically exported to the `outputs/` directory.

## Input Data

Input images should be placed in the `dataset/` directory.

The project uses several grayscale images for testing different processing techniques, including:

* `chest-xray.tif` — used for intensity-profile analysis and spatial processing;
* `spectrum.tif` — used for intensity and contrast transformations;
* `bonescan.tif` — used for the multi-stage image enhancement pipeline;
* additional images required by individual experiments.

For additional context and setup instructions, see the root README.

## Requirements

The project uses:

* Python
* NumPy
* SciPy
* scikit-image
* Pillow
* Matplotlib
* Jupyter Notebook

Install the required Python packages before running the notebook.

## Running the Project

1. Place the required input images in the `dataset/` directory.
2. Open `image_processing.ipynb` in Jupyter Notebook or JupyterLab.
3. Run the notebook cells to reproduce the analysis and generate the figures.
4. Generated figures and processed images will be saved in the `outputs/` directory.
