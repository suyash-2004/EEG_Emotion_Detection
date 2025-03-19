# NeuroSri : EEG-POWERED AI ROBOT FOR MENTAL HEALTH DETECTION AND THERAPY

This project implements a real-time EEG-based emotion recognition system integrated with a therapeutic chatbot. The system processes EEG signals using LSL (Lab Streaming Layer), performs frequency analysis, classifies emotions using deep learning, and provides therapeutic responses through a chatbot interface.

## Features
- Real-time EEG data acquisition using LSL
- Frequency domain analysis (Delta, Theta, Alpha, Beta, Gamma waves)
- Deep learning-based emotion classification
- Interactive therapeutic chatbot using g4f

## Project Structure
```
.
├── data/                  # Data storage directory
├── models/               # Trained models directory
├── src/
│   ├── eeg/             # EEG processing modules
│   ├── ml/              # Machine learning modules
│   ├── chatbot/         # Chatbot implementation
│   └── utils/           # Utility functions
└── config/              # Configuration files
```

## Setup
1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Configure LSL stream settings in config/settings.py
3. Run the main application:
```bash
python src/main.py
```

## Requirements
- Python 3.8+
- CHORDS LSL compatible EEG device
- Required Python packages listed in requirements.txt 