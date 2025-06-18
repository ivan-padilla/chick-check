# Chick-Check: Design and Development of a Feather Sexing Machine for Chicks Using YOLOv10 and UV Optical System

## Overview  
This repository contains the dataset and training pipeline used in our research, *Chick-Check: Design and Development of a Feather Sexing Machine for Chicks Using YOLOv10 and UV Optical System*, presented at the **2024 IEEE HNICEM** conference.
It includes a **cleaned and labeled dataset** of chick images captured under ultraviolet (UV) light, as well as a **Jupyter Notebook** that demonstrates training a YOLOv10 model for feather-based sex classification.

### Contents  
- `dataset/` – Labeled images of chicks under UV light, organized for object detection.  
- `YOLOv10_1.ipynb` – Jupyter Notebook for training YOLOv10 on the chick dataset.  

## Dependencies  
Please install the following libraries and tools before running the notebook:
- `ultralytics` – For YOLOv10 model training and inference.  

## How to Use  
1. Clone this repository and navigate to the folder.  
2. Open `YOLOv10_1.ipynb` in your Jupyter environment (I used Google Colab).  
3. Load the chick dataset.  
4. Train the YOLOv10 model using Ultralytics API.  
5. Evaluate model performance using provided plots and metrics.  
6. Use the trained model for inference on new UV chick images.

## Research Context  
This model plays a core role in our thesis on developing an **automated feather sexing machine** for chicks. The combination of YOLOv10’s real-time detection accuracy and UV light’s enhanced visibility of feather traits significantly improves the speed and reliability of chick sex classification.  

Presented in:  
🔬 *2024 IEEE International Conference on Humanoid, Nanotechnology, Information Technology, Communication and Control, Environment and Management (HNICEM)*
