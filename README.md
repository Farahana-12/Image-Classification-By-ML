This project demonstrates image classification using two different models:

1)MobileNetV2: Pre-trained on the ImageNet dataset for general-purpose image classification. 
2)CIFAR-10: A model trained on the CIFAR-10 dataset to classify images into 10 categories.

Features: 
1)MobileNetV2 (ImageNet): Classifies images into 1,000 object categories. 
2)CIFAR-10: Classifies images into one of the 10 categories: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck. 
3)Simple, interactive user interface built with Streamlit to upload an image and receive classification results.

Installation:-
To run this project locally, follow these steps: 
1)Clone the repository: git clone https://github.com/yourusername/your-repo-name.git 
2)Install the required dependencies: pip install -r requirements.txt 
3)Ensure you have the necessary pre-trained models: 
     The MobileNetV2 model will be automatically downloaded from TensorFlow. For the CIFAR-10 model 
     include a pre-trained model file (model111.h5) in the project directory. 
4)Run the Streamlit app:streamlit run app.py

Requirements:- 
Python 3.x
TensorFlow
Streamlit
NumPy
Pillow

Usage:- 
1)Open the app by running the command streamlit run app.py. 
2)Use the sidebar to choose between MobileNetV2 or CIFAR-10 models. 
3)Upload an image (JPG/PNG) for classification. 
4)The model will predict the class and display the confidence score.
