The project uses the Whisper model for speech recognition.
A Sentence Transformer model is loaded for document retrieval.
Various translation models are used for different language pairs.
The Whisper model transcribes audio input into text.
It also detects the language of the spoken audio.
The project includes a function to detect the language of the audio input.
It maps detected language codes to readable names for user-friendly output.
The system can translate between multiple language pairs.
It uses pre-trained MarianMT models from Hugging Face for translation tasks.
If the detected language isn't English, the transcription is first translated to English.
A simple RAG (Retrieval-Augmented Generation) system is implemented.
It uses a Sentence Transformer to encode documents and queries.
Cosine similarity is used to find the most relevant document for a given query.
Audio is transcribed.
The spoken language is detected.
A relevant document is retrieved based on the transcription.
A Gradio interface is created for user interaction.
Users can upload audio files and select a target language.
The system supports multiple languages including English, Hindi, Spanish, Japanese, German, Russian, Arabic, French, and Italian.
