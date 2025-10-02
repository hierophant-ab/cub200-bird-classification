# cub200-bird-classification

# 🐦 CUB-200 Bird Species Classification  

## 📌 Overview  
This project implements a deep learning model to classify bird species from the **CUB-200-2011 dataset** using **EfficientNet-B0** as the backbone. 
The dataset comprises **200 bird species** with over **11,000 images**, serving as a benchmark for fine-grained image classification.  

The goal of this project is to build and evaluate deep learning models that can accurately classify birds into their respective species.  

---

## 📂 Project Structure
CUB-200-Classification/
│── data/ # Dataset (not included in repo)
│── models/ # Saved trained models
│── notebooks/ # Jupyter notebooks for experiments
│── src/ # Source code
│ ├── dataset.py # Data loading & preprocessing
│ ├── model.py # Model architecture(s)
│ ├── train.py # Training script
│ ├── evaluate.py # Evaluation script
│── requirements.txt # Python dependencies
│── README.md # Project documentation

## 📊 Dataset  
The project uses the **CUB-200-2011 dataset**, available at:  
👉 [Caltech CUB-200-2011 Dataset](http://www.vision.caltech.edu/visipedia/CUB-200-2011.html)  

🛠️ Technologies Used

Python 3.9+
PyTorch / TensorFlow (depending on your implementation)
Matplotlib & Seaborn (visualization)
NumPy & Pandas
