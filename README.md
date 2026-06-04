# SwaraNet: Indian Classical Music Emotion and Instrument Classification

This repository contains the implementation of **SwaraNet**, a dual-task deep learning framework for simultaneous emotion recognition and instrument classification in Indian classical instrumental music.

## Overview

SwaraNet combines AudioNet-based feature extraction with Bi-GRU temporal modeling and attention mechanisms to jointly classify:

### Instrument Classes

* Flute
* Tabla
* Veena
* Violin

### Emotion Classes

* Calm
* Happy
* Relax
* Sad

## Repository Structure

```text
.
├── baselines/
├── configs/
├── data/
├── notebooks/
├── results/
├── src/
├── README.md
├── LICENSE
└── .gitignore
```

## Dataset

The experiments were conducted using the **Indian Classical Instrument Music Emotion Dataset**.

The dataset contains audio clips from four Indian classical instruments and four emotion categories.

## Experimental Configuration

* Framework: TensorFlow / Keras
* Input Representation: Mel-Spectrograms
* Random Seed: 42
* Optimizer: Adam
* Batch Size: 32
* Epochs: 20

Complete hyperparameter settings are provided in:

```text
configs/hyperparameters.yaml
```

## Reproducibility Resources

The repository contains:

* Kaggle notebook implementation
* Hyperparameter configuration
* Annotation protocol
* Dataset metadata structure
* Baseline model descriptions
* Experimental result documentation

Notebook:

```text
notebooks/swarna-lakshmi-paper2.ipynb
```

Annotation protocol:

```text
data/annotation_protocol.md
```

## Results

The results directory contains information related to:

* Emotion classification
* Instrument classification
* Confusion matrices
* ROC curves
* Training and validation performance

## Citation

If you use this work, please cite the corresponding SwaraNet publication.

## Contact

For questions regarding the implementation or dataset preparation, please contact the authors.
