YouTube Video to Audio, Transcription, and Text-to-Speech Conversion
This project automates the following tasks:

Download YouTube Video: Download videos from YouTube using the yt-dlp library.
Extract Audio: Extract audio from the downloaded video using moviepy.
Transcribe Audio: Transcribe the extracted audio into text using the Deepgram API.
Text-to-Speech Conversion: Convert the transcribed text into speech using the Eleven Labs API.
Features
Video Download: Efficiently download the highest quality YouTube videos.
Audio Extraction: Extract audio from video files and save them as WAV files.
Audio Transcription: Utilize the power of Deepgram's AI to convert audio into text.
Speech Generation: Generate natural-sounding speech from text using Eleven Labs.
Prerequisites
To use this project, you need:

Python 3.6+ installed on your system.
API Keys for:
Deepgram API
Eleven Labs API
Installation
Clone this repository or download the script.
Install the required dependencies by running:

Usage Instructions
Download YouTube Video: Provide the URL of the YouTube video.
Extract Audio: The script will automatically extract the audio from the downloaded video.
Transcribe Audio: Audio will be transcribed into text using Deepgram.
Generate Speech: Convert the transcription into speech using Eleven Labs.
Configuration
Before running the script, replace the placeholders for DEEPGRAM_API_KEY and ELEVEN_LABS_API_KEY in the script with your actual API keys.

How It Works
Download Step: The video is downloaded from YouTube in the best available quality.
Audio Extraction Step: Audio is extracted from the video and saved as a WAV file.
Transcription Step: The audio file is sent to the Deepgram API for transcription.
Speech Generation Step: The transcribed text is converted back into speech using the Eleven Labs API.
Notes
Ensure you have valid API keys for both Deepgram and Eleven Labs.
This script saves the output files (video, audio, transcription, and generated speech) in the specified directory.
License
This project is open-source and available for use under the MIT License.

Enjoy automating your video, audio, and transcription workflows!
