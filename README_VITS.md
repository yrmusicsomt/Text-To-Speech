
# VITS Inference - Multi-Speaker Voice Conversion

This repository provides a Jupyter Notebook for **multi-speaker voice conversion** using **VITS (Variational Inference Text-to-Speech)**.

## Overview

The notebook demonstrates how to apply **VITS** for generating and converting speech using different speaker voices.

## Features

- Multi-speaker voice conversion
- Pre-trained **VITS** model usage
- Supports phonemization and prosody modeling

## Installation

Clone the VITS repository and install dependencies:

```bash
git clone https://github.com/jaywalnut310/vits.git
cd vits
pip install -U -r requirements.txt
pip install Cython librosa matplotlib numpy phonemizer scipy tensorboard torch torchvision Unidecode
```

## Usage

1. Run the Jupyter Notebook `6A_VITS_inference.ipynb`.
2. Load the pre-trained VITS model.
3. Provide input text or audio for voice conversion.
4. Generate the output speech file.

## Dependencies

- PyTorch
- librosa
- phonemizer
- scipy

## References

- [VITS GitHub Repository](https://github.com/jaywalnut310/vits)
