# Animal-Image-Classification-using-InceptionV3

This project aims to classify images of animals—cats, dogs, and snakes—using deep learning models. It explores two approaches: building a custom Convolutional Neural Network (CNN) and fine-tuning a pre-trained InceptionV3 model. The project focuses on achieving high accuracy and efficient classification.

# 🧠 Technologies Used
- Python
- TensorFlow (for model building and training)
- Keras (for neural network layers)
- OpenCV (for image processing and quality detection)
- Matplotlib & Seaborn (for visualizing model performance)

# 🔧 Features
- **Custom CNN Model**: Built a simple Convolutional Neural Network from scratch, achieving 70% accuracy on the classification task.
- **InceptionV3 Model**: Leveraged a pre-trained InceptionV3 model, fine-tuned for our dataset, and achieved 97% accuracy.
- **Data Augmentation**: Applied image preprocessing techniques like rescaling to increase dataset diversity and improve model generalization.
- **Blurry Image Detection**: Used OpenCV to filter out blurry images to ensure better model performance.

# 📊 Results
- Custom CNN Model Accuracy: 70%
- InceptionV3 Pre-trained Model Accuracy: 97%

![Image Prediction](output.png)

# 📂 Dataset Structure
```
dataset/
│
├── test/
│   ├── cats/
│   ├── dogs/
│   └── snakes/
│
└── train/
    ├── cats/
    ├── dogs/
    └── snakes/
```

# 📸 Image Categories
- __cats__: Images of cats.
- __dogs__: Images of dogs.
- __snakes__: Images of snakes.

# 🏁 Setup and Installation
1. **Clone the repository :**
   ```bash
   git clone https://github.com/your-username/animal-image-classification.git
   cd animal-image-classification

2. **Install required dependencies:**
   ```bash
   pip install -r requirements.txt

3. **Run it on Jupyter Notebook**

# 🔍 How to Use
- **Run the Training Notebook**: You can train the CNN model or fine-tune the InceptionV3 model. Both models are available as separate notebooks.
- **Visualize Results**: Use Matplotlib and Seaborn to plot the model’s accuracy, loss, and confusion matrix to evaluate its performance.

# 💬 Contributing
Feel free to fork this repository, open issues, and submit pull requests. If you have suggestions for improvements or enhancements, don't hesitate to contribute!
