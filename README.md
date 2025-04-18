🔥 Forest Fire Detection using Deep Learning
🌍 Overview
Wildfires cause devastating damage to the environment, wildlife, and human lives. This project leverages Deep Learning techniques to detect forest fires from images and videos, enabling early intervention and prevention.

🛠️ Features
✅ Fire detection using Convolutional Neural Networks (CNNs)
✅ Image classification into fire and non-fire categories
✅ Pretrained model integration for higher accuracy
✅ Data preprocessing and augmentation for improved results
✅ Real-time detection capability

📂 Project Structure
bash
Copy
Edit
📁 Forest_Fire_Detection_DL
│-- 📜 Forest_Fire_Detection_DL.ipynb  # Jupyter Notebook with model training & testing
│-- 📂 dataset/                        # Dataset containing fire and non-fire images
│-- 📂 models/                         # Trained models & weights
│-- 📂 results/                        # Evaluation metrics & visualizations
│-- 📜 README.md                        # Project documentation (this file)
🏗️ Technologies Used
🔹 Python 🐍
🔹 TensorFlow / Keras 🧠
🔹 OpenCV 👀
🔹 NumPy & Pandas 📊
🔹 Matplotlib & Seaborn 🎨

🚀 How to Run
1️⃣ Clone this repository:

bash
Copy
Edit
git clone https://github.com/yourusername/Forest_Fire_Detection_DL.git
cd Forest_Fire_Detection_DL
2️⃣ Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
3️⃣ Run the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook Forest_Fire_Detection_DL.ipynb
4️⃣ Follow the steps inside the notebook to train and evaluate the model.

📊 Results & Performance
Achieved high accuracy in detecting fire from images.

Successfully implemented real-time fire detection using OpenCV.

Used data augmentation to improve model generalization.

📌 Future Enhancements
🚀 Implement edge AI for real-time mobile applications
🚀 Deploy as a web or mobile application
🚀 Enhance dataset with satellite imagery for better accuracy

🌟 If you find this project useful, give it a ⭐ on GitHub!
Let's fight wildfires with AI! 🔥🌿
📅 Week 2 Summary
During Week 2, significant foundational progress was made in setting up and preparing the wildfire detection project. The following key tasks were completed:

🔸 Dataset Integration & Preprocessing
Successfully integrated the Wildfire Dataset using kagglehub.

Verified the presence of training, validation, and test directories.

Ensured that the dataset was properly structured for model training.

🔸 Environment Setup
Imported necessary libraries including:

TensorFlow/Keras for deep learning

OpenCV, NumPy, Matplotlib for data handling and visualization

Enabled GPU support for faster training using TensorFlow configuration.

🔸 Data Pipeline Creation
Initialized ImageDataGenerator for real-time image augmentation:

Applied rescaling, rotation, zoom, and horizontal flipping.

Created data generators for:

Training set

Validation set

Test set

These steps established the groundwork for model development and training, ensuring clean, organized input for the deep learning pipeline.
