# 👤 Celebrity Face Recognition Using ResNet-18
 
## 📌 Project Overview
 
This project focuses on celebrity face recognition using transfer learning with a pre-trained ResNet-18 architecture.
 
The model was fine-tuned on a custom dataset containing images of five well-known public figures:
 
- Bill Gates
- Elon Musk
- Jeff Bezos
- Mark Zuckerberg
- Steve Jobs
 
The primary objective was to develop a highly accurate image classification model capable of recognizing celebrities from facial images.
 
---
 
## 🎯 Project Objectives
 
- Explore transfer learning techniques
- Fine-tune a pre-trained ResNet-18 model
- Build a custom face recognition dataset
- Train and evaluate a deep learning model
- Measure classification performance on unseen images
 
---
 
## 📊 Dataset
 
The dataset contains images of the following individuals:
 
- Bill Gates
- Elon Musk
- Jeff Bezos
- Mark Zuckerberg
- Steve Jobs
 
The dataset was split into training and validation subsets for model development and evaluation.
 
### Dataset Download
 
https://drive.google.com/file/d/120xqh0mYtYZ1Qh7vr-XFzjPbSKivLJjA/view?pli=1
 
---
 
## 🧠 Deep Learning Approach
 
The project uses:
 
- Transfer Learning
- ResNet-18
- PyTorch
- Image Classification
- Data Augmentation
- Model Fine-Tuning
 
A pre-trained ResNet-18 network was adapted and trained on the custom celebrity dataset to improve recognition performance.
 
---
 
## 🔍 Project Workflow
 
### 1. Data Preparation
 
- Image collection
- Dataset organization
- Training and validation split
- Image preprocessing
 
### 2. Model Development
 
- Loading a pre-trained ResNet-18 model
- Replacing the final classification layer
- Fine-tuning on the custom dataset
 
### 3. Training and Validation
 
- Model training
- Validation accuracy monitoring
- Performance evaluation
 
### 4. Prediction and Visualization
 
- Celebrity classification
- Prediction visualization
- Result analysis
 
---
 
## 📈 Results
 
The model achieved:
 
### ✅ Validation Accuracy: 99.34%
 
The trained model demonstrated excellent classification performance across all celebrity classes and achieved highly reliable prediction results.
 
---
 
## 🛠 Technologies
 
- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Jupyter Notebook
 
---
 
## 📂 Project Structure
 
```text
data/ - Training and validation datasets
models/ - Saved model weights
notebooks/ - Training and evaluation notebooks
src/ - Source code and helper functions
results/ - Visualizations and prediction examples
```
 
---
 
## 🚀 Installation
 
Clone the repository:
 
```bash
git clone https://github.com/Alex1988Den/Celebrity-Face-Recognition-ResNet18.git
cd Celebrity-Face-Recognition-ResNet18
```
 
Create a virtual environment:
 
```bash
python -m venv myenv
```
 
Activate the environment:
 
Linux / macOS:
 
```bash
source myenv/bin/activate
```
 
Windows:
 
```bash
myenv\Scripts\activate
```
 
Install dependencies:
 
```bash
pip install -r requirements.txt
```
 
Launch Jupyter Notebook:
 
```bash
jupyter notebook
```
 
---
 
## 💡 Applications
 
- Face Recognition
- Celebrity Identification
- Computer Vision Education
- Transfer Learning Demonstrations
- Image Classification Systems
 
---
 
## 👨‍💻 Author
 
Developed by **Aleksandr Denissov**
 
📧 Email: aleksandr.denissov@brave.ee
 
---
 
⭐ If you find this project useful, feel free to leave a star on GitHub.
