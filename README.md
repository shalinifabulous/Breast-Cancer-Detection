# 🔬 Breast Cancer Detection using CNN

This deep learning project detects breast cancer using histopathological images by training a Convolutional Neural Network (CNN). The model achieved **97% accuracy** and uses **Grad-CAM** to provide visual explanations for predictions.

![Accuracy](https://img.shields.io/badge/Accuracy-97%25-brightgreen)

---

## 💡 Features

- Developed a CNN model with TensorFlow/Keras
- Preprocessed image data to enhance training quality
- Achieved **97% accuracy** on test data
- Applied **Grad-CAM** for explainable AI (XAI)
- Used Jupyter Notebook for step-by-step development and visualization

---

## 📊 Model Performance

| Metric     | Value  |
|------------|--------|
| Accuracy   | 97%    |
| Loss       | 0.09   |

✅ The model generalizes well on test data  
🎯 Grad-CAM helped verify which regions influenced the model’s decision

---

## 🖼️ Grad-CAM Visualization

Grad-CAM (Gradient-weighted Class Activation Mapping) was implemented in this project to visualize the areas of histopathological images the model focuses on while making predictions.

📌 **Note:** Visual heatmaps will be added in future updates.  
The feature is coded but image output is not included in this version.


📁 Folder Structure

breast_cancer_detection/
├── breast_cancer_detection.ipynb
├── data/
│   └── histopath_images/
├── outputs/
│   ├── gradcam_result.png
│   └── accuracy_loss_graph.png
├── README.md


🛠️ Tech Stack
Python 3.x

Jupyter Notebook

TensorFlow / Keras

NumPy, Pandas, Matplotlib

OpenCV

Scikit-learn


🚀 How to Run the Project

☁️ Option 2: Run on Google Colab
Visit Google Colab

Upload breast_cancer_detection.ipynb

Upload your dataset when prompted

Run each cell sequentially using Shift + Enter


📌 Project Status
✅ Completed – Core functionality and analysis done
💡 Future Improvements

Add UI using Streamlit/Flask

Expand dataset and support multi-class classification

Model compression for deployment


👩‍💻 Author
Shalini Gupta
B.Tech CSE (AI & ML) Student
📌 GitHub: @shalinifabulous
📌 LinkedIn: Shalini Gupta


📜 License
This project is licensed under the MIT License
