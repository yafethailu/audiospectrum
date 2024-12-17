# Audio Spectrum Visualizer

A real-time audio spectrum analyzer using ESP32 and LED matrix display that visualizes audio frequencies across the human hearing range.

<div align="center">
  <img width="369" alt="Screenshot 2024-12-17 at 3 57 25 PM" src="https://github.com/user-attachments/assets/6be40ebc-33ff-4e00-a7e5-e8b2b483d0e2" />
</div>

## Table of Contents
- [Introduction](#introduction)
- [Theory](#theory)
- [Features](#features)
- [Hardware](#hardware)
- [Results](#results)
- [Build Process](#build-process)

## Introduction

This project creates a visual representation of audio frequencies using an analog filter bank and LED matrix display. The system processes audio input in real-time, splitting the frequency spectrum into discrete bins and displaying them as an animated visualization.

## Theory

The human auditory system can perceive frequencies ranging from approximately 20 Hz to 20 kHz. This project visualizes these frequencies by:

- Splitting the audio spectrum into discrete frequency bands
- Using non-uniform frequency spacing to match human perception
- Displaying stronger bass frequencies on the left and treble on the right
- Accounting for the nonlinear nature of human frequency perception

<div align="center">
  <img width="753" alt="Screenshot 2024-12-17 at 3 58 38 PM" src="https://github.com/user-attachments/assets/5367b80d-0b05-4185-9a98-bbd48f99ce81" />
</div>

## Features

- Real-time audio processing
- Custom analog filter bank design
- ESP32-based processing
- LED matrix visualization
- Frequency range: 20 Hz - 20 kHz

## Hardware

The system consists of:
- ESP32 microcontroller
- Custom-designed analog filter bank
- LED matrix display
- Audio input circuit

<div align="center">
  <img width="712" alt="Screenshot 2024-12-17 at 4 01 03 PM" src="https://github.com/user-attachments/assets/dc6c7d82-5743-428e-bbfb-8c7d8a97fdc7" />
</div>

## Results

### Waveform Generator Testing
The system was tested using various input frequencies to verify the filter bank operation:

<div align="center">
  <img width="718" alt="Screenshot 2024-12-17 at 4 01 36 PM" src="https://github.com/user-attachments/assets/2d9bfa57-33c3-4647-a41e-8e21a7f2fc0a" />
  <img width="612" alt="Screenshot 2024-12-17 at 4 01 56 PM" src="https://github.com/user-attachments/assets/12f86263-5e71-4738-859e-401cea8f4b45" />
  <br/>
  <img width="793" alt="Screenshot 2024-12-17 at 4 02 18 PM" src="https://github.com/user-attachments/assets/01898a63-ce60-49ea-98b8-0105b36f8fdf" />
  <img width="760" alt="Screenshot 2024-12-17 at 4 02 39 PM" src="https://github.com/user-attachments/assets/0859486b-dc42-4c8a-bbf8-f4d6761cc1ce" />
</div>

### Final Build
The completed circuit board after soldering:

<div align="center">
  <img width="683" alt="Screenshot 2024-12-17 at 4 03 33 PM" src="https://github.com/user-attachments/assets/6de0a5b2-79f3-4d0f-b0b4-8178ef6cfe28" />
</div>

## Build Process

The project was implemented through the following steps:
1. Design and simulation of the analog filter bank
2. PCB design and fabrication
3. Component assembly and soldering
4. ESP32 programming and integration
5. LED matrix interface development
6. System testing and calibration

## **Technologies and Tools**
- **Hardware**: ESP32, Analog Filters, LED Matrix
- **Software**: Embedded C for ESP32 programming
- **Tools**: Digital multimeter, Oscilloscope, Soldering station

---

## **Key Features**
- Real-time visualization of audio frequency spectrum.  
- Accurate splitting of the spectrum into discrete bins.  
- Integration of analog filters with LED matrix for display.  
- Portable and responsive design using the ESP32 microcontroller.  

---

## **Future Improvements**
- Implementing FFT (Fast Fourier Transform) for more accurate frequency analysis.  
- Adding user input controls for dynamic customization.  
- Enhancing LED matrix resolution for finer visual detail.  

---

