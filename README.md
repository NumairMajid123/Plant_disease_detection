🌿 Plant Disease Detection
This project focuses on building a machine learning model to automatically detect plant diseases using image classification techniques. We trained our models on a dataset of 17,000 images, which are categorized into 9 different classes, representing healthy and diseased leaves of various crops.

📂 Dataset Overview
The dataset consists of labeled images of plant leaves, divided into the following 9 classes:

Apple___Apple_scab

Apple___Cedar_apple_rust

Corn_(maize)__Common_rust

Corn_(maize)___healthy

Potato___Early_blight

Potato___healthy

Tomato___Early_blight

Tomato___Tomato_Yellow_Leaf_Curl_Virus

Tomato___healthy

🧠 Approach
We implemented two different models to classify plant diseases:

🔸 1. Custom CNN (Convolutional Neural Network)
Designed and trained a custom CNN architecture from scratch.

Multiple convolutional and pooling layers for feature extraction.

Dropout layers for regularization and improved generalization.

🔸 2. ResNet with Transfer Learning
Used a pre-trained ResNet model (ResNet50) as the backbone.

Applied transfer learning by freezing initial layers and fine-tuning deeper layers for our specific dataset.

Significantly reduced training time and improved accuracy due to pre-learned features.

🛠️ Tools & Technologies
Python

TensorFlow, Keras

NumPy, Matplotlib

Google Colab, Jupyter Notebook

📊 Results
Both models showed strong performance in classifying plant diseases. The ResNet model achieved superior accuracy due to the power of transfer learning.
