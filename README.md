# Emotion Detection Application

This program recognizes emotions in photos and videos using deep learning models. It can identify emotions from static photos, real-time webcam feeds, and video files. The emotions identified include angry, disgusted, fearful, happy, sad, surprised, and neutral.

## Table Of Contents
1. [Overview] (#overview).
2. [Dependencies] (#dependencies).
3. [use] (#use).
4. [Features] (#features).
5. [Credits] (#credits).
6. [License] (#license).

<a name="Overview"><a> ## Overview

This study makes use of deep learning models to recognize facial emotions. It uses the following technologies:

- OpenCV is a library for processing images and videos.
- TensorFlow and Keras for deep learning-based emotion categorization.
- MTCNN (Multi-Task Cascaded Convolutional Neural Network) for facial recognition.
- The graphical user interface is implemented using Tkinter.
- System notification provider.
- Python Imaging Library (PIL) for image processing.

<a name="dependencies">.</a> ## Dependences

Make sure the following requirements are installed:

Python 3.x, OpenCV, TensorFlow, mtcnn, Pillow (PIL), and Plyer.

To install the Python requirements, use pip:

'''bash ` pip install opencv-python tensorflow mtcnn pillow plyer '''

<a name="usage"></a> ## Use

## Running the Application

To launch the program, type the following command:

'''Bash python emotion_detection.py.'''

### Options:

- **Recognize from File:** Choose an image file from your system to do emotion recognition.
- **Real-time Recognition:** Enables the camera to detect emotions in real time.
- **Recognize from Video:** Allows you to pick a video file for emotion recognition.
- **Stop Recognition:** Terminates the presently active recognition procedure.
- **Close:** closes the application.

<a name="Features"></a> ## Features:

- **File Recognition:** Recognize emotions in static photographs.
- **Real-time Recognition:** Detect emotions from a webcam stream.
- **Video Recognition:** Recognize emotions in video files.
- **Customizable:** Select the appropriate emotion for detection from the dropdown menu.
- **System alerts:** Receive alerts whenever a certain emotion is identified.
- **Visual Feedback:** Annotated photos and videos displaying observed emotions.
- **Easy to Use Interface:** A basic graphical user interface for interaction.

<a name="credits">.</a> ## Credits:

This project relies on pre-trained models and libraries created by the following:

- MTCNN was created by Iván de Paz Centeno, Ángel Serrano, and David Fuentes-Jiménez.
- **TensorFlow:** Developed by Google's Brain team.
- **OpenCV:** Created by Intel Corporation and Willow Garage.
- **Plyer:** Created by Kivy team.

<a name="license">.<a> ## License

This project is licensed under the [MIT License] (LICENSE).

---

Feel free to adapt this template to your own project requirements and preferences!
