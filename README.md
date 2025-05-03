# gesture-accessibility-game-input
A vision-based hand gesture recognition system for real-time game control, designed as an accessible input alternative for players with motor and speech impairments and built with OpenCV, MediaPipe, and PyAutoGUI.


# Vision-Based Hand Gesture Recognition for Game Accessibility

This project provides a real-time hand gesture recognition system that emulates keyboard input using only a standard webcam. It is designed to improve accessibility for players with motor and speech disabilities, allowing them to control video games without physical controllers or voice commands.

## Library and package
- **Python 3.8–3.10**
- **OpenCV** for real-time video processing
- **MediaPipe** for hand landmark detection
- **PyAutoGUI** to emulate keyboard inputs

## Features
- Non-invasive and camera-based — no extra hardware required
- Maps hand gestures to keyboard keys (e.g., ↑ ↓ → ←)
- Compatible with any game that uses keyboard input
- Supports gesture-to-command mapping:
  - UpArrow key → 4 fingers or 5 fingers up
  - DownArrow key → 0 finger or thumbs up
  - LeftArrow key → 1 finger up but not thumbs nor middle finger
  - RightArrow key → 2 fingers up
  - Space key → 3 fingers up
  - Close camera and exit program → press q on keyboard

    ⚠️ Make sure your palm is facing the camera when performing any gesture.
    The system may not recognize gestures correctly if the hand tilts or faces sideways.
 ---

▶️ How to Use
1. Launch your game or application that uses keyboard controls.

2. Run the program: gestureToKeyboard.py

3. A webcam window will open and begin tracking your hand gestures in real time.

4. Use the predefined gestures to control your game character (see feature -> gesture-to-command above).
⚠️ Important: After launching the program, click on your game window to ensure it is focused.
The system emulates keyboard input, so gestures will only control the game if the game window is active.
Avoid clicking back on the terminal, camera preview, or any other window.

5. To close the camera and exit the program:
- Press the Q key on your keyboard (make it focus on the camera window)


---

## Demo
[Insert Video Link]

## System Requirements
- Python 3.8–3.10
- Webcam (min. 360p)
- Mid-range PC or laptop
- Game or app that accepts keyboard input

## Acknowledgements
Inspired by open-source gesture recognition projects shared in developer communities (Discord).
