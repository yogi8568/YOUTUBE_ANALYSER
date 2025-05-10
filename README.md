# YouTube Video Finder with Analysis 🎬

A Python automation tool that finds and analyzes YouTube videos based on voice or text input in Hindi or English, using AI to recommend the best matching video.

## Features ✨

- 🎙️ **Voice input** support in Hindi or English
- ✍️ **Text input** alternative
- 🔍 **Smart YouTube search** with filters:
  - Videos between 4-20 minutes
  - Published within last 14 days
  - Top 20 relevant results
- 🤖 **AI-powered analysis** using Gemini 1.5 Flash
- 🌐 **Bilingual support** (Hindi/English)

## Installation ⚙️

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yogi8568/YOUTUBE_ANALYSER.git
   cd youtube_analyser

2. install dependencies
     ```bash
   pip install -r requirements.txt

3.Set up API keys:

Create a .env file in the project directory:

    ```bash
    YOUTUBE_API_KEY=your_youtube_api_key_here
    GEMINI_API_KEY=your_gemini_api_key_here

4.Usage 🚀
      Run the application:
  ```bash
      python youtube_finder.py

Choose input method:

1. Voice input
2. Text input
For voice input:

Speak clearly in Hindi or English when prompted

The system will automatically detect the language

For text input:

Type your query in Hindi or English

View results:

The system will display the best matching video with:

Title

Duration

Publication date

Direct YouTube link
