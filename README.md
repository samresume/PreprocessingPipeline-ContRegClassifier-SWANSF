
# Enhancing Solar Flare Prediction with Contrastive Learning and Multifaceted Preprocessing

Accurate solar flare prediction is essential due to the potential hazards they pose to astronauts, space equipment, and satellite communication systems. Our research enhances solar flare prediction by utilizing advanced data preprocessing and classification methods on the Space Weather Analytics for Solar Flares (SWAN-SF) dataset, which contains comprehensive multivariate time series data of solar active regions. Firstly, our study employs a novel preprocessing pipeline that includes missing value imputation, normalization, balanced sampling, near decision boundary sample removal, and feature selection to significantly boost prediction accuracy. Secondly, we combine contrastive learning with a GRU regression model to develop a novel classifier with high accuracy, thereby further improving prediction performance. To validate the effectiveness of our preprocessing pipeline, we compare and show the performance gain of each step, and to demonstrate the effectiveness of our novel classifier, we compare it to sequence-based deep learning architectures, including LSTM, GRU, RNN, and 1D-CNN, along with previous studies. Our findings demonstrate exceptional True Skill Statistics (TSS) scores, exceeding previous methods and highlighting the critical role of precise data preprocessing and classifier development in time series-based solar flare prediction.

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

This project is licensed under the MIT License.

