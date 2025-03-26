This project contains a full pipeline for training a machine learning model for hand recognition. It includes data preparation, training scripts, model conversion, and deployment files.


ML_HandModel/ – Contains the full pipeline for preparing images, annotations, and training the model, there is also a webcam script after the training is done to test the model

best.pt – The trained PyTorch model file.

config.yaml – Configuration settings used during training.

data.yaml – Dataset-related information, including paths and classes.

tfjs_converter/ – Tools and scripts used for converting the PyTorch model to TensorFlow.js.

converted_pt_model/ – The converted TensorFlow.js model.

model.json – The model architecture. 

group1-shard1of3, group1-shard2of3, group1-shard3of3 – The model weights.

index.html – A web-based interface for testing the converted tfjs model on a webcam in the browser.

