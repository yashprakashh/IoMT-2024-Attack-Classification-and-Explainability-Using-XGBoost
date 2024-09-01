# IoMT-2024-Attack-Classification-and-Explainability-Using-XGBoost
Overview
This project demonstrates the application of machine learning techniques to classify cyberattacks on Internet of Medical Things (IoMT) devices using the CIC IoMT 2024 dataset. The workflow involves training an XGBoost model for multiclass classification and utilizing SHAP and LIME for model interpretability.

Project Structure
colab_notebooks/: Contains the main Google Colab notebook with the implementation of the classification and explainability pipeline.
data/: Includes dataset files and descriptions.
src/: Python scripts for data processing, model training, and explainability.
results/: Contains saved plots and evaluation metrics.
requirements.txt: Lists the required Python packages.
README.md: This file, providing an overview of the project.
LICENSE: License information for the project.
Getting Started
Prerequisites
Python 3.x
Google Colab or local Jupyter environment
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/IoMT-2024-Attack-Classification-Explainability.git
Install required packages:
bash
Copy code
pip install -r requirements.txt
Usage
Open the Google Colab notebook IoMT_2024_Attack_Classification_Explainability.ipynb from the colab_notebooks/ directory.
Follow the instructions in the notebook to load the dataset, train the XGBoost model, and generate explainability plots using SHAP and LIME.
Data
The dataset used in this project is the CIC IoMT 2024 dataset, which includes traffic data from IoMT devices with various attack scenarios. Data is organized into directories for different attack types and device protocols.

Results
SHAP Summary Plot: Visualizes global feature importance and impact on model predictions.
LIME Explanations: Provides local explanations for individual predictions.
License
This project is licensed under the MIT License. See the LICENSE file for more details.

Contact
For any questions or feedback, please contact
