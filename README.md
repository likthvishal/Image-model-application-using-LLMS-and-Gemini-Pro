# Gemini Pro End-to-End Generative AI Project

## Overview
This project leverages **Gemini Pro**, a multimodal language model, to build an end-to-end AI application capable of handling both **text and image data**. Gemini Pro is known for its powerful language generation and image processing abilities, making it ideal for a variety of use cases, including **text summarization, Q&A, documentation, and image analysis**.

## Features
1. **Text-Based Applications**: This includes functionalities such as Q&A, text summarization, and generative responses. The project demonstrates the power of Gemini Pro in creating coherent and contextually accurate responses based on various inputs.
2. **Image-Based Applications**: Gemini Pro, being a multimodal model, also enables image-related tasks. This includes generating descriptions of images and creating blog content based on images.
3. **Front-End and Back-End Integration**: The project uses **Streamlit** for the front-end and **Google Generative AI API** for back-end AI model interactions, creating a full-stack application.
4. **Real-Time AI Responses**: Gemini Pro processes 60 queries per minute, ensuring rapid response times and enabling interactive applications.

## Installation and Setup
1. Clone this repository:
   ```bash
   git clone [repo URL]

## Obtain your API key from Google:
Go to Google API Key and generate an API key.
Store the key in a .env file with the name GOOGLE_API_KEY.

## Usage

## Text-Based Use Case
**Run the text-based application:**
streamlit run app.py
Enter a prompt in the input box, such as "Write a poem on pandas," and click "Ask Question" to see the AI’s response.

## Image-Based Use Case
**Run the image-based application:**
streamlit run vision.py
Upload an image file and enter a prompt, such as "Describe the image" or "Generate a blog based on the image." Gemini Pro will generate detailed descriptions and context around the image.

## Project Files
**app.py:** Code for the text-based application using Streamlit.

**vision.py:** Code for the image-based application using Streamlit.

**.env:** File storing the Google API key for Gemini Pro.

**requirements.txt:** Dependencies needed for the project.
