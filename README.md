1. FunAudioLLM/SenseVoiceSmall
Model Name: SenseVoiceSmall

Hugging Face Link: FunAudioLLM/SenseVoiceSmall

Architecture/Backbone: Non-autoregressive end-to-end transformer model

Task: Multilingual Speech Emotion Recognition, Speech Recognition, Audio Event Detection

Dataset Used for Pretraining: Trained with over 400,000 hours of data supporting more than 50 languages

Input Format: Raw audio waveform

Output Format: Emotion labels (specific labels not detailed)

Languages Supported: Supports over 50 languages including Mandarin, Cantonese, English, Japanese, and Korean

Model Size: Comparable to Whisper-Small; exact parameter count not specified

License: Not specified

Usage Example / Code Snippet: Provided in the GitHub repository

Evaluation Metrics: Benchmarked against Whisper on datasets like AISHELL-1, AISHELL-2, Wenetspeech, LibriSpeech, and Common Voice

Performance: Achieved and surpassed the effectiveness of current best emotion recognition models on test data

Special Notes: Offers low inference latency, processing 10 seconds of audio in 70ms, which is 15 times faster than Whisper-Large
arXiv
+5
Hugging Face
+5
Hugging Face
+5
arXiv
+10
Hugging Face
+10
GitHub
+10
arXiv
+4
GitHub
+4
Hugging Face
+4

2. amiriparian/ExHuBERT
Model Name: ExHuBERT

Hugging Face Link: amiriparian/ExHuBERT

Architecture/Backbone: Enhanced HuBERT model with block extension and fine-tuning

Task: Multilingual Speech Emotion Recognition

Dataset Used for Pretraining: Fine-tuned on EmoSet++, a comprehensive multi-lingual, multi-cultural speech emotion corpus with 37 datasets

Input Format: Raw audio waveform

Output Format: Emotion labels (specific labels not detailed)

Languages Supported: Multiple languages; exact list not specified

Model Size: Not specified

License: Not specified

Usage Example / Code Snippet: Not provided

Evaluation Metrics: Set new benchmarks for various SER tasks on unseen datasets

Performance: Demonstrated efficacy across various languages and domains

Special Notes: Introduces a novel twofold approach by gathering EmoSet++ and enhancing HuBERT through block extension
Hugging Face
+13
arXiv
+13
GitHub
+13
arXiv
+2
arXiv
+2
Hugging Face
+2

3. r-f/wav2vec-english-speech-emotion-recognition
Model Name: wav2vec-english-speech-emotion-recognition

Hugging Face Link: r-f/wav2vec-english-speech-emotion-recognition

Architecture/Backbone: Fine-tuned version of facebook/wav2vec2-large-xlsr-53-english

Task: Speech Emotion Recognition

Dataset Used for Pretraining: SAVEE, RAVDESS, TESS

Input Format: Raw audio waveform

Output Format: Emotion labels: angry, disgust, fear, happy, neutral, sad, surprise

Languages Supported: English

Model Size: Not specified

License: Apache 2.0

Usage Example / Code Snippet: Provided in the model card on Hugging Face

Evaluation Metrics: Not specified

Performance: Not specified

Special Notes: Fine-tuned on multiple English emotion datasets
