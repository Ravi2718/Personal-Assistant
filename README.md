# Personal-Assistant

## Overview

This Python script creates a voice assistant named SID that performs various tasks based on user voice commands. It can open websites, send emails, provide motivational quotes, play music, and fetch information from WolframAlpha or Wikipedia.

## Features

- **Voice Interaction**: Uses text-to-speech for responses and speech recognition for commands.
- **Website Access**: Opens YouTube, Google, and Gmail.
- **Motivational Quotes**: Provides a selection of motivational quotes upon request.
- **Email Functionality**: Sends emails using Gmail's SMTP server.
- **Music Playback**: Plays music from specified folders based on language preferences.
- **Information Retrieval**: Retrieves information from WolframAlpha or Wikipedia.

## Requirements

- Python 3.x
- Required Python libraries:
  - `pyttsx3`
  - `speech_recognition`
  - `wikipedia`
  - `wolframalpha`

## Installation

1. **Install Required Libraries**:
   ```bash
   pip install pyttsx3 speech_recognition wikipedia wolframalpha
   ```

2. **API Key Setup**:
   - Replace `XXXXXXXXXXXXXXXXXXX` with your WolframAlpha API key in the script.

3. **Email Configuration**:
   - Update the script with your Gmail credentials and recipient information for the email functionality.

## Usage

1. **Run the Script**:
   ```bash
   python your_script_name.py
   ```

2. **Commands**:
   - Speak or type commands such as "open YouTube," "send email," "play music," "what time is it," etc.
   - The assistant will respond and execute actions based on the commands.

## Important Notes

- **Email Functionality**: Ensure correct configuration of email credentials to avoid sending unintended messages.
- **Music Playback**: Verify that music file paths are correct and accessible.
- **Shutdown Command**: Use with caution, as the script includes a shutdown command in certain scenarios.

