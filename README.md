

# F1 Lap Time Prediction Model

A machine learning project that predicts Formula 1 lap times using real race data from the 2024 Bahrain Grand Prix.

## Overview

This project builds a predictive model that analyzes F1 race data to predict optimal lap times for each driver using Gradient Boosting regression.

## Dataset

Uses 2024 Bahrain Grand Prix data with 1,127 valid laps from 20 drivers. Data includes lap times, tire compounds, and driver performance metrics from the FastF1 library.

## Performance

Achieves 96.07% accuracy with 1.89 seconds mean error. Successfully predicts lap times within 2-6 seconds of actual fastest laps.

## Installation

```bash
pip install fastf1 pandas scikit-learn numpy
```

## Usage

Clone repository, install dependencies, and run the main script to see predictions vs actual lap times.

## Links

- **Blog Post**: [Read the detailed blog about this project](https://medium.com/@darshan11patil3/build-a-machine-learning-model-to-predict-lap-times-in-f1-races-8b1a9e96eb90)
- **Dataset Source**: [FastF1 Library](https://github.com/theOehrly/Fast-F1)

## Note
This project is in the initial development phase and continuously improving. Feedback and suggestions for enhancement are welcome as the model evolves.
