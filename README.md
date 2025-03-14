# Face Recognition with OpenCV

This Python script performs real-time face recognition using OpenCV and the `face_recognition` library. It captures video from your webcam, detects faces, and compares them with a set of known faces stored in the `Resources` folder.

## Features

- **Face Detection**: Detects faces in real-time using a webcam.
- **Face Recognition**: Compares detected faces with a pre-loaded set of known faces.
- **Real-time Display**: Displays the video feed with bounding boxes and labels for recognized faces.

## Requirements

- Python 3.x
- OpenCV (`cv2`)
- NumPy (`numpy`)
- face_recognition library

## Usage

1. Place images of known faces in the `Resources` folder. The filename (without extension) will be used as the label for the face.
2. Run the script:
```bash
python face_recognition.py
```
3. The script will open a window showing the webcam feed. Recognized faces will be labeled with their corresponding names.
## Example
If the Resources folder contains an image named john.jpg, the script will label any detected face that matches John with "JOHN".

## Notes
- Ensure the face_recognition library is installed and properly configured.
- The script assumes that the Resources folder is in the same directory as the script.
