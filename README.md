# BERT-Text-Classification-Model-with-Gradio

# BERT Text Classification with Gradio

This project demonstrates how to use a pre-trained BERT model for text classification using the `transformers` library by Hugging Face and create a user-friendly interface using Gradio. The model classifies text into positive or negative sentiments.

## Overview

The project includes:
1. Loading a pre-trained BERT model (`bert-base-uncased`) for sequence classification.
2. Defining an inference function to classify input text.
3. Creating a Gradio interface to interact with the model.
4. Testing the interface with example texts.

## Setup Instructions

### Prerequisites

Ensure you have the following installed:
- Python 3.6 or higher
- `pip` package manager

### Dependencies

Install the necessary Python packages using the following command:
```sh
pip install transformers torch gradio
