# ContextualAI---A-Personal-Assistant-with-Voice-Recognition-and-Contextual-Understanding

# README: ContextualAI - A Personal Assistant with Voice Recognition and Contextual Understanding

## Project Overview
ContextualAI is a web application designed to facilitate secure and interactive interview simulations. It combines state-of-the-art speech-to-text technologies with advanced language models to enable dynamic transcription and context-aware response generation.

## Key Features
- **Secure User Authentication**: Integration of Streamlit Authenticator provides robust user authentication and a personalized user experience.
- **Real-time Audio Processing**: Utilization of PyAudio for efficient handling of real-time audio streams.
- **Accurate Speech-to-Text Conversion**: Seamless integration with AssemblyAI for high-accuracy speech-to-text conversion.
- **Privacy-preserving Data Handling**: Incorporation of spaCy's Named Entity Recognition to redact sensitive information from conversation text.
- **Advanced Natural Language Understanding**: Integration of OpenAI's GPT for generating context-aware responses.

## Methodology
1. **User Interface**: Streamlit is used as the foundation for the user-friendly web application.
2. **Audio Processing**: PyAudio is employed for real-time audio capture and processing.
3. **Speech-to-Text Conversion**: Websockets are used to establish a reliable communication channel with AssemblyAI for speech-to-text conversion.
4. **Data Privacy**: spaCy's Named Entity Recognition is used to redact sensitive information from conversation text.
5. **Response Generation**: OpenAI's GPT is integrated for advanced natural language processing and context-aware response generation.

## Results
- Secure user authentication and personalized user experience through Streamlit Authenticator.
- Accurate speech-to-text transcription with approximately 92% similarity to the original text.
- Effective data redaction, successfully masking 72.22% of sensitive information.
- Seamless integration of various technologies for a comprehensive interview simulation platform.

## Usage
The ContextualAI application is designed to be user-friendly and easily deployable. It can be accessed through a web interface, providing a seamless experience for conducting interview simulations with real-time transcription and context-aware responses.
