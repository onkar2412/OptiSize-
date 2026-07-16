# OptiSize

> An intelligent computer vision application that dynamically adjusts on-screen text size based on the user's distance from the camera, enhancing readability and accessibility.

---

## Description / Overview

OptiSize is a Python-based computer vision project that estimates the user's distance from a webcam using facial landmark detection. Based on the measured distance, the application dynamically adjusts the displayed text size in real time, providing an improved reading experience and better accessibility.

This project demonstrates the practical use of computer vision, facial landmark detection, and real-time image processing to create an adaptive user interface.

---


## Features

- Real-time face distance estimation
- Dynamic text resizing based on user distance
- Facial landmark detection using MediaPipe Face Mesh
- Live webcam processing
- Fast and lightweight implementation
- Real-time visual feedback
- Accessibility-focused design

---

## How It Works

1. Captures live video from the webcam.
2. Detects facial landmarks using MediaPipe Face Mesh.
3. Calculates the distance between the user's eyes.
4. Estimates the distance from the camera.
5. Dynamically adjusts the text size.
6. Displays the updated text in real time.

---

## System Architecture

```text
Webcam
   │
   ▼
Video Capture
   │
   ▼
Face Detection
   │
   ▼
Face Landmark Detection
   │
   ▼
Distance Estimation
   │
   ▼
Dynamic Text Scaling
   │
   ▼
Display Output
```

---

## Tech Stack

### Programming Language

- Python

### Libraries

- OpenCV
- MediaPipe
- cvzone
- NumPy

### Tools

- Git
- GitHub
- PyCharm

---

## Project Structure

```text
OptiSize/
│
├── assets/
├── demo/
├── docs/
├── screenshots/
├── src/
│   ├── face_depth.py
│   ├── dynamic_text.py
│   └── utils.py
├── tests/
├── main.py
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/onkar2412/OptiSize.git
```

### Navigate to the Project Directory

```bash
cd OptiSize
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Usage

Run the application using:

```bash
python main.py
```

Ensure your webcam is connected before running the program.

---

## Requirements

- Python 3.8 or later
- Webcam
- OpenCV
- MediaPipe
- cvzone
- NumPy

---

## Results

The application successfully:

- Detects the user's face in real time.
- Estimates the distance from the webcam.
- Dynamically adjusts text size based on the measured distance.
- Maintains smooth real-time performance.

---

## Future Enhancements

- Graphical User Interface (GUI)
- Voice-assisted reading mode
- OCR integration
- Eye strain detection
- Mobile application support
- Multi-user support
- Custom accessibility settings

---

## Contributing

Contributions are welcome.

1. Fork this repository.
2. Create a new feature branch.
3. Commit your changes.
4. Push your branch.
5. Open a Pull Request.

---

## License

This project is licensed under the MIT License. You are free to use, modify, and distribute this software in accordance with the terms of the license.

For complete details, please refer to the [LICENSE](LICENSE) file.
---

## Credits / Acknowledgments

- OpenCV
- MediaPipe
- cvzone
- Python Community

---

## Author

**Onkar Shrikonda**

AI & Data Science Engineer

---

## Contact

- GitHub: https://github.com/onkar2412
- LinkedIn: https://www.linkedin.com/in/onkar-shrikonda/
- Email: Shrikonda.onkar@gmail.com
