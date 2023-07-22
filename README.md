# Demo
Experience my Speech Emotion Recognition (SER) System in action! 🎙️🎭 [Unmute 🔊 the video to hear the recorded voice].

https://github.com/Marwan951/Speech-Emotion-Recognition/assets/95751506/af1563fb-fe9f-4bff-9928-b0650d47a1eb

# Speech-Emotion-Recognition
In this repository, I present my graduation project, aiming to build an efficient real-time system that accurately identifies emotions from speech signals for enhancing human-computer interaction, it offers diverse datasets, multiple DL models, and comprehensive documentation for easy understanding of the system.

# SER General Architecture
The research's primary objective is to create a real-time SER system that can precisely categorize emotions based on audio input. The system employs various methods such as preprocessing, feature extraction, model classification, and emotion detection visualization to analyze and classify the input signals. It operates continuously until the user decides to stop recording, enabling users to capture and review their emotional expressions. Please refer to the above Figure for an illustration of the system's components.

![Block drawio](https://github.com/Marwan951/Speech-Emotion-Recognition/assets/95751506/7b07b6bf-714a-4513-8db6-5d005f432da7)
# Flow Diagram
Flow chart diagram for a SER system provides a visual representation of the sequential steps involved in the system's operation. It illustrates the flow of data and processes from input to output. The diagram typically includes various components, such as speech signal acquisition, preprocessing, silence removal, feature extraction, emotion classification, and the final result.

![photo_5809847672444664384_x](https://github.com/Marwan951/Speech-Emotion-Recognition/assets/95751506/e819a0df-a9ef-493b-b577-70314a266ccc)
# DL Model - CUDA_DNN_LSTM 
The SER system utilizes a CUDA-enabled Deep Neural Network with Long Short-Term Memory (LSTM) architecture, ensuring efficient emotion recognition.

![CuDnnLstm](https://github.com/Marwan951/Speech-Emotion-Recognition/assets/95751506/9d5775e8-8732-4114-97d3-87d304df91c0)
# Dataset - Rvdess, TESS
The system is trained on the RAVDESS and TESS datasets, providing a diverse range of emotions for robust emotion recognition.

# Preprocessing - Silence removal, Normalization, Encoding & Data Balancing
Prior to training, speech signals undergo preprocessing steps like silence removal, normalization, and encoding, with data balancing to enhance model performance.

# Feature Extraction
Acoustic feature extraction plays a crucial role in SER by capturing the acoustic characteristics and patterns indicative of different emotional states. The process uses LLDs and HLDs for feature extraction, capturing acoustic details and temporal variations in speech signals. LLDs use features like  RMSE, chroma-STFT ,ZCR, MFCC, and Mel-Spectrogram, while HLDs summarize acoustic features' statistical properties and emotional characteristics. SER systems use LLDs and HLDs to classify and recognize different emotional states in speech.

# Displaying the Emotions
The real-time SER system instantly presents the recognized emotion, allowing users to promptly interpret the emotional content conveyed in the input speech.
