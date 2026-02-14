# AI Virtual Trainer

This project uses Computer Vision and MediaPipe to create a virtual personal trainer that counts your exercise repetitions. The current implementation tracks bicep curls using pose estimation.

## Features
- Real-time pose estimation using MediaPipe.
- Automatic bicep curl counting.
- Visual feedback on exercise form (up/down stage).
- Lightweight and fast.

## Installation

1.  Clone the repository.
2.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
Run the main script:
```bash
python main.py
```
Ensure your webcam is connected. Stand in front of the camera so your upper body is visible. Perform bicep curls with your left arm to see the counter increment.

## Future Improvements
- Support for more exercises (Squats, Pushups).
- GUI for selecting exercises.
- Calories burned estimation.
