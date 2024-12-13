Overview:

This project is a Speech-to-Speech Translation System that uses Large Language Models (LLMs) to translate text between multiple languages and provides audio output of the translated text. It combines a user-friendly interface with robust backend capabilities powered by Flask and Transformer-based machine learning models.

Features:

Real-Time Translation: Translate text from one language to another.

Speech-to-Text and Text-to-Speech: Convert spoken words into text and provide audio output for translated text.

Wide Language Support: Supports a variety of languages for translation.

Interactive UI: Responsive and visually appealing interface built using HTML and CSS.

Technologies Used:

Frontend

HTML: Structuring the web interface.

CSS: Styling the interface to ensure a modern and responsive user experience.

JavaScript: Handling user interactions like starting/stopping speech recognition and triggering translation requests.

Backend

Flask: Lightweight Python web framework to manage the server-side logic and API endpoints.

PyTorch & Transformers: Leveraging pre-trained models from the transformers library for language translation.

gTTS: Generate audio files for the translated text.

Files and Directories:

index.html: Defines the structure and layout of the user interface.

style.css: Provides styling to the web interface, ensuring a sleek and user-friendly design.

app.py: Backend logic for handling translation, text-to-speech, and communication with the frontend.

How It Works:

Input:

Users can either speak or type the text to be translated.

Select source and target languages from dropdown menus.

Processing:

The text is sent to the Flask backend via an API call.

The backend uses a pre-trained Transformer model (MBART) to translate the text.

Translated text is converted into speech using the gTTS library.

Output:

Translated text is displayed on the screen.

Audio of the translated text is played in the target language.

