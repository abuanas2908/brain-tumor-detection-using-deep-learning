# Brain Tumor Detection using Deep Learning

This project uses a convolutional neural network (CNN) to classify brain MRI scans into four categories:
- Glioma Tumor
- Meningioma Tumor
- Pituitary Tumor
- No Tumor

The model is trained using TensorFlow and deployed using Gradio for easy interaction via a web interface.

## 🔍 Project Overview

### 🧠 Model Training (`brain_tumour_prediction.ipynb`)
- Dataset is loaded and preprocessed (resizing, normalization)
- A VGG16-based CNN model is built and trained
- Evaluation is performed with metrics such as accuracy and loss
- The trained model is saved as an `.h5` file

### 🌐 Model Deployment (`final_project.ipynb`)
- The saved model is loaded
- A prediction function is defined to accept MRI images
- A Gradio interface allows users to upload images and view the prediction
- The model can be launched in Colab or locally using Gradio

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/brain-tumor-detection.git
   cd brain-tumor-detection
