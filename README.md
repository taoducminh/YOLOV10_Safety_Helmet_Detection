# YOLOv10 Helmet Safety Fine-tuning

This repository contains a Jupyter Notebook for fine-tuning the YOLOv10 model for helmet safety detection. The notebook demonstrates the process of preparing the dataset, configuring the model, and training it to accurately detect helmets in images or video streams.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Helmet safety detection is crucial for ensuring compliance with safety regulations in various industries. This notebook provides a step-by-step guide to fine-tuning the YOLOv10 model to detect helmets with high accuracy.

## Features

- **YOLOv10 Model**: Utilizes the state-of-the-art YOLOv10 model for object detection.
- **Fine-tuning**: Customizes the model to improve helmet detection accuracy.
- **Dataset Preparation**: Instructions for preparing and annotating the dataset.
- **Training and Evaluation**: Code for training the model and evaluating its performance.

## Requirements

To run the notebook, you need the following dependencies:

- Python 3.8+
- Jupyter Notebook
- numpy
- pandas
- matplotlib
- opencv-python
- torch
- torchvision
- PyYAML
- tqdm

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/taoducminh/YOLOv10_Helmet_Safety_Finetuning.git
    cd YOLOv10_Helmet_Safety_Finetuning
    ```

2. Install the required Python packages:

    ```sh
    pip install -r requirements.txt
    ```

3. (Optional) Install Jupyter Notebook if you don't have it:

    ```sh
    pip install notebook
    ```

## Usage

1. Start Jupyter Notebook:

    ```sh
    jupyter notebook
    ```

2. Open the `YOLOv10_Helmet_Safety_Finetuning.ipynb` notebook and follow the instructions to run the cells.

3. Prepare your dataset and configure the model as instructed in the notebook.

4. Train the model and evaluate its performance.

## File Structure

- `YOLOv10_Helmet_Safety_Finetuning.ipynb`: The main notebook file for fine-tuning the YOLOv10 model.
- `requirements.txt`: List of required Python packages.
- `README.md`: This readme file providing an overview and instructions.

## Contributing

We welcome contributions to improve this project! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch-name`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-branch-name`.
5. Submit a pull request.


