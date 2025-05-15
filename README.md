# DeepFace Emotion Detector

A real-time facial emotion recognition tool leveraging MTCNN for face detection and DeepFace for emotion analysis.

## Overview

This project uses computer vision and deep learning techniques to detect faces in images or live webcam feed and classify their emotions. It combines the **MTCNN** face detector from `facenet-pytorch` with the **DeepFace** emotion analysis library to provide accurate and robust emotion predictions.

## Features

* **Real-Time Face Detection**: Uses MTCNN to locate faces in images or webcam stream.
* **Emotion Classification**: Employs DeepFace to analyze detected faces and predict emotions such as happy, sad, angry, surprised, etc.
* **Visualization**: Displays bounding boxes and emotion labels on images or video frames using OpenCV and Matplotlib.

## Requirements

* Python 3.7+
* `facenet-pytorch`
* `deepface`
* `opencv-python`
* `numpy`
* `Pillow`
* `matplotlib`

## Installation

```bash
pip install facenet-pytorch deepface opencv-python numpy pillow matplotlib
```

## Usage

1. Clone this repository:

   ```bash
   git clone https://github.com/3vmmar/emotion-detection.git
   cd Deepface_Emotion_Detector
   ```

2. Open the Jupyter notebook:
```bash
jupyter notebook Deepface_Emotion_Detector.ipynb
````

3. Run through the cells to start face detection and emotion analysis. You can switch between static images and webcam input as demonstrated in the notebook.

## Project Structure

```
├── Deepface_Emotion_Detector.ipynb   # Main notebook with code and explanations
├── .gitignore
├── LICENSE 
└── README.md                         # This file
```

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests for enhancements, bug fixes, or new features.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
