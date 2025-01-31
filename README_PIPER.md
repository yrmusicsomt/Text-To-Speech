
# Piper TTS - Text-to-Speech Inference

This repository contains a Jupyter Notebook for generating speech using the **Piper TTS** model.

## Overview

**Piper TTS** is an efficient text-to-speech (TTS) system that converts text input into high-quality speech.

## Features

- Lightweight and fast inference
- Supports multiple models and languages
- Converts text input to speech audio

## Installation

Install Piper TTS with:

```bash
pip install piper-tts
```

## Usage

Run the following command to generate speech:

```bash
echo 'Welcome to the world of speech synthesis!' | piper --model en_US-lessac-medium --output_file welcome.wav
```

To use the notebook:
1. Open `6B_Piper_TTS.ipynb` in Jupyter Notebook.
2. Load the Piper TTS model.
3. Provide input text for speech generation.
4. Save the output as a WAV file.

## Dependencies

- Piper TTS
- Torch (if using GPU acceleration)
