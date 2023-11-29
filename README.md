# Demo 
🎥 Watch the showcasing SER System in action 🎙️🎭. Remember to unmute 🔊 the video to hear the voice.

https://github.com/Marwan951/Speech-Emotion-Recognition/assets/95751506/af1563fb-fe9f-4bff-9928-b0650d47a1eb
# Speech Emotion Recognition
In this repository, I present my graduation project, aiming to build an efficient real-time system that accurately identifies emotions from speech signals for enhancing human-computer interaction, it offers diverse datasets, multiple DL models, and comprehensive documentation for easy understanding of the system.

# SER Flowchart 
The research's primary objective is to create a real-time SER system that can precisely categorize emotions based on audio input. The system employs various methods such as preprocessing, feature extraction, model classification, and emotion detection visualization to analyze and classify the input signals. It operates continuously until the user decides to stop recording, enabling users to capture and review their emotional expressions. Please refer to the above Figure for an illustration of the system's components.

![Block drawio](https://github.com/Marwan951/Speech-Emotion-Recognition/assets/95751506/7b07b6bf-714a-4513-8db6-5d005f432da7)
## Features

- **Real-Time Emotion Recognition:** My system efficiently processes speech signals in real-time, enabling instant emotion identification.

- **Web-Based Interface:** The web-based interface offers a user-friendly experience, allowing users to interact with the system through their browsers.

- **Mobile Application:** For on-the-go access,  mobile application extends the emotion recognition capabilities to smartphones.

- **Diverse Emotion Dataset:** The system is trained on a diverse and well-annotated emotion dataset to ensure accurate recognition across different emotions, sourced from the Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS) and Toronto Emotional Speech Set (TESS).

- **Preprocessing:** Before training, speech signals undergo preprocessing steps including silence removal, normalization, encoding, and data balancing to enhance model performance.

- **Feature Extraction:** Low-level descriptors such as Mel-Frequency Cepstral Coefficients (MFCC), Mel Spectrogram, and Zero-Crossing Rate (ZCR), combined with high-level descriptors like Mean and Standard Deviation, form the feature set for emotion classification.

- **DL Model (CUDA_DNN_LSTM):** The SER system utilizes a CUDA-enabled Deep Neural Network with Long Short-Term Memory (LSTM) architecture, ensuring efficient emotion recognition.

- **Displaying Emotion:** The SER system displays the recognized emotion, enabling users to interpret the emotional content of the input speech.

## Installation

1. Clone this repository to your local machine.
2. Install the required dependencies using [requirements.txt](requirements.txt): 'pip install -r requirements.txt'

## Contributions

@Marwan951
@SER-Team

## Acknowledgments

- Special thanks to Dr. Sally Saad and TA Samar Aly for their invaluable guidance and contributions to the development of this SER System.
