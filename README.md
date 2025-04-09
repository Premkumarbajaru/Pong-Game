# Pong Game Project

## Overview
This project is a simple implementation of the classic Pong game using Python. The game leverages computer vision techniques to allow players to control the paddles using hand gestures. The project utilizes the following libraries:

- **MediaPipe**: For hand tracking and gesture recognition.
- **NumPy**: For numerical operations.
- **TKinter**: For creating the game's graphical user interface (GUI).
- **OpenCV**: For video capture and image processing.
- **CVZone**: A computer vision utility library that simplifies working with MediaPipe and OpenCV.

## Features
- **Hand Gesture Control**: Players can control the paddles by moving their hands in front of the camera.
- **Real-Time Video Feed**: The game displays a real-time video feed with hand tracking overlays.
- **Simple GUI**: The game includes a basic GUI for starting and resetting the game.
- **Score Tracking**: The game keeps track of the scores for both players.

## Requirements
To run this project, you need to have the following Python libraries installed:
# List of dependencies
```bash

mediapipe
numpy
opencv-python
cvzone
tkinter
```

## Project Structure
```
pong-game/
│
├── main.py                # Main script to run the game
├── modulized.py           # Contains the Pong game logic
├── utils.py               # Hand tracking and gesture recognition logic
├── README.md              # This file
├── requirements.txt       # List of dependencies
└── Resources/             # Directory for storing assets (e.g., images)

```

## How to Run
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Premkumarbajaru/Pong-Game.git
   cd Pong-Game
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Game**:
   ```bash
   python main.py
   ```

4. **Play the Game**:
   - Use your hand gestures to control the paddles.
   - The left paddle is controlled by the left hand, and the right paddle is controlled by the right hand.
   - The game ends when one player reaches the maximum score (e.g., 10 points).

## Contributing
Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments
- **MediaPipe**: For providing an excellent hand tracking solution.
- **CVZone**: For simplifying the integration of MediaPipe with OpenCV.
- **OpenCV**: For powerful image processing capabilities.
- **TKinter**: For creating the game's GUI.

## Contact
For any questions or feedback, please contact [ PREMKUMAR BAJARU ] at [premkumarbajaru@gmail.com].

---

Enjoy playing the Pong game! 🎮
