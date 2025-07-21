# AOHRSI_Final_Project
This project implements a U-Net-based deep learning pipeline for binary semantic segmentation of satellite images USING DeepGlobe road dataset. It includes custom dataset handling, combined Dice + BCE loss for optimized performance, training with early stopping and checkpointing. 

📁 Dataset
# Dataset Structure
train/
├── image_001_sat.jpg
├── image_001_mask.png
├── image_002_sat.jpg
├── image_002_mask.png
...

Download the dataset used for training and evaluation here:
👉 Download Dataset 'https://drive.google.com/drive/folders/1VVSxcHAKjSvZTrMRfUmXf7sMCunfcRQY?usp=sharing'

Each image has a corresponding binary mask highlighting road areas.

🧠 Pretrained Model
Find the best model among the file in the repository (best_model_1.pt)
