# Emergency vs Non-Emergency Vehicle Sound Classification

This repository contains work on classifying audio data to distinguish between emergency and non-emergency vehicle sounds. The project explores audio representation in both the time domain and as spectrograms, and builds a deep learning model for audio classification.

## Project Overview

- **Goal:** Classify audio samples as either emergency vehicle sounds (like sirens) or non-emergency vehicle sounds.
- **Approach:** 
  - Load and process raw audio data.
  - Visualize and analyze audio signals in both the time domain and frequency domain (spectrograms).
  - Build and evaluate a deep learning model for classification.
- **Main Notebook:** `Emergency_and_Non_emergency_audio_classification.ipynb`

## Repository Structure

- `Emergency_and_Non_emergency_audio_classification.ipynb` - Main Jupyter Notebook containing code for data processing, visualization, modeling, and evaluation.
- `data/` - (Recommended) Directory to store audio files and datasets.
- `models/` - (Optional) Directory to save trained models.
- `README.md` - Project documentation.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Recommended libraries:
  - numpy
  - pandas
  - matplotlib
  - librosa
  - tensorflow or pytorch (depending on model implementation)
  - scikit-learn

Install dependencies using pip:
```bash
pip install numpy pandas matplotlib librosa tensorflow scikit-learn
```

### Running the Notebook

1. Clone the repository:
    ```bash
    git clone https://github.com/manola1109/Project---Emergency-vs-Non-Emergency-Vehicle-Sound-Classification.git
    cd Project---Emergency-vs-Non-Emergency-Vehicle-Sound-Classification
    ```
2. Start Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
3. Open and run `Emergency_and_Non_emergency_audio_classification.ipynb`.

## Dataset

- The audio data should be placed in the `data/` directory.
- Data includes both emergency (e.g., sirens) and non-emergency vehicle sounds.

## Results

- The notebook provides visualizations of audio waveforms and spectrograms.
- Model evaluation metrics (accuracy, confusion matrix, etc.) are displayed to assess classification performance.

## Contributing

Contributions are welcome! Please fork the repo and submit a pull request.

## License

This project is for educational purposes.

---

*Work with the audio data. Represent an audio data - Time Domain and Spectrogram. Build a deep learning model while working with audio data.*
