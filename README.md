# DC Motor Fault Classification using Neural Networks

This project presents a MATLAB-based simulation and classification framework for detecting fault conditions in DC motor systems using machine learning techniques.

## Overview

The system under study is a standard DC motor, simulated under three different operating conditions:

- Healthy
- Sensor Noise (Gaussian noise added to output)
- Friction Fault (increased damping factor)

Each condition is simulated using MATLAB, and the resulting speed responses are used to train a simple feedforward neural network for classification.

## Features

- MATLAB-based dynamic simulation of DC motor
- Synthetic dataset generation with labeled time-series data
- Neural network classifier using fitcnet in MATLAB
- Visualization of output signals and confusion matrices


## Requirements

- MATLAB R2021a or later
- Statistics and Machine Learning Toolbox
- Control System Toolbox

## Results

The trained neural network classifier achieved:
- Test Accuracy: 81.67%
- Correct classification of all healthy and most faulty signals
- Clear distinction between noise-induced and mechanical faults


## Author

Safa Bazrafshan  
Independent Researcher  
Email: safa.bazrafshan@gmail.com

---

*Feel free to use or extend this project for academic, industrial, or personal learning purposes.*
