# Clustering on UNSW-NB15 Dataset

This project implements clustering analysis on the UNSW-NB15 network intrusion dataset.

## Overview

The UNSW-NB15 dataset is a network traffic dataset containing normal and attack traffic samples. This project applies clustering techniques to analyze and group network traffic patterns.

## Dataset

The dataset used is the UNSW-NB15 dataset, which contains:
- Network traffic flow features
- Attack and normal traffic labels
- 49 features including protocol, service, state, and various network metrics

## Features

- Data cleaning and preprocessing
- Handling missing values
- Categorical encoding (Label Encoding)
- Feature scaling (StandardScaler)
- Clustering analysis and visualization

## Files

- `Clustering2.ipynb` - Main Jupyter notebook containing the clustering analysis

## Dependencies

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

## Installation

1. Clone this repository
2. Install required packages:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Usage

Run the Jupyter notebook `Clustering2.ipynb` to execute the clustering analysis:

```bash
jupyter notebook Clustering2.ipynb
```

## Author

[Your Name/Organization]

## License

This project is open source and available under the MIT License.
