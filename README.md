# Chatbot_by_AI
# ChatBotAI: Interactive Chatbot with OpenAI GPT-3.5-turbo and Gradio
## Overview

ChatBotAI is an interactive chatbot built using the powerful OpenAI GPT-3.5-turbo model, capable of generating contextually relevant responses to user input. Leveraging the user-friendly Gradio library, this project provides a web-based interface that allows users to engage in seamless conversations with the AI-powered assistant.

## How to Use

1. Visit the [ChatBotAI Demo](https://59c989bde74d00b97a.gradio.live) to access the web-based chat interface.
2. Engage with ChatBotAI by typing messages and initiating conversations.
3. Experience the remarkable AI-driven responses as the assistant takes on the role of a knowledgeable senior professor.

## Installation and Local Development

To run ChatBotAI locally and experiment with different configurations:

1. Clone this repository to your local machine.
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Replace `YOUR_OPENAI_API_KEY` in `main.py` with your valid OpenAI API key.
4. Run the application using `python gradio_interface.py`.
5. Access the chatbot interface at `http://localhost:5000` in your web browser.

## Files Included

1. `main.py`: This file contains the code for the backend of the chatbot application. It sets up the communication with the OpenAI GPT-3.5-turbo model and defines the interaction between the user and the AI assistant.

2. `gradio_interface.py`: This file defines the Gradio user interface for the chatbot. It takes user input and calls the `main.py` file to get the AI-generated response, displaying it back to the user in real-time.

3. `requirements.txt`: This file lists the required Python dependencies for running the project. Install these dependencies using `pip install -r requirements.txt` before running the chatbot.

## Features

- **Intelligent Conversations**: ChatBotAI embodies the persona of a senior professor with expertise in every subject, enabling dynamic and insightful conversations.
- **Real-time Responses**: Users can interact with ChatBotAI in real-time, receiving prompt replies powered by the GPT-3.5-turbo model.
- **Easy Integration**: The Gradio-based web interface ensures a simple and intuitive experience for users to chat with the AI assistant.
- **Customizable Persona**: Developers can fine-tune the persona of the assistant for specific use cases, tailoring its responses as needed.

## Contributions

We welcome contributions to enhance ChatBotAI's capabilities, improve the user interface, or optimize its performance. To contribute, follow these steps:

1. Fork this repository and create a new branch for your feature or bug fix.
2. Make your changes and test thoroughly.
3. Submit a pull request, explaining your changes and improvements.

## Acknowledgments

ChatBotAI was made possible by the incredible capabilities of the OpenAI GPT-3.5-turbo model and the simplicity of the Gradio library for creating delightful user experiences.

