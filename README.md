# 🖐️ Virtual Mouse Controller

A Fun and Innovative Way to Control Your Computer Mouse Using Hand Gestures! ✨


## Overview

Welcome to the Virtual Mouse Controller GitHub repository! This innovative Python script combines the power of computer vision and automation to give you a unique way to control your computer mouse using hand gestures. Say goodbye to your traditional mouse and hello to a fun, touchless experience.

## Prerequisites

Before you get started, ensure you have the following prerequisites:

- **Python**: You'll need Python 3.x installed on your computer.

- **Dependencies**: Install the necessary Python packages using `pip`:

  ```bash
  pip install opencv-python mediapipe pyautogui
  ```

## Getting Started

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/swarup-09/Mouse-control-using-hand.git
   ```

2. Run the script:

   ```bash
   python hand_mouse.py
   ```

3. Position your hand in front of your webcam, and start controlling your mouse cursor with hand gestures!

## How It Works

- **Hand Tracking**: We use the powerful MediaPipe library to detect and track your hand movements.

- **Mouse Control**: Your index finger moves the mouse cursor on the screen.

- **Mouse Click**: Bring your thumb close to your index finger to simulate a mouse click.

- **Exit**: To exit the script, simply press the 'Esc' key.

## Customization

We understand that everyone's needs are unique. You can customize the behavior of the virtual mouse by tweaking the following variables in the script:

- `cap = cv2.VideoCapture(0)`: Change the `0` to use a different camera if you have multiple cameras connected.

- `pyautogui.sleep(1)`: Adjust the sleep duration (in seconds) after performing a click action.

- Fine-tune the click action conditions by modifying `if abs(index_y - thumb_y) < 20:`.

## Troubleshooting

Please note that the script's performance may vary based on your webcam quality, lighting conditions, and hand gestures. For improved results, consider adjusting parameters as needed.

## Contributing

We welcome contributions! If you have any ideas, bug fixes, or feature enhancements, please submit a pull request.


---

Go ahead, take control of your computer like a wizard! 👋🧙‍♂️🖥️
