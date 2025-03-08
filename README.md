# Kaggle Real Doppler RADAR Database

## Overview
This repository contains a Jupyter Notebook that analyzes the **Kaggle Real Doppler RADAR Database** using **Deep Learning models** such as **DenseNet** and **Vision Transformer (ViT)**. The dataset consists of **radar signal images**, classified into three categories: **People, Drones, and Cars**. The project explores data preprocessing, feature extraction, and training machine learning models on radar-based data.

## Features
- **Data Preprocessing:**
  - Reads radar images stored as **CSV files** and converts them to NumPy arrays.
  - Normalizes image data to a scale of **0-1**.
  - Resizes images from **11×61** to **64×64** for model compatibility.
- **Exploratory Data Analysis (EDA):** Visualization and distribution analysis of radar signal data.
- **Machine Learning Models:**
  - **DenseNet** for feature extraction and classification.
  - **Vision Transformer (ViT)** with **4×4 patch embeddings** (196 patches total).
- **Model Evaluation:**
  - Uses **K-Fold cross-validation** to improve generalization.
  - Tracks performance using standard evaluation metrics.

## Dataset
The dataset used in this project can be accessed from Kaggle: [Kaggle Radar Dataset](https://www.kaggle.com/)

### Structure
The dataset consists of:
- **Radar Signal Data**: Raw signals captured using Doppler radar and stored as images in CSV format.
- **Metadata**: Labels (People, Drones, Cars) and file structures.
- **Preprocessed Features**: Resized, normalized images used for model training.

## Installation
To run this notebook locally, ensure you have Python installed and set up the required dependencies.

### Dependencies
Install necessary Python packages using:
```bash
pip install transformers timm torchview numpy pandas matplotlib seaborn scikit-learn
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Kaggle_Radar_Analysis.git
   cd Kaggle_Radar_Analysis
   ```
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open `Kaggle_Real_Doppler_RADAR_database.ipynb` and execute the cells step by step.

## Results
- **Data Preprocessing Outputs**: Displays processed radar images and their class distributions.
- **Model Training**:
  - DenseNet and ViT models trained on radar data.
  - Performance evaluation using accuracy, precision, and recall.
  - **Cross-validation results** to ensure model generalization.
- **Visualization**: Patch embeddings, feature maps, and confusion matrices.

## Contributions
Contributions are welcome! Feel free to fork this repository and submit pull requests with improvements.

## License
This project is licensed under the MIT License.

## Citation
If you use this work, please cite the original dataset:
```
@dataset{KaggleRadar202X,
  author = {Kaggle Contributors},
  title = {Real Doppler RADAR Database},
  year = {202X},
  url = {https://www.kaggle.com/}
}
```

## Contact
For any questions or feedback, reach out via [GitHub Issues](https://github.com/yourusername/Kaggle_Radar_Analysis/issues).

