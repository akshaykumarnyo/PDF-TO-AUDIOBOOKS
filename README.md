﻿# PDF-TO-AUDIOBOOKS
PDF to Audiobook
This is a simple Streamlit application that converts a PDF document into an audiobook. The application reads the content of a PDF file and displays the text word by word while reading it out loud using a text-to-speech engine.

Features
PDF Upload: Users can upload a PDF file of their choice.
Text-to-Speech: The application reads the PDF text aloud using the pyttsx3 library.
Word-by-Word Display: The text is displayed on the screen word by word in sync with the audio.
Interactive Interface: A user-friendly interface built with Streamlit.
Requirements
Python 3.6+
Required Python libraries:
pyttsx3: For text-to-speech conversion.
PyPDF2: For extracting text from PDF files.
streamlit: For building the web interface.
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/username/pdf-to-audiobook.git
cd pdf-to-audiobook
Install the required libraries:

bash
Copy code
pip install pyttsx3 PyPDF2 streamlit
Usage
Run the Streamlit application:

bash
Copy code
streamlit run app.py
Upload a PDF File:

Click the "Choose a PDF file" button and upload your PDF document.
Listen and Read:

The application will start reading the text aloud and display the words on the screen one by one.
Customization
Text-to-Speech Settings:
You can customize the voice, rate, and volume of the text-to-speech engine by modifying the pyttsx3 settings in the script.

Reading Speed:
Adjust the time.sleep() duration in the script to change the speed of word display.

Example

License
This project is licensed under the MIT License. See the LICENSE file for more details.
