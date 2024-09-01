# Hand-Sign-Language-Detection
This project is designed to detect and interpret hand signs in real-time using a custom-trained machine learning model. Unlike pre-trained models, this system uses a model trained from scratch with thousands of self-captured hand images, encompassing multiple letters, words, and phrases. The project utilizes OpenCV for image processing, TensorFlow/Keras for the model, and MediaPipe for hand tracking, providing an effective tool for translating sign language gestures into text.


# Usage

Data Collection: Use datacollection.py to gather data for model training.
Testing: Run test.py to evaluate the performance of the trained model.
Model: The model file (keras_model.h5) and label file (labels.txt) are used for hand sign classification.
us.py: to run it o streamlit Web Ui Application in your default browser
