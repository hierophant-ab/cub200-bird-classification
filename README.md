# 🐦 CUB-200 Bird Species Classification  

## 📌 Overview  
This project implements a deep learning model to classify bird species from the **CUB-200-2011 dataset** using **EfficientNet-B0** as the backbone. 
The dataset comprises **200 bird species** with over **11,000 images**, serving as a benchmark for fine-grained image classification.  

The goal of this project is to build and evaluate deep learning models that can accurately classify birds into their respective species.  

---

## 📂 Project Structure
CUB-200-Classification/<br>
│── data/ # Dataset (not included in repo)<br>
│── models/ # Saved trained models<br>
│── notebooks/ # Jupyter notebooks for experiments<br>
│── src/ # Source code<br>
│ ├── dataset.py # Data loading & preprocessing<br>
│ ├── model.py # Model architecture(s)<br>
│ ├── train.py # Training script<br>
│ ├── evaluate.py # Evaluation script<br>
│── requirements.txt # Python dependencies<br>
│── README.md # Project documentation<br>

## 📊 Dataset  
The project uses the **CUB-200-2011 dataset**, available at:  
👉 [Caltech CUB-200-2011 Dataset](http://www.vision.caltech.edu/visipedia/CUB-200-2011.html)  

🛠️ Technologies Used

Python 3.9+<br>
PyTorch / TensorFlow (depending on your implementation)<br>
Matplotlib & Seaborn (visualization)<br>
NumPy & Pandas

## 📚 What I Learned from This Project  

Working on this project gave me hands-on experience with:  

- Implementing and fine-tuning **EfficientNet-B0** for a real-world classification task  
- Handling a **large fine-grained dataset (CUB-200-2011)** and preparing it for training  
- Applying **data preprocessing techniques** such as normalization, augmentation, and train-test splits  
- Understanding the **importance of transfer learning** and how pre-trained models accelerate convergence  
- Experimenting with **evaluation metrics** (accuracy, top-5 accuracy, ROC curves) to assess model performance  
- Structuring a machine learning project with **modular code (dataset, model, train, evaluate)** for clarity and reusability  
- Using **TensorFlow** effectively for deep learning workflows   

This project helped strengthen both my deep learning fundamentals and practical ML engineering skills.  

