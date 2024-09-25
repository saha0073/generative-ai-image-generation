# Image Generation Chatbot

![Image Generation Chatbot](Images/chatbot_interface.png)

## About

This Image Generation Chatbot is a Streamlit application that uses OpenAI's DALL-E 3 model to generate images based on user prompts. It provides an interactive chat interface where users can describe the image they want, and the AI will generate and display the image in real-time.

## Features

- Interactive chat interface
- Real-time image generation using DALL-E 3
- Chat history persistence
- Responsive design

## Sample Generated Images

Here are some examples of images generated by the chatbot:

<div style="display: flex; justify-content: space-around;">
  <img src="Images/raining_paris.jpg" alt="Sample Image 1" width="30%">
  <img src="Images/amazon_rainforest.jpg" alt="Sample Image 2" width="30%">
  <img src="Images/spacex_starship.jpg" alt="Sample Image 3" width="30%">
</div>


## Run the Streamlit app:
   ```
   streamlit run image_gen.py
   ```

## Usage

1. Enter a description of the image you want to generate in the chat input.
2. Press Enter or click the send button.
3. Wait for the AI to generate and display the image.
4. Continue the conversation or start a new one for more image generations.

## Technologies Used

- Python
- Streamlit
- OpenAI API (DALL-E 3)
- Pillow (PIL)
- python-dotenv
