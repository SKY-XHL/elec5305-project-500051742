# A Comparative Study of Audio Feature Representations for Environmental Sound Classification

## Research Question

How do different audio feature representations affect environmental sound classification performance?

## Project Overview

This ELEC5305 research project investigates how different audio feature representations influence environmental sound classification performance. The project will compare commonly used representations under a controlled classification pipeline to examine their effectiveness and computational requirements.

## Dataset

The project will use the ESC-50 dataset, a publicly available benchmark containing 2,000 five-second environmental audio recordings across 50 sound classes.

Official dataset repository:

https://github.com/karolpiczak/ESC-50

The dataset will not be stored in this repository. Instructions for downloading and preparing the dataset will be provided separately.

## Proposed Feature Representations

The initial comparison will include:

- Mel-Frequency Cepstral Coefficients (MFCC)
- Log-Mel spectrogram features
- Handcrafted spectral features, if time permits

## Proposed Methodology

The audio recordings will be processed using a consistent preprocessing pipeline. Each feature representation will be evaluated using the same classification method to reduce the influence of unrelated model differences.

The initial classifier will be a Support Vector Machine with a radial basis function kernel. Evaluation will follow the official five-fold structure provided by ESC-50.

## Evaluation Metrics

The proposed evaluation metrics include:

- Classification accuracy
- Macro-F1 score
- Confusion matrix
- Feature extraction time
- Model training and inference time

## Tools

The project is expected to use:

- Python
- Jupyter Notebook
- Librosa
- NumPy and Pandas
- Scikit-learn
- Matplotlib and Seaborn

## Current Progress

- [x] Project topic selected
- [x] Research question defined
- [x] Public GitHub repository created
- [x] Initial dataset selected
- [ ] Literature review
- [ ] Project proposal
- [ ] Feature extraction implementation
- [ ] Classification experiments
- [ ] Evaluation and final report

## Reference

Piczak, K. J. (2015). ESC: Dataset for Environmental Sound Classification. *Proceedings of the 23rd ACM International Conference on Multimedia*, 1015-1018. https://doi.org/10.1145/2733373.2806390
