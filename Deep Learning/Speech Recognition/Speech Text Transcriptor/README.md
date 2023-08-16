Speech to Text Transcription using Nvidia Quartznet

# Business Overview
As you can think, speech is essential to both our personal and professional life on a
daily basis, and voice-to-text technology has a wide range of uses. It can be used to
record meetings and other discussions, transcribe customer service or sales calls,
create voice-activated chatbots, and more.
Enhanced productivity is the main advantage of voice recognition applications. Without
manually entering any data into a computer, users can dictate documents, email
responses, and other content.
By removing one barrier between a user's thoughts and their digital output,
speech-to-text technology can improve productivity by streamlining corporate
procedures and saving time.
This project involves building a model by utilizing learning from Nvidia QuartzNet
models to develop a speech-to-text transcriptor.

# Aim
To use Nvidia Quartznet models for automatic speech recognition and build a
speech-to-text transcriptor.
Data Description
LibriSpeech is a corpus of approximately 1000 hours of 16kHz read English speech,
prepared by Vassil Panayotov with the assistance of Daniel Povey.

# Tech Stack
➔ Language: Python
➔ Libraries: pandas, matplotlib, tensorboard, librosa, torchaudio, torch, jiwer,
PyYAML

# Approach
● Data Preparation
○ Audio Formats
○ Data Labelling
● Model Architecture
● Requirements
● Configuration
○ Configuration file for the project
● Data Loading
● Utils
○ Model Creation
○ Audio to Mel Spectrogram
○ Encode/Decode
● Model Training
● Testing
● Nvidia Quartz Net Demo
○ Model Loading
○ Youtube Data Preparation
○ Transcription Results
