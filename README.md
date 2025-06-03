# Intro2SDR_Ex0

# FM Receiver using GNU Radio

## Overview

This project is submitted as **Assignment 0** for the *Introduction to Software Defined Radio (intro2sdr)* course. The goal was to get familiar with GNU Radio and RTL-SDR hardware by implementing a working signal processing application. For this purpose, I developed a simple **FM receiver**.

The application allows tuning to any FM radio frequency in the 88–108 MHz band using a slider and outputs real-time audio via your computer’s speakers. It also saves the received audio to a `.wav` file.

## Features

- Uses an **RTL-SDR USB dongle** as the SDR front-end.
- Real-time **FM demodulation** and audio playback.
- **Frequency slider** to tune in to any FM station.
- GUI elements for visualizing the signal:
  - Frequency Spectrum
  - Waterfall Display
  - Time-domain Signal
- **Audio recording** to a WAV file (included in the repository).

## Files

- `Ex0.grc` — The original GNU Radio Companion (GRC) flowgraph file.
- `Ex0.py` — Auto-generated Python flowgraph (used for execution).
- `ex0-audio.wav` — Recorded audio file of the FM receiver in action.

## Requirements

- GNU Radio 3.10+
- RTL-SDR dongle (and appropriate drivers)
- Python 3.x
- PyQt5 (for GUI support)

## Running the Project

1. **Connect** your RTL-SDR dongle to your machine.
2. **Launch** the Python script:
   ```bash
   python3 Ex0.py
