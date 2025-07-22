# AOHRSI_Final_Project
This project implements a U-Net-based deep learning pipeline for binary semantic segmentation of satellite images USING DeepGlobe road dataset. It includes custom dataset handling, combined Dice + BCE loss for optimized performance, training with early stopping and checkpointing. 

📁 Dataset

The model was trained and validated on the [DeepGlobe Road Extraction Dataset](https://www.kaggle.com/datasets/balraj98/deepglobe-road-extraction-dataset/data) available on Kaggle.  
Each image has a corresponding binary mask highlighting road areas.

# Dataset Structure
train/
├── image_001_sat.jpg
├── image_001_mask.png
├── image_002_sat.jpg
├── image_002_mask.png
...

# New Dataset
The the model was tested on a new data (Washington) that was downloaded from the NAIP geoportal

# Dataset Structure
road/
├── 000000000001.png
├── 000000000002.png
...

Download the dataset used for training and evaluation here:
👉 Download Dataset [here via Google Drive](https://drive.google.com/drive/folders/1VVSxcHAKjSvZTrMRfUmXf7sMCunfcRQY?usp=sharing)


Each image has a corresponding binary mask highlighting road areas.

🧠 Pretrained Model
Find the best model among the file in the repository (best_model_1.pt)
