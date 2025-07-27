# FFT Study

Fast Fourier Transform (FFT) learning project with interactive Jupyter notebooks and practical examples.

## Overview

This repository provides hands-on learning materials for understanding the Fast Fourier Transform (FFT) through interactive Python notebooks. Learn signal processing fundamentals with visual examples and real audio data analysis.

## Features

- **Interactive Notebooks**: Step-by-step FFT implementation and visualization
- **Real Audio Analysis**: Process actual audio files with FFT
- **Voice Processing**: F0 extraction using PyWORLD
- **Educational Content**: Clear explanations with mathematical formulas

## Notebooks

### 1. fft_test.ipynb
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rayramy04/fft-study/blob/main/fft_test.ipynb)

Interactive FFT learning with:
- Custom waveform generation (sin/cos waves)
- Wave composition and visualization
- FFT analysis of composite signals

### 2. f0_extraction.ipynb
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rayramy04/fft-study/blob/main/f0_extraction.ipynb)

Voice fundamental frequency extraction using:
- PyWORLD library for F0 analysis
- Real audio file processing
- Spectrogram visualization

## Getting Started

### Online (Recommended)
Click the "Open in Colab" badges above to run notebooks in Google Colab without any setup.

### Local Setup
1. Clone this repository
2. Install dependencies: `pip install -r requirements.txt`
3. Launch Jupyter: `jupyter notebook`

## Data

- `data/figure/`: Generated plots and visualizations
- `data/zundamon_sample.wav`: Sample audio file for analysis

## Live Demo

📖 **[Read the detailed explanation](https://rayramy04.github.io/fft-study/)**

## Requirements

- Python 3.7+
- NumPy, SciPy, Matplotlib
- Librosa for audio processing
- PyWORLD for voice analysis

## License

Educational use - feel free to learn and experiment!