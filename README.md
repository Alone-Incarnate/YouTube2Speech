# YouTube Video to Audio, Transcription, and Text-to-Speech Conversion

This project automates the entire process of downloading YouTube videos, extracting audio, transcribing the audio to text, and converting the text back into speech. Perfect for creating accessible content or transforming video content into audio format!

## 🚀 Features

- **Video Download**: Efficiently download high-quality YouTube videos using the `yt-dlp` library.
- **Audio Extraction**: Extract and save audio from videos as WAV files with `moviepy`.
- **Audio Transcription**: Leverage Deepgram's powerful AI to convert audio content into text.
- **Speech Generation**: Use Eleven Labs API to generate natural-sounding speech from text.

## 📋 Prerequisites

Before using this project, ensure you have the following:

- **Python 3.6+** installed on your system.
- **API Keys** for:
  - [Deepgram API](https://deepgram.com)
  - [Eleven Labs API](https://elevenlabs.com)


## 📖 Usage Instructions
Download YouTube Video: Provide the URL of the YouTube video you wish to process.
Extract Audio: The script will automatically extract audio from the downloaded video.
Transcribe Audio: Transcription is handled via the Deepgram API, converting audio into text.
Generate Speech: Use Eleven Labs to convert the transcription back into speech.

## ⚙️ Configuration
Before running the script, update your API keys in the script:


## 🧐 How It Works
Download Step: Videos are downloaded from YouTube in the best available quality.
Audio Extraction Step: Extract audio from videos and save as WAV files.
Transcription Step: Send the audio file to the Deepgram API for transcription.
Speech Generation Step: Convert transcribed text into speech using the Eleven Labs API.

## 📝 Notes
Ensure you have valid API keys for both Deepgram and Eleven Labs.
The script saves output files (video, audio, transcription, and speech) in the specified directory.

## 📄 License
This project is open-source and available for use under the MIT License.

Enjoy automating your video, audio, and transcription workflows!
