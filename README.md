# Brain-Tumor
# Brain Tumor Classification – Naan Mudhalvan Project

This project is developed as part of the **Naan Mudhalvan** skill development program under the subject **Deep Learning**. It aims to classify brain tumors from MRI scans using a **Convolutional Neural Network (CNN)** and provides predictions via an interactive **Gradio** interface.

---

## 📌 Introduction

Brain tumor classification is a crucial step in medical imaging and diagnosis. This project utilizes deep learning to categorize brain MRI images into one of the following four classes:

- **Glioma Tumor**
- **Meningioma Tumor**
- **Pituitary Tumor**
- **No Tumor**

The trained model is deployed with a Gradio UI, allowing users to upload MRI images and get instant predictions.

---

## 🧠 Project Structure

- `Brain Tumor Classification System.ipynb` – Main Jupyter Notebook containing:
  - Data loading and preprocessing
  - CNN model creation and training
  - Gradio interface integration

- `Brain Tumor Classification System.docx` - Report of the Brain Tumor Classification System
- 
- `README.md` – Documentation of the project, setup instructions, and future goals.

---

##  Features

Classifies MRI scans into: glioma, meningioma, notumor, pituitary

Uses TensorFlow/Keras for building and training a CNN

Handles image preprocessing with OpenCV

LabelBinarizer for multi-class output

Gradio interface for easy drag-and-drop predictions

---

## 🛠 Technologies Used

- **Python**
- **Google Colab**
- **TensorFlow & Keras** – Deep learning framework
- **Gradio** – For web interface
- **NumPy & Pandas** – Data handling
- **Matplotlib** – For training visualization

---

## ▶️ How to Run

1. Open the notebook in **Google Colab**:  

2. Upload your MRI image dataset or connect to your Google Drive.

3. Run all cells in `project2.ipynb` to:
   - Train the CNN model
   - Launch the Gradio interface

4. Use the Gradio web app to upload MRI images and view tumor classification results.

---

## 🚀 Future Enhancements

- Improve prediction accuracy using deeper CNN architectures (e.g., ResNet, EfficientNet)
- Train with a larger and more diverse dataset for better generalization
- Deploy the Gradio app online for broader accessibility

---

## 📄 License

This project is for **educational purposes only** under the **Naan Mudhalvan** initiative. It is not intended for commercial or clinical use.

---
