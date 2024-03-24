# MOFCGCNN Synthetic Data Generation

This repository contains a Jupyter Notebook (`notebook.ipynb`) for synthesizing synthetic data for MOFCGNN (Metal-Organic Framework Graph Neural Network) models. The goal is to replace occurrences of 'data' or 'real_data' with the dataframe.

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
2. Replace instances of 'train'  with the dataframe name( which contains train,test,validation)
3. <b> we need to find a way and address the issue of creating a unique yet constant ID for the dataframe to align with the `.cif` files we have in the database.</b>
4. Follow the notebook instructions to synthesize the data for MOFCGNN.

## Note

Ensure you have the necessary dependencies installed in your virtual environment before running the notebook. For any questions or issues, refer to the notebook comments or reach out to me please
