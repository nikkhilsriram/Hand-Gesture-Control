# Hand-Gesture-Control
Control your computer with hand gestures
# Hand Gesture Control System

A computer vision-based system that allows you to control your computer using hand gestures.

## Features

- Control mouse cursor with hand movements
- Click detection with thumb and index finger
- Scrolling with left hand movements
- Volume control with hand gestures
- Visual feedback for all actions
- Smooth cursor movement with position averaging

## Installation

1. Clone this repository:
```
git clone https://github.com/yourusername/hand-gesture-control.git
cd hand-gesture-control
```

2. Install required dependencies:
```
pip install -r requirements.txt
```

## Usage

Run the hand gesture control system with:
```
python SCROLL.PY
```

### Hand Control Usage:
- **Right Hand**: Controls mouse movement
  - Pinching index finger and thumb: Click
  - Thumb movement: Adjust volume
- **Left Hand**: Scrolling (up/down)
- Press 'q' in the camera window to exit

## System Requirements

- Python 3.7 or higher
- Webcam for hand tracking
- Windows OS (for volume control features)

## Troubleshooting

- If hand tracking is jerky, try adjusting lighting conditions
- If mouse control is too sensitive, modify the MOUSE_SENSITIVITY value in the code
- Make sure your webcam is working properly
- For volume control issues, check that the audio libraries are properly installed

## License

This project is licensed under the MIT License - see the [LICENSE](nikkhilsriram) file for details.

## Acknowledgments

- MediaPipe for hand tracking functionality
- The open-source community for the various libraries used in this project 
