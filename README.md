# Conversion of Sign Language to Text and Speech
A real-time computer vision-based application that captures American Sign Language (ASL) gestures through a webcam and translates them into readable text and audible speech output.
This project is designed to bridge the communication gap between deaf/mute individuals and the hearing population, making communication more inclusive and accessible.

🚀 Features
Real-time hand gesture recognition using webcam

Hand landmark detection using Mediapipe

CNN-based classification of ASL alphabets (A-Z)

Conversion of recognized gestures into text

Text-to-speech conversion for audio output

Works across different backgrounds and lighting conditions

User-friendly GUI developed with Tkinter

High recognition accuracy (up to 97%-99%)

🎯 Objectives
To recognize ASL hand gestures and convert them into English text.

To translate recognized text into speech using a TTS engine.

To create an affordable, efficient, and accessible communication tool.

To support deaf/mute individuals in better interaction with society.

🔧 Tech Stack
Programming Language: Python 3.9

Libraries/Frameworks:

OpenCV (for image processing)

Mediapipe (for hand landmark detection)

TensorFlow & Keras (for building CNN model)

Pyttsx3 (for text-to-speech conversion)

Tkinter (for GUI development)

NumPy (for numerical operations)

Hardware: Webcam (built-in or external)

🛠️ How It Works
Capture live hand gestures using the system’s webcam.

Extract hand landmarks using Mediapipe.

Preprocess images and pass them to the CNN model.

Classify the gestures into corresponding alphabets.

Display recognized alphabets on the GUI.

Convert text output into audio speech using pyttsx3.

🧪 Testing
Tested under different lighting and background conditions.

Achieved real-time prediction speed with high accuracy.

Robust performance observed even without clean backgrounds.

📈 Future Enhancements
Full word and sentence recognition.

Mobile application version.

Dynamic gesture (motion-based signs) recognition.

Multi-language speech output support.

AI-powered prediction improvements.

