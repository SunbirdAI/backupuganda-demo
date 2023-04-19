### Backup Uganda Text Translation and Speech Synthesis

This Streamlit application is designed for Backup Uganda to translate podcast transcripts from English to Luganda and perform speech synthesis on the translated text. The application leverages state-of-the-art natural language processing models to provide high-quality translations and speech synthesis results.

### Features

- Supports translation from English to Luganda
- Text can be input by uploading a file or manually entering text
- Uses Hugging Face's Sunbird/sunbird-en-mul model for translation
- Uses Sunbird/sunbird-lug-tts for text-to-speech synthesis in Luganda
- Provides an audio player to listen to the synthesized speech

### Installation

**Requirements**
Python 3.7 or later
Streamlit
Transformers
Torch
SpeechBrain
Torchaudio
NLTK

### Steps

Clone the repository or download the source code.
Install the required dependencies:

```bash
pip install streamlit transformers torch speechbrain torchaudio nltk
```

Run the Streamlit application:

```bash
streamlit run app.py
```

Open the provided URL in your web browser.

### Usage

- Select the target language (Luganda) from the dropdown menu.
- Upload a text file containing the podcast transcript or manually enter the text in the text area.
- Click the "Translate" button to translate the text.
- Review the translated text in the "Translated Text" section.
- Click the "Synthesize and Play Translated Text" button to generate the speech synthesis.
- Use the audio player to listen to the synthesized speech.

### License

This project is open-source and available under [tbd] License.

### Acknowledgments

- Hugging Face's Sunbird/sunbird-en-mul model for translation
- Sunbird/sunbird-lug-tts for text-to-speech synthesis in Luganda
- SpeechBrain for providing the TTS and Vocoder models
- Streamlit for providing the web application framework

### Contributing

If you have any suggestions or improvements, feel free to submit a pull request or create an issue. Your contributions are more than welcome!
