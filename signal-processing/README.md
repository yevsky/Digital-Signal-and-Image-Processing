# ECG Signal Processing

This project focuses on the analysis and digital processing of electrocardiogram (ECG) signals in both the time and frequency domains.

The purpose of the project was to showcase the ECG signal processing techniques, including signal visualization, Fourier transform analysis, inverse signal reconstruction, frequency-spectrum analysis, and digital filtering. The project also demonstrates how sampling frequency and frequency-domain characteristics affect the representation and processing of ECG signals.

## Contents

The main work is presented in the Jupyter Notebook:

**`ecg_signal_processing.ipynb`**

Open the notebook to see the complete analysis, including explanations, source code, visualizations, and results.

The notebook covers:

* loading and visualizing ECG recordings;
* analyzing periodic signals using the Fast Fourier Transform (FFT);
* examining ECG signals in the frequency domain;
* reconstructing signals using the inverse FFT;
* analyzing noisy ECG recordings;
* designing and applying Butterworth digital filters;
* reducing high-frequency interference and baseline drift;
* comparing signals before and after filtering.

Figures generated during the analysis are automatically exported to the `outputs/` directory.

## Input Data

Input ECG recordings should be placed in the `signals/` directory.

The project uses the following recordings:

* `ekg1.txt` — 12 ECG leads sampled at 1000 Hz;
* `ekg100.txt` — a single ECG lead sampled at 360 Hz;
* `ekg_noise.txt` — a noisy ECG signal sampled at 360 Hz.

For additional context and setup instructions, see the root README.

## Requirements

The project uses:

* Python
* NumPy
* SciPy
* Matplotlib
* Jupyter Notebook

Install the required Python packages before running the notebook.

## Running the Project

1. Place the ECG recordings in the `signals/` directory.
2. Open `ecg_signal_processing.ipynb` in Jupyter Notebook or JupyterLab.
3. Run the notebook cells to reproduce the analysis and generate the figures.
4. Generated figures will be saved in the `outputs/` directory.
