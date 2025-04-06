# 🩺 Sanjeevani: AI-Powered Medical Diagnosis & Health Analysis

Sanjeevani is an AI-powered medical diagnostic system designed to assist healthcare professionals and patients by analyzing medical images and lab reports to detect diseases at an early stage. Built with advanced Machine Learning and Computer Vision techniques, Sanjeevani aims to bridge the gap in healthcare accessibility, especially in underserved regions.

## 🚀 Features

- 🔬 **Image-Based Diagnosis**
  - **Chest X-rays:** Detect Pneumonia & Tuberculosis using CNN models.
  - **MRI Scans:** Identify Brain Tumors.
  - **Skin Images:** Classify Melanoma and other skin conditions.

- 📄 **Medical Report Analysis**
  - Extract text using OCR (Tesseract/Google Vision API).
  - Interpret blood and urine test reports using ML models.

- 📊 Real-time inference with TFLite deployment for mobile accessibility.

- 💬 Interactive dashboard for uploading, analysis, and viewing results.

---

## 🧠 Tech Stack

| Module                 | Technology Used                                |
|------------------------|-----------------------------------------------|
| AI/ML Models           | TensorFlow, Keras (ResNet50, EfficientNet)     |
| OCR                    | Tesseract OCR, Google Vision API               |
| Image Preprocessing    | OpenCV, NumPy                                  |
| UI/UX                  | Streamlit / Flask / React (based on version)   |
| Deployment             | TFLite, Colab API, Firebase / Render           |
| Dataset Sources        | Shenzhen TB X-rays, ISIC Skin Lesion, BraTS    |

---

## 📁 Project Structure

sanjeevani/ │ <br>├── models/ # Trained AI/ML models (H5/TFLite) <br>├── datasets/ # Image datasets (X-ray, MRI, skin)
              <br>├── notebooks/ # Training and evaluation notebooks <br> ├── backend/ # Flask/Django backend for inference 
              <br>├── frontend/ # UI for interaction 
              <br>├── static/ # Icons, CSS, JS files 
              <br>├── utils/ # Helper scripts for preprocessing, OCR 
              <br>└── README.md

![Screenshot 2025-04-06 111319](https://github.com/user-attachments/assets/dc73d543-8ae6-4765-b98e-40291280728f)


---

## 🛠 Installation & Setup

1. **Clone the Repository**
```bash
git clone https://github.com/yourusername/sanjeevani.git
cd sanjeevani
```

---

2. **Create a virtual environment & install dependencies**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```
---

3. **Run the Application**
```bash
python backend/app.py  # Or use Streamlit / Flask depending on your frontend
```


**🧪 Sample Results
Input Image	Output Diagnosis
Chest X-ray	✅ Tuberculosis Detected
Brain MRI	⚠️ Possible Tumor Region
Skin Lesion	✅ Likely Benign (Melanoma)
Blood Test (OCR Extracted)	🔍 Elevated WBC Count
AND many more......

💡 Use Cases
Rural Telemedicine & Diagnosis

Public Health Screening Programs

AI Assistance in Primary Healthcare

Mobile Health Apps Integration

👨‍💻 Developed By

Sahana G: https://www.linkedin.com/in/sahana-g-912979326?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app
<br> HealthTech Enthusiast • Project Lead

Yashashwini R: https://www.linkedin.com/in/yashaswini-r-39a127325?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app
<br> AI Engineer • AI/ML Developer

Madhuradarshini : 
<br> Frontend Developer • OCR & Image Processing

Armaan Samir Jena: www.linkedin.com/in/jena-armaan
<br> Backend Developer • Cloud Integrator



📜 License
This project is licensed under the MIT License.
See the LICENSE file for details.


🙏 Acknowledgements
NIH Shenzhen Dataset

ISIC Skin Cancer Dataset

BraTS Brain Tumor Dataset

TensorFlow, Google Cloud, Tesseract OCR
***
