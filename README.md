# Smart Ambulance Traffic System (SATS) 🚑  

This repository contains the implementation of the **Smart Ambulance Traffic System (SATS)** project, designed to prioritize emergency vehicles and reduce delays in urban traffic using AI-driven systems. The project integrates two key components:  

## Features  
1. **YOLOv8 Ambulance Detection Model:**  
   - Detects ambulances in real-time from live traffic footage using the YOLOv8 algorithm.  
   - Trained on a diverse dataset of ambulance images for high accuracy.
   - For reference visit: https://docs.ultralytics.com/models/yolov8/ 

2. **Siren Detection Model:**  
   - Classifies audio inputs to detect ambulance sirens amidst urban noise.  
   - Built with TensorFlow and Librosa for audio processing and deep learning.
   - This uses a pre processing Step called MFCC - Mel Frequency Cepstral Coefficients.

## Repository Contents  
- **`Yolo_v8_training.ipynb/`**: YOLOv8 model training code and sample datasets.  
- **`Audio_model_training_testing.ipynb/`**: Audio classification model code, including training scripts and pre-processed datasets.  
- **`README.md`**: Project overview and setup instructions.  

## Prerequisites  
- Python 3.8+  
- TensorFlow, Librosa, PyTorch  
- NVIDIA GPU (for YOLOv8 training)  

## Contributions
Feel free to contribute to improving models, adding datasets, or optimizing code. Open a pull request or raise issues!

## Help make traffic smarter and save lives with AI! 😊

##License
This project is licensed under the MIT License.
