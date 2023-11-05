# Pose-detection-using-Mediapipe

This Python script uses the OpenCV library and the MediaPipe library for real-time pose estimation using your computer's camera. It detects and visualizes pose landmarks on the video and camera

## Prerequisites

Before running the code, make sure you have the following libraries installed:

- OpenCV (`pip install opencv-python`)
- MediaPipe (`pip install mediapipe`)

## Usage

1. Clone or download this repository to your local machine.
2. Open a terminal or command prompt.
3. Navigate to the project directory.
4. Run the script using the following command:
5. The webcam feed will open, and you will see the pose landmarks drawn on your body in real time.

## Key Features

- Captures video frames from the default camera.
- Converts frames to RGB color space for processing.
- Estimates pose landmarks using MediaPipe's Pose model.
- Draws landmarks and connections on the video frames.
- Displays the processed video feed in real time.

## Documentation

The code contains comments that explain various parts of the script. Here's a brief explanation of the main components:

- `mpDraw`: Used for drawing pose landmarks on the video frame.
- `mpPose`: Used for pose estimation.
- `pose`: An instance of `mpPose.Pose()` for pose estimation.
- The `while` loop captures and processes video frames continuously.
- Pose landmarks are extracted and displayed, and their coordinates are printed.
- The `cv2.imshow` function displays the video feed.

## License

This project is licensed under the MIT License. You can find the license details in the [LICENSE](LICENSE) file.

## Acknowledgments

- This project uses the [MediaPipe](https://mediapipe.dev/) library for pose estimation.



