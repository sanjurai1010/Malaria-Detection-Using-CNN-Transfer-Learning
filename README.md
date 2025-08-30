🦟 Malaria Detection Using CNN & Transfer Learning

📌INTODUCTION

Malaria is a life-threatening disease caused by parasites transmitted through mosquito bites. Early detection is crucial to save lives, especially in high-risk regions.
This project uses Deep Learning (CNNs + Transfer Learning) to automatically classify blood smear images into:
✅ Uninfected
❗ Infected (Malaria positive)
The model achieved 91% accuracy, showing the potential of AI in supporting medical diagnosis.

📊 DATASET:

Total Images: 27,558 blood cell images
Split: 80% Training, 20% Testing
Image Size: 224 × 224 pixels
Source: NIH / Kaggle Malaria Dataset

🛠️TOOLS AND LIBRARIES USED:

Programming Language: Python
Deep Learning Frameworks: TensorFlow, Keras
Other Libraries: NumPy, Matplotlib, OS
Environment: Jupyter Notebook / Google Colab

⚙️MODEL WORK FLOW:

Load a pre-trained CNN model (Transfer Learning).
Preprocess and resize blood smear images.
Train the model on labeled data (Infected vs. Uninfected).
Evaluate accuracy and performance.
Use a prediction function to test on new images.

📈RESULTS:

Accuracy: 91%
Correct prediction ~8 out of 10 times.

OUTPUT CLEARLY DISPLAYS:

✅ Uninfected (Healthy)
❗ Infected (Malaria)

🚀FUTURE WORK:

Improve accuracy with more data and augmentation.
Fine-tune model further for better generalization.
Deploy as a web or mobile application for real-time diagnosis.
