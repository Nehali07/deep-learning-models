# Deep Learning Classifier: MNIST & CIFAR-10

This project demonstrates deep learning techniques using Deep Neural Networks (DNNs) and Convolutional Neural Networks (CNNs) on two popular image datasets: **MNIST** and **CIFAR-10**. It includes model building, evaluation, and saving/loading for reuse.

## 🔍 Tasks Covered

1. **Basic DNN for MNIST**  
   - Simple feedforward neural network.

2. **Deeper DNN for MNIST**  
   - Added more hidden layers for improved accuracy.

3. **DNN with Dropout (MNIST)**  
   - Introduced dropout for better generalization.

4. **CNN for CIFAR-10**  
   - Used convolutional layers to classify 32x32 color images.

5. **Model Saving & Reloading**  
   - Saved and loaded models using `.h5` format.

## 📁 Files

- `deep_learning_tasks (1).ipynb` – Jupyter notebook with all task implementations.
- `mnist_dnn_model.h5` – Saved DNN model trained on MNIST.
- `cifar10_cnn_model.h5` – CNN model trained on CIFAR-10.
- `cnn_model.h5` – Duplicate of CIFAR-10 CNN model used to demonstrate model reloading.
- `README.md` – Project overview and instructions.

## 🧠 Technologies Used

- Python
- TensorFlow / Keras
- MNIST & CIFAR-10 Datasets
- Google Colab / Jupyter Notebook

## ✅ How to Run

1. Open `deep_learning_tasks (1).ipynb` in Jupyter or [Google Colab](https://colab.research.google.com/).
2. Run all cells in sequence.
3. Make sure to install dependencies (if needed):
   ```bash
   pip install tensorflow
