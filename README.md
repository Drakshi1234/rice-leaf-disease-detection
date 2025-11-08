Rice Leaf Disease Detection
📘 Overview

Rice is one of the world’s most important crops, and leaf diseases can cause major yield losses if not identified early.
This project uses Deep Learning (CNN) to automatically detect and classify rice leaf diseases from images.
The goal is to assist farmers and researchers in early diagnosis and prevention through AI-powered crop health monitoring.

🧠 Project Objectives

Detect and classify rice leaf diseases automatically.

Reduce manual effort and improve diagnostic accuracy.

Support smart agriculture using AI and computer vision.

⚙️ Technologies Used

Python

TensorFlow / Keras

OpenCV

NumPy & Pandas

Matplotlib / Seaborn

📂 Dataset

The dataset consists of images of rice leaves belonging to the following categories:

Bacterial Leaf Blight

Brown Spot

Leaf Smut

Healthy Leaf

You can use any publicly available dataset such as the Rice Leaf Disease Dataset from Kaggle
.

🧩 Model Architecture

A Convolutional Neural Network (CNN) is used for image classification.
Steps include:

Image preprocessing and augmentation

Feature extraction using CNN layers

Classification into respective disease categories

Model evaluation using accuracy and confusion matrix

🚀 How to Run the Project

Clone the repository:

git clone https://github.com/<your-username>/rice-leaf-disease-detection.git


Navigate to the project folder:

cd rice-leaf-disease-detection


Install dependencies:

pip install -r requirements.txt


Run the training script:

python train_model.py


Test the model on new images:

python predict.py --image path_to_image.jpg

📊 Results

Achieved high accuracy in classifying rice leaf diseases.

Visualized model performance with accuracy/loss graphs.

Successfully predicted disease type for unseen leaf images.

🌱 Future Enhancements

Deploy model as a web app using Flask / Streamlit.

Add more disease types and a larger dataset.

Integrate with mobile camera input for real-time detection.

🤝 Contributing

Contributions are welcome!
If you’d like to improve the model, add more data, or enhance the interface, feel free to fork the repo and create a pull request.

