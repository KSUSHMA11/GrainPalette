# GrainPalette
Rice Variety Classification using Deep Learning (CNN)
Nov 2025 – Personal Project

Built an image classification model to identify 5 rice varieties (Arborio, Basmati, Ipsala, Jasmine, Karacadag) from 75,000 RGB images using TensorFlow/Keras
Preprocessed dataset with Pandas, Pathlib, PIL & OpenCV; used splitfolders to create 80/10/10 train-val-test splits

Designed a custom CNN architecture (Conv2D → MaxPool → Dense) achieving 97.73% training accuracy and 96.52% test accuracy in just 3 epochs
Implemented ImageDataGenerator for real-time data augmentation and efficient batch processing (28×28×3 input)
Visualized class distribution and sample images using Matplotlib & ImageGrid
Tech stack: Python, TensorFlow 2.x, Keras, Pandas, NumPy, OpenCV, Matplotlib, Scikit-learn

Rice Image Classification (CNN) – TensorFlow/Keras
Developed a 5-class rice variety classifier on a 75,000-image dataset. Engineered data pipeline using Pandas, Pathlib, and splitfolders (80/10/10 split). Built and trained a custom convolutional neural network that achieved 97.7% training and 96.5% test accuracy in only 3 epochs. Leveraged ImageDataGenerator for on-the-fly augmentation and visualized results with Matplotlib.
