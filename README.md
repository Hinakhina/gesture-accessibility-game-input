# gesture-accessibility-game-input
A vision-based hand gesture recognition system for real-time game control, designed as an accessible input alternative for players with motor and speech impairments and built with OpenCV, MediaPipe, and PyAutoGUI.


# Vision-Based Hand Gesture Recognition for Game Accessibilit

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
  - ✋ Open palm → Jump / Up 
  - ✊ Closed fist → Down 
  - ☝️ Index finger → Left
  - ✌️ Index + Middle → Right 
  - 🤙 Pinky → Exit / Quit

---

## Demo
[Insert link to YouTube demo or .gif showing the system in action]

## System Requirements
- Python 3.8–3.10
- Webcam (min. 360p)
- Mid-range PC or laptop
- Game or app that accepts keyboard input

## Acknowledgements
Inspired by open-source gesture recognition projects shared in developer communities (Discord).
