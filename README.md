# Audio Classification with PyTorch 🎙️🤖

This project demonstrates **audio classification** using **PyTorch** on the **ESC-50 dataset**. The goal is to classify environmental sounds into 50 different categories using a convolutional neural network (CNN). 🎯📊

---

## Table of Contents 📑
1. [Overview](#overview-)
2. [Installation](#installation-)
3. [Usage](#usage-)
4. [Code Structure](#code-structure-)
5. [Results](#results-)
6. [License](#license-)

---

## Overview 🚀

This project:
- Uses **PyTorch** to build and train a CNN for audio classification. 🤖🎙️
- Leverages the **ESC-50 dataset** for training and validation. 🧠🔍
- Implements spectrogram transformation, model training, and evaluation. 📊📉

---

## Installation 🛠️

To run this project, you need to install the required libraries. Run the following commands:

```bash
!pip install torch torchaudio matplotlib
!apt install sox
```

---

## Usage 🖥️

1. **Load Dataset**: The script downloads and loads the ESC-50 dataset.
2. **Preprocess Data**: Applies spectrogram transformation and splits the data into training, validation, and test sets.
3. **Build Model**: Defines and trains a CNN for audio classification.
4. **Evaluate Model**: Evaluates the model's performance on the validation set.
5. **Visualize Results**: Plots waveforms and spectrograms for analysis.

---

## Code Structure 🗂️

- **Data Preparation**:
  - Downloads and preprocesses the ESC-50 dataset.
  - Applies spectrogram transformation and splits the data into training, validation, and test sets.

- **Model Definition**:
  - Defines a CNN with convolutional and fully connected layers.
  - Uses cross-entropy loss for training.

- **Training**:
  - Trains the model using the training set.
  - Tracks training and validation loss.

- **Evaluation**:
  - Evaluates the model's performance on the validation set.
  - Visualizes results using waveforms and spectrograms.

---

## Results 📊

- **Training/Validation Loss**: The model achieves low training and validation loss.
- **Spectrogram Visualization**: Visualizes audio data as spectrograms for analysis.

---

## License 📜

This project is licensed under the **MIT License**. Feel free to use, modify, and distribute it as needed.

---

## Example Output 🖼️

Here’s an example of the model's training progress:

```plaintext
Epoch 1/10: Training Loss: 0.123, Validation Loss: 0.045
Epoch 2/10: Training Loss: 0.045, Validation Loss: 0.032
```

---

## Dependencies 📦

- `torch`
- `torchaudio`
- `matplotlib`
- `sox`

---

## Author 👨‍💻

This project was created by **[Navid Falah](https://github.com/navidfalah)**. Feel free to reach out for questions or collaborations at **navid.falah7@gmail.com**! 🤝
