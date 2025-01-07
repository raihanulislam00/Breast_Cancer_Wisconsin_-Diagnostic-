# Wisconsin Diagnostic Breast Cancer Prediction

## Overview

This project focuses on predicting breast cancer diagnoses using the Wisconsin Diagnostic Breast Cancer dataset. The dataset contains measurements from biopsied cells and their corresponding diagnoses (malignant or benign). By applying machine learning techniques, the goal is to create a predictive model for effective and accurate diagnosis.

## Dataset

The dataset originates from the University of Wisconsin Hospitals, Madison, Wisconsin, and was created by Dr. William H. Wolberg. It is a widely used benchmark in the machine learning community.

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)
- **Features**: 30 numeric features representing various characteristics of cell nuclei
- **Target**: Binary classification (malignant = 1, benign = 0)

## Installation

1. Clone the repository or download the project files.
2. Ensure you have Python installed along with the required libraries:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```

## Usage

1. Load the dataset:
   ```python
   from sklearn.datasets import load_breast_cancer
   cancer = load_breast_cancer()
   ```

2. Create a DataFrame for easier manipulation:
   ```python
   import pandas as pd
   df = pd.DataFrame(data=cancer.data, columns=cancer.feature_names)
   df['target'] = cancer.target
   ```

3. Follow the steps in the Jupyter Notebook to preprocess the data, visualize patterns, and train machine learning models.

## Features and Target

### Features
The dataset includes measurements computed from digitized images of fine needle aspirate (FNA) of breast mass. For each cell nucleus, ten real-valued features are computed:

- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness
- Concavity
- Concave points
- Symmetry
- Fractal dimension

For each feature, three values are recorded:
- Mean
- Standard error
- "Worst" or largest (mean of the three largest values)

### Target
- 0: Benign
- 1: Malignant

## Results

The trained models achieve high accuracy in classifying breast cancer diagnoses, ensuring reliable performance in medical applications. Detailed performance metrics and model comparisons can be found in the project notebook.


The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
