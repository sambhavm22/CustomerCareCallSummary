# Customer Care Call Summarization

This project provides a streamlined solution for summarizing customer care call recordings and emailing the summaries automatically. By leveraging cutting-edge AI technologies, this app performs audio transcription, summarization, and email automation seamlessly.


## Features

- **Audio Transcription**: Converts `.mp3` call recordings to text using the OpenAI Whisper model.
- **AI-Powered Summarization**: Utilizes OpenAI's GPT-based models for summarizing the transcription.
- **Email Automation**: Sends summarized call information to specified email addresses via Zapier integration.
- **User-Friendly Interface**: A simple and intuitive Streamlit-based frontend for uploading and processing files.


## Prerequisites

Ensure you have the following environment variables set:

1. `OPENAI_API_KEY`: Get your API key from [OpenAI's API platform](https://platform.openai.com/).
2. `ZAPIER_NLA_API_KEY`: Obtain your Zapier NLA API key from the [Zapier NLA Documentation](https://nla.zapier.com/docs/authentication/).

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/sambhavm22/CustomerCareCallSummary.git
   cd CustomerCareCallSummary

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

3. Run the app:
   ```bash
   streamlit run app.py
  
## Usage

1. Upload Audio Files: Use the app's interface to upload one or more .mp3 files.
2. View Uploaded Files: Uploaded files are displayed in a table.
3. Email Summaries: Click the "Send Email" button for each file to transcribe, summarize, and send the results via email.
4. Success Message: A success message will be displayed upon successful email delivery.

## File Structure
1. app.py: Main entry point for the Streamlit application.
2. utils.py: Contains utility functions (e.g., audio processing, summarization).
3. requirements.txt: Lists all required Python packages.

## Key Dependencies
1. ffmpeg-python: For handling audio files.
2. openai-whisper: For transcription of audio to text.
3. langchain: For managing and utilizing LLM agents.
4. streamlit: For creating the web-based user interface.
5. openai: For interacting with OpenAI's GPT models.


## Troubleshooting
1. Environment Variables Not Found: Ensure that OPENAI_API_KEY and ZAPIER_NLA_API_KEY are correctly set in your environment.
2. Dependency Errors: Verify that all dependencies are installed using the command

## License
This project is licensed under the MIT License. See the LICENSE file for details.

--- 
#### For more detail read my blog:
https://sambhavm22.medium.com/customer-care-call-summarisation-6cd589015f90

Feel free to reach out for support or improvements! 🚀
