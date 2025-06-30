# Traffic Light Classification Using CNN

This project was developed as part of the "AI Foundations in Practice" coursework. It involves building and evaluating a Convolutional Neural Network (CNN) to classify traffic light images into two categories: **Red** or **Green**.

## 📁 Project Structure

- `AI_Foundations_CW2.ipynb` – Main Jupyter Notebook with all preprocessing, model building, training, and evaluation.
- `README.md` – Overview of the project and how to use it.
- `.gitignore` – To exclude cache and temporary files from version control.

## 🖼️ Dataset Overview

The dataset contains traffic light images labeled either "red" or "green". Steps performed include:
- Image preprocessing and resizing
- Data augmentation
- Splitting into training and testing sets

## 🧠 Model Architecture

The CNN model includes:
- 2D Convolutional layers
- MaxPooling layers
- Flatten and Dense layers
- ReLU and Softmax activations

Training was performed using Keras with TensorFlow backend.

## 📊 Results

- **Training Accuracy**: ~97%
- **Validation Accuracy**: ~95%
- **Test Accuracy**: ~94%

### Sample Predictions

Five randomly selected test images were classified with high accuracy, and their predicted labels matched the actual labels.

## 💡 Future Improvements

1. Introduce more diverse real-world images to improve robustness.
2. Experiment with deeper CNN architectures like VGG or transfer learning using MobileNet.

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/traffic-light-classifier-cnn.git
Open the notebook in Google Colab or Jupyter.

Ensure the required libraries are installed:

bash
Copy
Edit
pip install tensorflow keras matplotlib numpy
🧾 License
This project is part of an academic assignment and is intended for learning purposes only.

yaml
Copy
Edit

---

### 🛑 .gitignore

```gitignore
.ipynb_checkpoints/
__pycache__/
*.pyc
.DS_Store
*.h5
*.zip
