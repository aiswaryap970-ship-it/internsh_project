# Motion Gesture Classifier

A web-based motion gesture classifier that uses device accelerometer data and an Edge Impulse machine learning model to recognize three types of gestures: **Circle, Wave, and Idle**.

## Live Demo

[Open the Motion Gesture Classifier](https://motion-gesture-classifie-fda3c.web.app)

## Features

- Real-time accelerometer data visualization
- Motion gesture classification
- Three gesture classes: Circle, Wave, and Idle
- Motion data recording
- CSV download
- Session analytics
- Runs machine learning inference directly in the browser

## Technologies

- HTML
- JavaScript
- Edge Impulse
- WebAssembly (WASM)
- Firebase Hosting
- Device Accelerometer / Generic Sensor API

## How It Works

The application reads motion data from the device's accelerometer. The sensor data is processed by an Edge Impulse machine learning model, which predicts the gesture being performed.

The predicted probabilities for **Circle, Wave, and Idle** are displayed in the browser.

## Project Structure

```text
motion_gesture_classifier/
├── public/
│   ├── index.html
│   ├── edge-impulse-standalone.js
│   └── edge-impulse-standalone.wasm
├── .firebaserc
└── firebase.json
