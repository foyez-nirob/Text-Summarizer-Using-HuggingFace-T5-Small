Dialogue Text Summarizer using T5-small

A simple dialogue summarization application built by fine-tuning a pretrained T5-small model from Hugging Face. The application takes a conversation as input and generates a concise summary.

Project Overview

This project explores Transformer-based text summarization using the T5-small model. I fine-tuned the pretrained model on a dialogue summarization dataset using a smaller subset of the original data due to limited computational resources.

The trained model is deployed through a simple web interface built with HTML, CSS, JavaScript, and FastAPI.

Technologies Used

Python

PyTorch

Hugging Face Transformers

T5-small

FastAPI

HTML, CSS, JavaScript

Dataset

Used a SAMSum dataset for fine-tuning.

For this project, I used:

4,000 training samples

500 validation samples

A smaller subset was selected to reduce training time and computational requirements.

Project Structure

Text-Summarizer/
│
├── Text_Summarizer.ipynb  # Model training and fine-tuning
├── app.py                 # FastAPI backend
├── index.html             # Web interface
├── requirment.txt         # Dependencies
├── saved_model/           # Fine-tuned model and tokenizer
└── README.md

Installation and Usage

1. Clone the repository

git clone https://github.com/foyez-nirob/Text-Summarizer-Using-HuggingFace-T5-Small.git

cd Text-Summarizer-Using-HuggingFace-T5-Small

2. Install dependencies

pip install -r requirment.txt

3. Run the FastAPI application

uvicorn app:app --reload

4. Open the application

Visit the following URL in your browser:

http://127.0.0.1:8000

Built as part of my journey into Generative AI and Large Language Models.
