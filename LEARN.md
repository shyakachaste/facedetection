# Face Detection with OpenCV

This repository contains a simple C++ program for face detection using OpenCV. The program captures video from a camera and uses Haar cascades for face detection.

## Prerequisites

Before diving into the world of face detection, make sure you have the following prerequisites:

- Basic understanding of C++ programming.
- Familiarity with OpenCV library installation.
- OpenCV: You can install it using your preferred package manager or by building it from source. Ensure that OpenCV is properly linked in your project.

## Program Features

- Face detection using Haar cascades.
- Displays the number of faces found in each frame.
- Draws rectangles around detected faces.
- Shows a count of the faces found on the top left corner.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/shyakachaste/facedetection.git
   cd facedetection

## Usage

The program captures video from the default camera (camera index 1). Adjust the camera index in the code if needed.

Press the 'Esc' key to exit the program.

## Haar Cascade XML File

The program uses the Haar cascade file `haarcascade_frontalface_default.xml` for face detection. Ensure that this file is present in the same directory as the executable or provide the correct path in the code.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to modify and use the code according to your needs.
