# Eye-Controlled Mouse 👁️🖱️

## Project Overview 🚀

This Python project offers a hands-free mouse interface controlled by your eye movements, leveraging the power of computer vision libraries: OpenCV, MediaPipe, and PyAutoGUI.

## Key Functionalities 🔑

### Image Capturing (OpenCV) 📸:
- Retrieves live video frames from your webcam using OpenCV.
- Each frame serves as the foundation for eye detection and movement tracking.

### Facial Landmark Detection (MediaPipe) 🤖:
- Employs a pre-trained MediaPipe model to identify facial landmarks on captured frames.
- Focuses on locating key points like eyes, nose, and mouth.

### Eye Movement Tracking (OpenCV) 👀:
- Analyzes positions of detected eye landmarks (particularly iris or pupil centers) using OpenCV.
- Tracks subtle eye movements, translating direction and distance into corresponding cursor movements on the screen.

### Mouse Control (PyAutoGUI) 🖱️:
- Utilizes PyAutoGUI for GUI automation.
- Translates tracked eye movements into real-time cursor control on your screen.
- Optionally, eye blinks can be programmed to trigger mouse clicks (left or right) for selection/interaction.

## Benefits 🌟

- Hands-free computer interaction, ideal for accessibility purposes or a futuristic navigation method.

## Considerations 🤔

- Initial calibration may be required to fine-tune eye movement sensitivity for optimal control.
- Ambient lighting conditions can influence detection accuracy.

## Further Enhancements (Optional) 🛠️

- Calibration options to personalize eye movement sensitivity.
- Head movement tracking integration for more intuitive control.
- Expand functionality of eye blinks to include double-clicks or drag-and-drop actions.

