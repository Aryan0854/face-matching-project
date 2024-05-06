# Real-Time Face Detection and Features Recognition

This Python script utilizes OpenCV (Open Source Computer Vision Library) to perform real-time face detection and features recognition using pre-trained cascade classifiers.

## Requirements
- Python 3.x
- OpenCV (cv2)
- NumPy

## Installation

You can install OpenCV and NumPy using pip:

```bash
pip install opencv-python-headless numpy
```

## Usage

1. Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/face-detection.git
```

2. Navigate to the cloned directory:

```bash
cd face-detection
```

3. Run the Python script:

```bash
python face_detection.py
```

4. The script will open your webcam and start detecting faces and features in real-time.

## Additional Notes

- The script loads pre-trained cascade classifiers for face, eye, and smile detection. These classifiers are provided by OpenCV.
- You can adjust the detection parameters such as scaleFactor, minNeighbors, and minSize according to your requirements.
- Press the 'Esc' key to exit the program.

## Credits

- This script is based on the Haar cascade classifiers provided by OpenCV.
- Created by Aryan Mishra.
