# 🌍 Land Use Classification with Aerial Imagery using PyTorch

This project trains a Convolutional Neural Network (CNN) in **PyTorch** to classify aerial images into different land use categories using the **EuroSAT RGB Dataset**.

## 📌 Objective

Classify satellite images into 10 land-use classes:
- AnnualCrop
- Forest
- HerbaceousVegetation
- Highway
- IndustrialBuildings
- Pasture
- PermanentCrop
- ResidentialBuildings
- River
- SeaLake

## 📂 Dataset

**EuroSAT RGB dataset**: 27,000 labeled 64×64 RGB satellite images.
- Source: [Zenodo.org](https://zenodo.org/record/7711810)
- Format: Folder with 10 subfolders (one for each class)

## 🛠️ Tools & Libraries Used

- Python
- PyTorch
- Torchvision
- Matplotlib
- scikit-learn
- Seaborn
- Google Colab or Jupyter Notebook

## 🧠 Model

A simple CNN architecture with:
- 2 Convolutional layers
- 2 MaxPooling layers
- 2 Fully connected layers
- ReLU activations & Dropout

## 🔁 Workflow

1. Download and unzip the dataset
2. Preprocess and normalize the images
3. Split into training and validation sets (80/20)
4. Train CNN using cross-entropy loss and Adam optimizer
5. Evaluate using accuracy and confusion matrix
6. Visualize predictions

## 📊 Results

- Validation Accuracy: ~ (write your accuracy here after training, e.g. 85%)
- Confusion matrix and prediction visualizations included.

## ▶️ How to Run

1. Clone this repository:
```bash
git clone https://github.com/buildinglogic/landuse-app-aereo
cd landuse-app-aereo
