# Facial-recognition
This project is a facial recognition system that captures images of a subject, trains a recognition model, and provides real-time facial recognition through a graphical user interface (GUI). It uses Python along with OpenCV, Pillow, NumPy, and OS for implementation.


## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Folder Structure](#folder-structure)
- [Setup](#setup)
- [Steps to Run](#steps-to-run)

## Introduction

Provide a brief introduction to your project. Explain its purpose, features, and any important context.

## Requirements

List the requirements and dependencies for your project. Include the necessary libraries:

- Python
- OpenCV (cv)
- Pillow
- NumPy
- OS (usually comes with Python)

## Folder Structure

dataset/ # Contains collected data
datacollect.py # Script for data collection
trainingdemo.py # Script for model training
testmodel.py # Script for testing the model
other files and folders

## Setup

1. Clone the repository to your local machine:

  ```bash
  git clone https://github.com/YourUsername/YourRepository.git
  ```

2. Navigate to the project directory:
  
  ```bash
  cd Facial-recognition
  ```

3. Install the required Python libraries:
  ```bash
  pip install opencv-python pillow numpy
  ```

## Steps to Run

1. **Data Collection:**

   - Run `datacollect.py` to capture images of the subject.
   - Capture images from various angles and expressions (around 500 images).

2. **Model Training:**

   - Execute `trainingdemo.py` to create a `training.yml` file.
   - This file contains the trained model for facial recognition.

3. **Testing:**

   - Run `testmodel.py` to launch the GUI for facial recognition.
   - Use the GUI to test the system in real-time.

Enjoy using the facial recognition system!


