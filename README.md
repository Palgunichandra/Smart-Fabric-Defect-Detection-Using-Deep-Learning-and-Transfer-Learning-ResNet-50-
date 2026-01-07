📌 Project Overview

Fabric quality inspection is a critical process in the textile industry. Traditional manual inspection methods are time-consuming, inconsistent, and prone to human error. This project presents an automated fabric defect detection system using deep learning and transfer learning with ResNet-50 to accurately classify fabric images as defective or non-defective.

The system improves inspection accuracy, reduces human intervention, and provides a scalable solution suitable for modern textile manufacturing environments.

🎯 Objectives

Automate fabric defect detection using deep learning

Apply ResNet-50 for robust feature extraction

Classify fabric images into defective and non-defective categories

Improve accuracy compared to traditional inspection methods

🧠 Methodology

Data Collection – Labeled fabric images (defective and non-defective)

Image Pre-Processing – Resizing, normalization, and data augmentation

Model Selection – Pre-trained ResNet-50 using transfer learning

Model Training – Fine-tuning on fabric dataset

Classification – Defect vs non-defect prediction

Evaluation – Accuracy, loss, and confusion matrix

🏗️ System Architecture
Fabric Images
      ↓
Image Pre-Processing
      ↓
ResNet-50 CNN (Transfer Learning)
      ↓
Feature Extraction
      ↓
Defect Classification
      ↓
Output Prediction

📊 Expected Outcomes

High-accuracy fabric defect detection

Reduced manual inspection effort

Fast and consistent quality control

Scalable solution for textile industries

🧪 Technologies Used

Python

TensorFlow / Keras

OpenCV

NumPy

Matplotlib

Jupyter Notebook

🗂️ Project Structure
Fabric_Defect_Detection/
│
├── dataset/
│   ├── defective/
│   └── non_defective/
│
├── inceptionv3_model_1.ipynb   # Model training & evaluation notebook
├── README.md
└── requirements.txt

⚙️ Installation & Setup
1️⃣ Create Virtual Environment (Recommended)
conda create -n fabric_env python=3.9
conda activate fabric_env

2️⃣ Install Dependencies
pip install tensorflow==2.10.0 numpy pandas matplotlib opencv-python scikit-learn pillow

3️⃣ Run the Project

Open Jupyter Notebook

Run inceptionv3_model_1.ipynb step-by-step

Train the model and view evaluation results

📈 Results

The proposed system achieves high classification accuracy (≈96–98%), demonstrating the effectiveness of deep learning and transfer learning for fabric defect detection.

🚀 Future Enhancements

Real-time camera integration

Deployment on edge devices

Multi-defect and severity classification

Web application using Flask/Streamlit

👨‍👩‍👦 Team Members

Palguni M B – 4MH22CA031

Suri R – 4MH22CA052

Varun J S – 4MH22CA058

Manjunatha B S – 4MH23CA402

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
