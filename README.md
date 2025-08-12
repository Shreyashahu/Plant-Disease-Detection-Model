# 🌿 Plant Disease Detection

This project helps farmers detect plant diseases using Deep Learning. We use a Convolutional Neural Network (CNN) built with PyTorch to classify leaf images into **39 different disease categories**. The model is trained on the popular PlantVillage dataset.

---

## 🚀 Getting Started

### Prerequisites

* Python 3.8 installed on your machine
* Basic knowledge of Python and virtual environments

### Setup Instructions

1. **Create and activate** a Python virtual environment:
   [Python venv Guide](https://docs.python.org/3/tutorial/venv.html)

2. **Install required dependencies** by running:

   ```bash
   pip install -r requirements.txt
   ```

3. Navigate to the `Flask Deployed App` directory.

4. Download the pre-trained model file `plant_disease_model_1.pt` from [this link](https://drive.google.com/drive/folders/1ewJWAiduGuld_9oGSrTuLumg9y62qS6A?usp=share_link) and place it inside the `Flask Deployed App` folder.

5. Run the Flask application using:

   ```bash
   python3 app.py
   ```

6. The web app will be accessible locally, and you can upload leaf images to detect diseases.

*Alternatively*, you can use the pre-trained model in the `Model` section with Jupyter Notebook for experimentation.

---

## 🤝 Contribution Guidelines

* This project is **open source** and welcomes contributions!
* You can improve the UI, enhance the deep learning model, or add documentation.
* If you modify the deep learning model, please include updated `.md`, `.pdf`, and `.ipynb` files.
* Ensure your code runs without errors before submitting.
* Fork the repository, make your changes, and submit a pull request.
* For help with pull requests, see: [How to create a pull request](https://opensource.com/article/19/7/create-pull-request-github)

---

## 📂 Testing Images

If you don’t have leaf images to test, you can use the sample images located in the `test_images` folder. Each image is labeled with the corresponding disease, so you can verify model accuracy easily.

---


If you want me to add or remove anything else, just say!
