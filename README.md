# Text Summarization Web App

## Overview

This project is a web application for text summarization built using [SpaCy](https://spacy.io/) and [Flask](https://flask.palletsprojects.com/). The application allows users to input a block of text and receive a concise summary, leveraging natural language processing techniques.

## Features

- User-friendly web interface for inputting text
- Automatic text summarization using SpaCy
- Clear and concise output summaries
- Easy to deploy and extend

## Installation

### Prerequisites

- Python 3.7 or later
- [pip](https://pip.pypa.io/en/stable/)

### Steps

1. Clone the repository:
    ```sh
    git clone https://github.com/Ahana19/TextSummarizerWebApp
    cd text-summarization-web-app
    ```

2. Create a virtual environment:
    ```sh
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:


4. Download the SpaCy language model:
    ```sh
    python -m spacy download en_core_web_sm
    ```

## Usage

1. Run the Flask application:
    ```sh
    python app.py
    ```

2. Open your web browser and go to `http://localhost:3000/home`.

3. Enter the text you want to summarize and click the "Summarize" button.

