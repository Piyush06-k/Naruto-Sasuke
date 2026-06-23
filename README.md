# 🌀 Naruto-Sasuke AR Hand Tracking

An interactive augmented reality (AR) web application that brings Naruto and Sasuke's iconic jutsu to life using your webcam! By utilizing Google's MediaPipe framework for real-time hand tracking, this project overlays dynamic video effects (like a Rasengan or Chidori) onto your hands when you open your palms.


## Features

* Real-Time Hand Tracking: Detects up to two hands simultaneously using a standard webcam.
* Gesture Recognition: Automatically detects an "open hand" gesture to trigger the visual effects.

### Dynamic Visuals
* Left Hand: Triggers the Naruto effect.
* Right Hand: Triggers the Sasuke effect.


## Tech Stack

* HTML5 / CSS: For structure, layout, and blending modes (mix-blend-mode: screen for the VFX).
* JavaScript: Core logic and DOM manipulation.
* MediaPipe Hands: Machine learning model for high-fidelity hand and finger tracking.
* MediaPipe Camera & Drawing Utils: Helper libraries for webcam access and rendering landmarks.

