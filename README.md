# Wake Word  "komputer" model

This repository contains a series of Jupyter Notebooks for training Neural Networks (NN) to detect the wake word "komputer". The purpose of this wake word detection system is to identify instances of the word "komputer" in an audio stream, which can be used to trigger actions or commands in voice-activated systems.

## Table of Contents

- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Getting Started

The project utilizes deep learning techniques for detecting the wake word in audio signals. The model is trained using a dataset of audio samples containing the wake word "komputer" as well as other background noises and words to ensure robustness in real-world applications.

## Prerequisites

- Python 3.x
- Jupyter
- TensorFlow 2.x
- Librosa
- NumPy
- Matplotlib

## Installation

1. Clone this repository.

    ```sh
    git clone [https://github.com/yourusername/wake-word-detection.git](https://github.com/chwalap/wake-word-komputer-model.git)
    ```

2. Navigate to the cloned directory.

    ```sh
    cd wake-word-komputer-model
    ```

3. Install the required Python packages.

    ```sh
    pip install -r requirements.txt
    ```

4. Launch Jupyter Notebook.

    ```sh
    jupyter notebook
    ```

## Project Structure

The project contains several Jupyter Notebooks:

- `Preprocessing.ipynb`: Contains code for loading and preprocessing the audio data.
- `Training.ipynb`: Contains code for defining, training, and evaluating the neural network.

## Usage

1. Start by opening `Preprocessing.ipynb`. Execute the cells to preprocess your audio data. Ensure that you have the audio dataset in the required directory.

2. Open `Training.ipynb`. Execute the cells to train the Neural Network on your preprocessed data. You can experiment with different architectures and hyperparameters.

3. The trained model will be able to detect the wake word "komputer" in audio streams. You can integrate it into your applications as required.


*Note: Please make sure to provide proper credits and references if you are using data or code from other sources.*
