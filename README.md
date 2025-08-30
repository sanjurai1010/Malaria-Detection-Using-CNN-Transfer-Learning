🦟 Malaria Detection Using CNN & Transfer Learning
📌 Introduction

Malaria is a life-threatening disease caused by parasites transmitted through mosquito bites. Early detection is crucial to save lives, especially in high-risk regions.
This project uses Deep Learning (CNNs + Transfer Learning) to automatically classify blood smear images into:

✅ Uninfected

❗ Infected (Malaria positive)

The model achieved 91% accuracy, showing the potential of AI in supporting medical diagnosis.

📊 Dataset

Total Images: 27,558 blood cell images

Split: 80% Training, 20% Testing

Image Size: 224 × 224 pixels

Source: NIH / Kaggle Malaria Dataset

🛠️ Tools & Libraries Used

Programming Language: Python

Deep Learning Frameworks: TensorFlow, Keras

Other Libraries: NumPy, Matplotlib, OS

Environment: Jupyter Notebook / Google Colab

⚙️ Model Workflow

Load a pre-trained CNN model (Transfer Learning).

Preprocess and resize blood smear images.

Train the model on labeled data (Infected vs. Uninfected).

Evaluate accuracy and performance.

Use a prediction function to test on new images.

📈 Results

Accuracy: 91%

Correct prediction ~8 out of 10 times.

Output clearly displays:

✅ Uninfected (Healthy)

❗ Infected (Malaria)

🚀 Future Work

Improve accuracy with more data and augmentation.

Fine-tune model further for better generalization.

Deploy as a web or mobile application for real-time diagnosis.
