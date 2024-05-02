# AI-YouTube-Audio-Text-Synthesis

**Project Description:**
This Python script aims to download a YouTube video, extract its audio, convert the audio to text using the Deepgram API, and then generate new audio using the text with the voice of Eleven Labs. The script is designed to run in Google Colab for ease of access and collaboration.

**Features:**
1.Download YouTube Video: Utilizes the pytube library to download a YouTube video given its URL.
2.Extract Audio: Uses moviepy library to extract audio from the downloaded video.
3.Convert Audio to Text: Integrates with the Deepgram API to convert the audio file to text.
4.Generate Audio with Voice: Utilizes a library (e.g., gTTS) to generate new audio from the extracted text using the voice of Eleven Labs.

**Usage:**
Open the provided Google Colab notebook.
Replace the YouTube video URL with the desired video link.
Run each cell sequentially to execute the script step-by-step.
Ensure to have necessary API keys for accessing Deepgram API and any other required dependencies.
