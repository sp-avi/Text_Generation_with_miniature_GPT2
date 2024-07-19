# Text Generation Using Miniature GPT Model with IEMOCAP Database.

This repository contains code for a text generation model implemented using a miniature GPT architecture. The model is trained on transcriptions from the IEMOCAP database and is capable of generating text based on a given seed text.

## Table of Contents

### Introduction

This project demonstrates the use of a miniature GPT model for text generation. The model is built using TensorFlow and Keras and trained on the IEMOCAP database, which contains transcriptions of emotional dyadic interactions.

### Dataset

The IEMOCAP (Interactive Emotional Dyadic Motion Capture) database can be requested from the University of Southern California's website here. For this project, only the transcriptions are used.

### Installation

To run this project, you need to have Python installed along with the required libraries. You can install the dependencies using:

`pip install tensorflow numpy
`

### Usages
1.Clone the repository:

`git clone https://github.com/your_username/text-generation-miniature-gpt.git
cd text-generation-miniature-gpt
`
2.Download and preprocess the dataset:

Request and download the IEMOCAP dataset.
Extract the transcriptions and save them in a file named transcriptions.txt in the project directory.

3.Run the training script:

`python train.py
`

### Training

The training script will load the transcriptions, preprocess the text, and train the miniature GPT model. The model architecture includes embedding, LSTM layers, and a dense layer for generating the next word in the sequence.

### Text Generation

After training, you can generate text using the trained model. Run the following script to generate text:

`python generate_text.py
`
You can modify the generate_text.py script to change the seed text and the number of words to generate.

### Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or new features.


