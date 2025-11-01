# Brain-Tumor-Classification

# 🧠 Brain Tumor Classification using Deep Learning

This project is a **Brain Tumor Classification Web Application** built using **Streamlit** and a **pre-trained Deep Learning model**.  
It allows users to upload **MRI brain scan images** and predicts one of the following categories:

| Tumor Type      | Description |
|-----------------|-------------|
| **Glioma**       | Tumors formed in the glial cells of the brain. |
| **Meningioma**   | Tumors developing in the protective membranes of the brain & spinal cord. |
| **Pituitary Tumor** | Tumors affecting the pituitary gland. |
| **No Tumor**     | Indicates a healthy MRI scan. |

---

## 🚀 Features
- Simple and interactive **web interface using Streamlit**
- Accepts **JPG / JPEG / PNG** MRI images
- Displays:
  - Predicted Tumor Type
  - Confidence Score
  - Class-wise Confidence Bar Chart
- Works entirely offline after setup

---

## 📂 Project Structure
📁 Brain-Tumor-Classification
│
├── brain_tumor.ipynb # Model training notebook (Jupyter)
├── brain_tumor.py # Streamlit application script
├── InceptionV3_best.pkl # Trained model file (example name)
└── README.md # Documentation

yaml
Copy code

---

## 🧰 Tech Stack

| Component | Technology |
|----------|------------|
| Frontend / UI | Streamlit |
| Model Type | CNN (InceptionV3 / EfficientNetB0 or similar) |
| Libraries Used | TensorFlow, NumPy, Pillow, Pickle |
| Language | Python |

---

