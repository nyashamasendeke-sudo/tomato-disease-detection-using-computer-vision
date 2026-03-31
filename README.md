# tomato-disease-detection-using-computer-vision
This repository contains dataset and model for tomato disease detection on raspberry pi using transfer learning.  
The dataset for this project was taken from Kaggle tomato disease dataset.  
A pretrained model was used as the base model for transfer learning (MobileNet) optimised for embedded harware.  
A transfer layer was added to the base model for disease detection.  
Model transfer learning on raspberry pi was evaluated using software for resource monitoring during training.  
The model was tested on real tomato leaves in an experimental tomato garden with infected tomato plants.  
The models confidence score/ predictions were not that far off.  
The major diseases which were being investigated were early blight and late blight.  
Model inference was also evaluated noting parameters such as latency.  
Hardware considerations were taken into account to reduce latencies during inference\

