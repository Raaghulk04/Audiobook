# Audiobook
# PDF to Speech Converter (Python)

This project is a simple Python script that converts any PDF file into spoken audio using the pyttsx3 text-to-speech engine.
It extracts text from each page of the PDF and reads it aloud sequentially.

# Features

* Converts PDF text into speech

* Reads any number of pages

* Works offline (no API required)

* Simple graphical file picker using tkinter

* Uses the updated PdfReader API (PyPDF2 ≥ 3.0)

# How It Works

* A file dialog opens and lets you select a PDF file.

* The script reads the PDF using PyPDF2's PdfReader.

* It extracts text from each page.

* The pyttsx3 speech engine speaks the extracted text out loud
