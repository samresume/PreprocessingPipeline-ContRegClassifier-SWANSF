
# Solar Flare Prediction with ContReg

This repository contains the Jupyter notebooks and related code for our study on enhancing solar flare prediction using advanced preprocessing and a novel deep learning-based classifier called ContReg on the SWAN-SF dataset.

## Overview

Accurate solar flare prediction is essential due to the potential hazards they pose to astronauts, space equipment, and satellite communication systems. This project enhances prediction accuracy through advanced preprocessing and classification methods, outperforming previous methods.

## Notebooks

1. **Part1_Reading-SWANSF-Dataset.ipynb**: This notebook covers the initial steps of reading and understanding the SWAN-SF dataset, which contains comprehensive multivariate time series data of solar active regions.

2. **Part2_Preprocessing.ipynb**: This notebook details our novel preprocessing pipeline, including missing value imputation, normalization, balanced sampling, near decision boundary sample removal, and feature selection.

3. **Part3_ContrastiveRegressionClassifier.ipynb**: This notebook demonstrates the implementation of our novel deep learning-based classifier, ContReg, which combines contrastive learning with a GRU regression model for high-accuracy prediction.

4. **Part4_FinalVisualizations.ipynb**: This notebook provides visualizations to showcase the performance of our preprocessing pipeline and classifier, comparing them to previous studies and other sequence-based deep learning architectures such as LSTM, GRU, RNN, and 1D-CNN.

## Setup and Usage

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python libraries (listed in `requirements.txt`)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/solar-flare-prediction.git
cd solar-flare-prediction
```

2. Install the required libraries:

```bash
pip install -r requirements.txt
```

### Running the Notebooks

1. **Part1_Reading-SWANSF-Dataset.ipynb**:
   - Open the notebook in Jupyter.
   - Follow the steps to read and explore the SWAN-SF dataset.

2. **Part2_Preprocessing.ipynb**:
   - Run the notebook to preprocess the data using our pipeline.

3. **Part3_ContrastiveRegressionClassifier.ipynb**:
   - Implement and train the ContReg classifier using the preprocessed data.

4. **Part4_FinalVisualizations.ipynb**:
   - Generate visualizations to compare the performance of our method with previous studies.

## Results

Our findings demonstrate exceptional True Skill Statistics (TSS) scores, exceeding previous methods and highlighting the critical role of precise data preprocessing and classifier development in time series-based solar flare prediction.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

We acknowledge the sources and tools used in this project, including the SWAN-SF dataset and the libraries utilized in our analysis.

## Contact

For any questions or issues, please contact [your email or GitHub profile].
