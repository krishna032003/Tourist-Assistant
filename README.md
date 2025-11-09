# 🌍 AI Tourist Assistant

This is a voice-enabled AI tourist assistant built with Python, Gradio, and Google's free-tier APIs. It can answer questions about locations, find nearby attractions, and even read information from a custom knowledge base.

## Features

- **Conversational AI:** Uses Google's Gemini model to provide natural answers.
- **Voice-Enabled:** Supports both text and voice input (Speech-to-Text) and provides spoken responses (Text-to-Speech).
- **Location Aware:** Integrates with the Google Places API to find nearby attractions.
- **Knowledge Base (RAG):** Can read from PDF documents placed in the `knowledge-base` folder to answer specific questions.

## Setup

1.  Clone this repository:

    ```bash
    git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)
    cd YOUR_REPO_NAME
    ```

2.  Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

3.  Create a `.env` file in the main folder and add your API keys:

    ```env
    GOOGLE_API_KEY="YOUR_GEMINI_API_KEY"
    GOOGLE_PLACES_API_KEY="YOUR_GOOGLE_PLACES_KEY"
    ```

4.  (Optional) Add PDF files to the `knowledge-base` folder.

5.  Run the `tourist.ipynb` notebook in VS Code or Jupyter.
