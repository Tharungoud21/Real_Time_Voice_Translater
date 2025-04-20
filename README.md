<h2 style="text-align: left;"> 🔤 Project Overview: Language Translator with Voice Support </h2>
<p> This Python project creates a Language Translator GUI Application using Tkinter. It allows users to:

Translate text between languages.

Input speech and convert it to translated text.

Output translated text as speech.

It supports multiple languages using Google’s translation and speech services and is suitable for educational and practical language learning or communication aids.</p>
<h2>📦 Required Modules & Their Purpose</h2>
<p> from tkinter import *                 # GUI components (Text boxes, Buttons, Frames, etc.)
  <br>
from tkinter import ttk, messagebox   # Additional widgets (ComboBox), pop-up messages
<br>

import googletrans                    # For getting available language codes<br>
import textblob                       # For translation between languages<br>
from gtts import gTTS                 # Converts translated text to speech (mp3)<br>

import speech_recognition as sr       # Converts speech input to text<br>
from playsound import playsound       # Plays the mp3 audio file<br>
import os                             # File operations (e.g., delete audio after playing)</p>
