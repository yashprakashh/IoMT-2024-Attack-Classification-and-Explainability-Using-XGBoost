# IoMT 2024 Attack Classification and Explainability Using XGBoost

## Overview
This project demonstrates the application of machine learning techniques to classify cyberattacks on Internet of Medical Things (IoMT) devices using the CIC IoMT 2024 dataset. The workflow involves training an XGBoost model for multiclass classification and utilizing SHAP and LIME for model interpretability.

## Project Structure
- `colab_notebooks/`: Contains the main Google Colab notebook with the implementation of the classification and explainability pipeline.
- `data_src/`: Python scripts for data processing, model training, and explainability.
- `results/`: Contains saved plots and evaluation metrics.
- `requirements.txt`: Lists the required Python packages.
- `README.md`: This file, providing an overview of the project.
- `LICENSE`: License information for the project.

## Getting Started

### Prerequisites
- Python 3.x
- Google Colab or local Jupyter environment

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yashprakashh/IoMT-2024-Attack-Classification-and-Explainability-Using-XGBoost.git
2. Navigate into the project directory:
   ```bash
   cd IoMT-2024-Attack-Classification-and-Explainability-Using-XGBoost
3. Install required packages:
   ```bash
   pip install -r requirements.txt
4. (Optional) Update pip if a newer version is available:
   ```bash
   python -m pip install --upgrade pip
5. (Optional) If you are using Jupyter, you may need to install Jupyter notebooks:
   ```bash
   pip install notebook
6. Open the notebook:
   If using Google Colab, upload and open the colab_notebooks/ notebook.
   If using Jupyter locally, run the following command to start the Jupyter notebook server:
   ```bash
   jupyter notebook
   ```
   Then open the notebook from the colab_notebooks/ directory.
