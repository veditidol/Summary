# Image Text Extraction and Summarization 

This project uses **EasyOCR**, **spaCy**, and **Hugging Face Transformers** to extract text from images and provide a summarized version of the extracted text. It is built using **Flask** to serve as a simple API for frontend integration.

## Features

- **Text Extraction**: Uses EasyOCR to extract text from an image uploaded by the user.
- **Named Entity Recognition (NER)**: Uses spaCy's pre-trained models to identify names in the text.
- **Date and Time Extraction**: Extracts time and date from the text and associates them with the speaker and the conversation.
- **Summarization**: Uses the **facebook/bart-large-cnn** model to summarize the extracted text.
- **Flask API**: A simple REST API that allows frontend teams to upload images and retrieve summaries.

## Prerequisites

- Python 3.6+
- pip (Python package manager)

## Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
