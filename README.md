---
title: CE13 Skin Disease Classifier
emoji: 🩺
colorFrom: blue
colorTo: green
sdk: streamlit
sdk_version: 1.60.0
app_file: app.py
pinned: false
---

# CE13 Skin Disease Classifier Using CNN

## CE13 Mini Project

This project uses a Convolutional Neural Network (CNN) based on **MobileNetV2** to classify skin disease images into two categories:

- Candidiasis
- Tinea

## Dataset

The dataset contains:

- Training Images: **1,063**
- Testing Images: **129**

**Total Images:** **1,192**

The dataset was obtained from Kaggle and organized into separate training and testing folders.

## Model Performance

- Training Accuracy: **93.89%**
- Validation Accuracy: **89.15%**
- Validation Loss: **0.2935**

## Technologies Used

- Python
- TensorFlow/Keras
- MobileNetV2
- Streamlit
- NumPy
- Pillow
- Matplotlib

## How to Run

1. Install the required packages:

```bash
pip install -r requirements.txt
```

2. Run the application:

```bash
streamlit run app.py
```

3. Upload a skin disease image.

4. The application predicts whether the image is:

- Candidiasis
- Tinea

and displays the prediction confidence.

## GitHub Repository

https://github.com/kingenchanted40-code/CE13_Tinea_Candidiasis_Classifier

## Author

**ISUO, BENEDICT EDET**


Group Members and Assigned Responsibilities

Group Leader
ISUO, BENEDICT EDET
Registration Number: 22/EG/CE/1366
Role: Project Coordinator and Team Supervisor
Responsibilities:
Directed the overall execution of the project.
Distributed assignments among team members.
Monitored progress and ensured milestones were achieved.
Verified the final application and approved the project before submission.

1. EDUOK DANIEL GODWIN
Registration Number: 22/EG/CE/1396
Role: Data Acquisition Officer
Responsibilities:
Obtained the project dataset from the appropriate source.
Sorted images into their respective categories.
Checked the dataset for completeness and consistency before training.

2. BASSEY ODUDU JOHN
Registration Number: 22/EG/CE/1416
Role: Image Processing Specialist
Responsibilities:
Prepared the image dataset for model training.
Applied resizing, normalization, and image enhancement techniques.
Configured image generation settings for improved model learning.

3. MGBEBU, THANKGOD JOSHUA
Registration Number: 22/EG/CE/1386
Role: AI Model Development Officer
Responsibilities:
Designed and implemented the deep learning architecture.
Carried out model training and validation.
Monitored learning performance and selected the best-performing model.

4. WILLIE, VICTORIA GODWIN
Registration Number: 22/EG/CE/1406
Role: User Interface Developer
Responsibilities:
Built the web interface using Streamlit.
Connected the trained model to the application.
Developed the prediction interface and result display.

5. MFONMMAENO ANIEKAN ENANG
Registration Number: 22/EG/CE/1376
Role: Deployment and Technical Documentation Officer
Responsibilities:
Published the project to the cloud platform.
Managed the GitHub repository, releases, and project files.
Compiled the technical report and validated the deployed application before final delivery.
