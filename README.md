---

# Sign Language Recognition

## Project Description

The **Sign Language Recognition (SLR)** system translates sign language into text. Users form hand shapes that are structured signs or gestures. The configuration of the fingers, the orientation of the hand, and the relative position of fingers and hands to the body are expressions of a deaf and mute person. Our model detects these sign gestures using computer vision and a module called MediaPipe to detect landmarks and positions of body postures. We use a Long Short Term Memory (LSTM) model to predict the sign gestures.

## Objective

The purpose of the SLR system is to provide an efficient and accurate way to convert sign language into text, enabling very young children and others to interact using the system.

## Features

- **Hand Gesture Detection**: Uses MediaPipe to detect hand landmarks and positions.
- **Gesture Prediction**: Utilizes an LSTM model to predict sign gestures.
- **Real-time Translation**: Converts sign language gestures into text in real-time.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/SrirajPenjerla/sign_recognition.git
    ```
2. Navigate to the project directory:
    ```bash
    cd sign_recognition
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the main script to start the sign language recognition:
    ```bash
    python srs_code.py
    ```
2. Follow the on-screen instructions to perform sign gestures in front of the camera.

## Files

- **srs_code.py**: Main script for running the sign language recognition.
- **srs_model.h5**: Pre-trained LSTM model for gesture prediction.
- **MP_data.zip**: Dataset used for training the model.
- **README.md**: Project documentation.

