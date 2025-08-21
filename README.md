# Real-Time Irish Sign Language (ISL) Recognition 🎥🤟

This project implements a **real-time Irish Sign Language (ISL) recognition system** using **MediaPipe Holistic** for landmark extraction and a **Long Short-Term Memory (LSTM)** deep learning model for classification.  
The system recognizes 11 ISL gestures in live video input from a webcam and overlays the predicted action on screen.


## ✨ Features
- **Dataset Creation**: ISL gestures recorded via webcam following trusted tutorials ([NCSE YouTube channel](https://youtu.be/hT__XVBx6to)).
- **Preprocessing**: 
  - Keypoint extraction (face, hands, pose) with MediaPipe Holistic  
  - Normalization and sequence padding (30 frames per sequence)  
  - Label mapping and storage in structured directories  
- **Model**: LSTM-based sequential neural network trained on recorded dataset  
- **Evaluation**: 
  - Accuracy, confusion matrices, precision, recall per gesture  
  - Training curves reconstructed from logs  
- **Real-Time Testing**: Live predictions with probability visualisation overlay  
- **Results**: Achieved ~76% accuracy on test set; reliably detected most gestures in real-time.  
