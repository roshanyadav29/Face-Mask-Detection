# Face Mask Detection using Arduino and Python

![Final Assembly](https://github.com/roshanyadav29/Face-Mask-Detection/blob/main/Ref%20Images/Sample-Security-Model.jpg)

## Description
This project showcases my expertise in computer vision, Arduino programming, and Python integration, addressing the critical need for safety measures during the COVID-19 pandemic.

The primary objective of this project was to create a model for face mask detection using Python. Leveraging the power of OpenCV and TensorFlow, I trained a custom model to accurately detect whether individuals are wearing face masks. The model combines image processing techniques and machine learning algorithms to provide real-time detection and classification of faces with or without masks.

To ensure seamless communication between the Python application and Arduino, I implemented Pyfirmata, a Python library for interfacing with Arduino boards. Pyfirmata enabled smooth coordination between the face mask detection model and the physical components controlled by Arduino. To demonstrate the practical application of the face mask detection system, I integrated a door lock mechanism using servos controlled by Arduino. When a person without a mask is detected, the system triggers the servo motors to secure the door, preventing access. Conversely, when a person wearing a mask is identified, the servos unlock the door, allowing entry.

By combining face mask detection algorithms with Arduino-controlled servos, this system offers a reliable and efficient approach to enforcing mask-wearing policies in various settings. It can be easily deployed in entrances, access points, or any location requiring automated monitoring and control. This project represents a significant achievement in leveraging emerging technologies to ensure the well-being of individuals and communities.

## Getting Started

### Prerequisites
Before you begin, ensure you have met the following requirements:
* You have a Windows machine. 
* You have installed the latest version of Python and Arduino IDE.
* You have basic knowledge of Python and Arduino programming.

### Installing Face Mask Detection
To install Face Mask Detection, follow these steps:

1. Clone the repo:
```bash
git clone https://github.com/roshanyadav29/Face-Mask-Detection.git
```
2. Navigate into the project directory:
```bash
cd Face-Mask-Detection
```
3. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Using Face Mask Detection
To use Face Mask Detection, follow these steps:

1. Open the Arduino IDE and upload the Arduino code to your Arduino board.
2. Run the Python script:
```bash
python DetecMask.py
```

## How it Works
The system works by first capturing video frames and then processing these frames using a trained machine learning model. The model has been trained to detect faces and determine whether a mask is being worn or not. If a face is detected without a mask, the system sends a signal to the Arduino board, which can then perform a specific action, such as sounding an alarm.

## Contributing to Face Mask Detection
To contribute to Face Mask Detection, follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b <branch_name>`.
3. Make your changes and commit them: `git commit -m '<commit_message>'`
4. Push to the original branch: `git push origin <project_name>/<location>`
5. Create the pull request.

Alternatively, see the GitHub documentation on [creating a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

## Contact
If you want to contact me, you can reach me at `30005500@iitb.ac.in`.

## License
This project uses the following license: `<MIT License>`.