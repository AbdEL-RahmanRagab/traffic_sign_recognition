# Traffic Sign Classification 🚦

## 📌 Overview
This project is a deep learning model that classifies traffic signs using a Convolutional Neural Network (CNN). The model is trained on a dataset of traffic signs and can predict the class of a given traffic sign image.

## 🔧 Features
- Image classification of traffic signs.
- Model training and evaluation with performance metrics.
- Data visualization including loss and accuracy plots.

## 🛠 Technologies Used
- **Python** 🐍
- **TensorFlow/Keras** for deep learning.
- **OpenCV** for image processing.
- **Matplotlib & Seaborn** for data visualization.
- **Pandas & NumPy** for data manipulation.

## 📂 Project Structure
```
📦 Traffic Sign Classification
 ┣ 📂 Dataset
 ┃ ┣ 📂 train
 ┃ ┣ 📂 test
 ┣ 📜 main.py  (Model training and evaluation)
 ┣ 📜 Test_Model.py  (Prediction on new images)
 ┣ 📜 README.md  (Project Documentation)
 ┗ 📜 requirements.txt  (Required Libraries)
```

## 🏗 Model Training
To train the model, run the following command:
```bash
python main.py
```
The model will be saved as `my_model.h5`.

## 🚀 How to Use
1. **Classify an Image:**
   ```bash
   python Test_Model.py --image path_to_image.jpg
   ```

## 📊 Model Performance
- Training Accuracy: **98%**
- Validation Accuracy: **99%**
- Confusion Matrix included for performance analysis.

## 📌 Future Improvements
- Deploy the model as a web application.
- Optimize for mobile devices using TensorFlow Lite.

## 🔗 References
- [TensorFlow Documentation](https://www.tensorflow.org/)
- [OpenCV Documentation](https://opencv.org/)

🚀 **Developed by [Abd EL-Rahman Ragab]**

