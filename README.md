# Chatbot using Pretrained LLM and Gradio Interface

This project implements a simple chatbot using a pretrained language model and a user-friendly interface built with Gradio. Code available in the ``chatbot.ipynb`` file.

## Features

- Loads a pretrained LLM from Hugging Face (`gpt2-medium`)
- Uses Gradio's `ChatInterface` for interactive conversation
    * Input: User message (text)
    * Output: Model-generated reply
    * Session memory for chat history
- Handles user messages and generates coherent responses
- Clean and lightweight setup

## Tech Stack

- Python
- PyTorch
- Hugging Face Transformers
- Gradio

## Environment

The environment configuration is provided for reproducibility:

``environment.yml`` - for setting up with Conda.
``requirements.txt`` - for installing dependencies with pip.