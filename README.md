# Audio-Analysis
Audio data analysis is often necessary to extract meaningful and important information from a conversation recording, and also for analysing it later. Some analysis requires speech-to-text conversion, while others require even deeper information such as sentiment analysis to understand the speaker's sentiment, text summarization for a gist of the whole audio file, etc. This notebook contains a consolidated pipeline for the various aspects of conversation specific audio analysis, thus reducing time and effort required for the same.<br /><br />

This notebook is capable of performing the following operations on a .wav conversation audio file: <br />
• extraction of call duration <br />
• extraction of sample rate <br />
• extraction of number of channels <br />
• speech-to-text conversion <br />
• sentiment analysis <br />
• speaker time to silence time ratio <br />
• transcription text summarization <br /> <br />
### Prerequisites to running this notebook successfully:<br />
• Installation of python on the system <br />
• Editor access to GCP project with access to google APIs and storage bucket (if using Google APIs) <br />
• Microsoft account to use Azure cognitive services (if using Azure APIs) <br />
• Installation of FFmpeg on the system (if it's a Windows system) <br />
• Installation of various python packages listed in the beginning of the notebook <br /><br />
### Steps to run the notebook: <br />
• User inputs the path of the audio file that needs to be analyzed. <br />
• Details such as number of channels, sample rate and call duration are extracted. <br />
• User provides Google Application credentials (if using Google APIs) or Azure speech services credentials (if using Azure APIs). <br />
• Text-to-speech conversion is executed. <br />
• Sentiment analysis is done. <br />
• Text summarization is done. <br /><br />

The required instructions for installing FFmpeg and obtaining google/azure credentials are mentioned in AudioAnalytics_USER GUIDE.docx file. <br />
