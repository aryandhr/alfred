# Gesture Recognition for Machine Automation - ALFRED

ALFRED is a personal project developed to explore the world of deep learning and its application in automating machine operations using hand gestures in real time. The project utilizes various technologies and libraries such as Mediapipe, OpenCV (cv2), Pyautogui, and LSTM models to achieve its objectives.

Commercial use is not within the scope of this project. The dataset used to train the model was generated solely by the author through multiple recordings for each hand gesture. Furthermore, the automation functions implemented in this project are specifically designed for macOS machines. While a more generalized solution could be explored in the future, it was not the primary focus of this project.

## Table of Contents

- [Project Overview](#project-overview)
- [Demo](#demo)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Overview

The Gesture Automation project focuses on automating machine operations based on hand gestures. The workflow involves the following steps:

1. **Webcam Integration**: OpenCV (cv2) is utilized to access the machine's webcam and capture video frames for gesture recognition. The captured frames are then processed to extract the hand landmarks using Mediapipe Holistic.

2. **Hand Gesture Detection**: The project employs the Mediapipe Holistic library to extract landmark values for hand gestures in real time. By feeding the landmarks into the LSTM model, it can recognize various gestures made by the user.

3. **Gesture Recognition**: A Long Short-Term Memory (LSTM) model is trained to classify the extracted hand gestures. LSTM models are a type of recurrent neural network (RNN) particularly effective for sequence data like hand gesture recognition.

4. **Automation**: Once a gesture is recognized, the Pyautogui library is employed to automate specific tasks. Pyautogui provides cross-platform support for automating mouse movements, clicks, and keyboard inputs.

## Demo

![](giphy.gif)

## Technologies Used

The Gesture Automation project utilizes the following technologies and libraries:

- **Mediapipe Holistic**: A library for real-time hand landmark detection and gesture recognition.

- **OpenCV (cv2)**: A computer vision library used for accessing the webcam, capturing video frames, and image processing.

- **Pyautogui**: A cross-platform library for automating mouse movements, clicks, and keyboard inputs.

- **Keras LSTM Model**: A deep learning model based on Long Short-Term Memory architecture, trained to recognize hand gestures.

## Contributing

Contributions to the Gesture Automation project are welcome. If you have any ideas, bug fixes, or enhancements, feel free to submit a pull request. Please ensure that your code follows the project's coding style and includes appropriate documentation.

## License

The Gesture Automation project is available under the [MIT License](LICENSE). Feel free to modify and distribute the code for personal and educational purposes.

## Contact

If you found this project useful, or have any questions, don't hesitate to reach out to the project's creator at dhararya@msu.edu.
