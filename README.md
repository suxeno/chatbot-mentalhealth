# Chatbot using TFxIDF and Cosine Similarity

## Overview

This repository contains a simple chatbot program that utilizes TFxIDF (Term Frequency-Inverse Document Frequency) and cosine similarity metrics to match user questions with a provided dataset. The chatbot aims to provide responses based on the closest match found within the dataset.

## Features

- **TFxIDF Calculation**: The chatbot utilizes TFxIDF to represent text data and measure the importance of words within the dataset.
- **Cosine Similarity**: Cosine similarity is employed to determine the similarity between user input and the questions in the dataset.
- **Dataset**: The chatbot relies on a dataset containing questions and corresponding answers, which serves as the knowledge base for generating responses.
- **Interactive Interface**: Users can interact with the chatbot by inputting questions through a command-line interface or any other suitable user interface implemented.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/suxeno/chatbot-mentalhealth.git
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

1. Ensure you have Python installed on your system.
2. Navigate to the directory where you cloned the repository.
3. Run the chatbot program:

```bash
python chatbot.py
```
