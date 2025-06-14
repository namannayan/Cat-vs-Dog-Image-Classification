# Cat-vs-Dog-Image-Classification
A deep learning project to classify images as either Cat or Dog using Convolutional Neural Networks (CNNs) in TensorFlow and Keras.


cat-vs-dog-classification/

 main.ipynb   # file with main code
 
 README.md    
        

🔍 Objective
This project aims to build an image classification model capable of distinguishing between cats and dogs using CNNs. It utilizes TensorFlow 2.x and processes images from the given dataset for model training and validation.

⚙️ Tech Stack
Python 3.x

TensorFlow 2.x / Keras

NumPy

Matplotlib (for visualization)

Jupyter Notebook



🧠 Model Architecture
The model is a CNN built with:

Multiple Conv2D + MaxPooling layers

BatchNormalization

Dropout for regularization

Flatten → Dense → Output layer with Softmax



🚀 How to Run
Clone this repository:

bash
git clone https://github.com/your-username/cat-vs-dog-classification.git
cd cat-vs-dog-classification
Install dependencies:

bash
pip install -r requirements.txt
Launch Jupyter Notebook:

bash
jupyter notebook main.ipynb
Note: Make sure train/ and test/ folders are present in the working directory and contain cats/ and dogs/ subfolders with respective images.


*Data set Link

https://www.kaggle.com/datasets/salader/dogs-vs-cats 


📊 Sample Results

Training Accuracy: 94.52%

Validation Accuracy: 82.18%


📌 To-Do
 Add confusion matrix

 Implement data augmentation

 Deploy model with Flask or Streamlit


 📄 License
This project is licensed under the MIT License.



