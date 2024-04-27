# MOFCGCNN Synthetic Data Generation

This repository contains a Jupyter Notebook (`notebook.ipynb`) for synthesizing synthetic data for MOFCGNN (Metal-Organic Framework Graph Neural Network) model project we are working on. 
<p>
The primary purpose of Synthetic Data Vault (SDV) models is to generate synthetic data that mimics the statistical properties of the real data. While SDV models can replicate the structure and distribution of the features in the real dataset, they are not designed to accurately capture the relationships between variables or predict a dependent variable.
 </p>


<h3>Here are five examples where synthetic data generation can be useful:</h3>

1. **Privacy Protection**: Synthetic data can be used to maintain privacy in sensitive datasets by creating new data that mimic the statistical properties of the original data, without containing any identifiable information.

2. **Data Augmentation**: In situations where the dataset is small, synthetic data can be used to augment the dataset, providing more data for training machine learning models.

3. **Testing Database Systems**: Synthetic data can be used to test the performance and scalability of database systems, simulating large databases.

4. **Anomaly Detection**: Synthetic data can be used to create datasets with known anomalies, useful for testing the performance of anomaly detection algorithms.

5. **Filling Missing Data**: Synthetic data can be used to fill in missing values in a dataset, providing a complete dataset for analysis or model training.

Visit  <a href='https://sdv.dev/'>Here</a> to learn more




## Setup

1. Create a virtual environment using `venv` with the provided `requirements.txt` file.
   ```bash
   python -m venv mofcgnn_env
   source mofcgnn_env/bin/activate  # For Linux/macOS
   ./mofcgnn_env/Scripts/activate   # For Windows
   pip install -r requirements.txt
   ```

## Usage

1. Open `notebook.ipynb` in Jupyter Notebook or JupyterLab.
2. Follow the notebook instructions to synthesize the data for MOFCGNN.
3. In doubt of anything read the docs of SDV (things are likely to change in the future)

## Note

Ensure you have the necessary dependencies installed in your virtual environment before running the notebook. For any questions or issues, refer to the notebook comments or reach out to me please
