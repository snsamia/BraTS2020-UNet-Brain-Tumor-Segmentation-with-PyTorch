# BraTS2020-UNet: Brain Tumor Segmentation with PyTorch

This project implements a **U-Net** model in **PyTorch** for brain tumor segmentation on the [BraTS2020 dataset](https://www.kaggle.com/datasets/awsaf49/brats20-dataset-training-validation/data).  
It covers dataset preparation, model training, evaluation (Accuracy, Dice, IoU), and visualization of predictions.

---

## 📂 Project Structure
- `U-Net2.ipynb` → Main notebook with data loading, model definition, training, and evaluation  
- `README.md` → Project documentation  
- `requirements.txt` → Python dependencies  

---

## 🚀 Features
- Data loading of **BraTS2020 multimodal MRI scans (T1, T1Gd, T2, FLAIR)** in `.nii.gz` format  
- Preprocessing: normalization, skull-stripped volumes, and slice extraction  
- **U-Net architecture** built from scratch in PyTorch  
- Training & validation loops with DataLoader support  
- Model checkpoint loading for inference  
- Evaluation metrics: Accuracy, Confusion Matrix, Classification Report, Dice Score, IoU  
- Visualization of ground truth masks vs. predictions  


