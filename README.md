
# Multi Model Sentiment Analysis

### 🎯 Project Overview

The Multimodal Sentiment Analysis System is an advanced AI-powered solution that analyzes human emotions and sentiments across multiple data modalities simultaneously. Unlike traditional sentiment analysis tools that rely on a single input type, this system integrates text processing, facial expression recognition, and speech analysis to provide a comprehensive and accurate understanding of human emotional states.

#### 🚀 Key Innovation
This project addresses the limitation of unimodal sentiment analysis systems by combining three distinct AI technologies:

- 🎭 Facial Expression Recognition (FER) - Analyzes facial micro-expressions and emotional cues using computer vision.

- 🎤 Speech Emotion Recognition - Processes audio input to detect emotional tone, pitch variations, and speech patterns.

- 📝 Natural Language Processing - Understands textual content, context, and linguistic sentiment indicators.

By fusing these modalities, the system achieves higher accuracy and robustness compared to single-modal approaches, making it particularly effective in real-world scenarios where human emotions are expressed through multiple channels simultaneously.

### Problem Statement
Traditional sentiment analysis systems often fail to capture the full spectrum of human emotional expression because they:

Rely on single data sources (text-only or audio-only)
Miss contextual emotional cues present in facial expressions
Cannot detect contradictions between verbal and non-verbal communication
Lack real-time processing capabilities for dynamic interactions
# Features

### Core Capabilities

- Multi-Modal Input Processing: Simultaneous analysis of text, audio, and video streams.
- Real-Time Emotion Detection: Live facial expression recognition and speech emotion analysis.
- Advanced NLP Processing: Context-aware text sentiment analysis with linguistic pattern recognition.
- Speech-to-Text Integration: Automatic transcription using OpenAI Whisper for audio sentiment analysis.
- Facial Expression Recognition: Real-time detection of 7 basic emotions (happy, sad, angry, fear, surprise, disgust, neutral)
- Sentiment Fusion Engine: Intelligent combination of multi-modal predictions for enhanced accuracy.
- Confidence Scoring: Reliability metrics for each prediction to ensure trust in results.
- Cross-Modal Validation: Detection of emotional contradictions between verbal and non-verbal cues.

### Technical Features

- Scalable Architecture: Modular design supporting easy addition of new modalities.
- Performance Optimization: Efficient processing pipeline for real-time applications.
- Flexible Input Formats: Support for various file types (MP4, WAV, MP3, TXT, live camera/microphone).
- Customizable Thresholds: Adjustable sensitivity levels for different use cases.
- Comprehensive Logging: Detailed analysis reports and prediction histories.
- API Integration: RESTful endpoints for seamless integration with existing systems.

# Tech Stack
### Machine Learning & AI

- OpenCV - Computer vision library for image and video processing
- FER - Facial Expression Recognition library
- NLTK - Natural Language Toolkit for text processing
- TextBlob - Simple API for NLP tasks

### Speech & Audio Processing

- OpenAI Whisper - Automatic speech recognition system
- SpeechRecognition - Speech-to-text conversion
- PyAudio - Audio I/O library for real-time processing

### Data Processing & Analysis

- NumPy - Numerical computing library
- Pandas - Data manipulation and analysis
- Matplotlib - Data visualization and plotting
- Seaborn - Statistical data visualization

### APIs & Integration

- OpenAI API - Advanced language model integration
- JSON - Data interchange format
- Pickle - Python object serialization

## Dataset Link
https://zenodo.org/records/1188976
### Installation
### Prerequisites

Python 3.8 or higher

pip package manager

Git

Webcam and microphone (for real-time processing)

Intsall the Dataset

Quick Start

Clone the repository:

```bash

git clone https://github.com/yourusername/multimodal-sentiment-analysis.git

```

Navigate into the project folder:

```bash
bashcd multimodal-sentiment-analysis
```
Create a virtual environment:

```bash
bashpython -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```
Install the necessary dependencies:
```bash
bashpip install -r requirements.txt
```
Download required model weights:
```bash
bashpython download_models.py
```
Run the multimodal sentiment analyzer:
```bash
bashpython main.py
```

Clone the repository:
```bash
bashgit clone https://github.com/yourusername/multimodal-sentiment-analysis.git
```



# How It Works
### system Architecture
[Input Sources] → [Processing Pipeline] → [Fusion Engine] → [Output Analysis]
Step-by-Step Process
1. Input Acquisition

Video Stream: Captures facial expressions using OpenCV
Audio Stream: Records speech using microphone or audio files
Text Input: Processes written text or transcribed speech.

2. Feature Extraction

Facial Analysis: FER library detects facial landmarks and classifies emotions.
Speech Processing: Whisper converts audio to text, analyzes tone and pitch.
Text Analysis: NLTK and TextBlob process linguistic patterns and sentiment.

3. Individual Modal Analysis

Computer Vision: CNN models analyze facial micro-expressions
Speech Recognition: Audio features processed for emotional tone detection.
NLP Processing: Transformer models analyze text sentiment and context.

4. Multi-Modal Fusion

Feature Alignment: Synchronizes temporal features across modalities
Confidence Weighting: Assigns reliability scores to each modal prediction.
Ensemble Learning: Combines predictions using weighted voting or neural fusion.

5. Final Prediction

Sentiment Classification: Outputs primary emotion (positive/negative/neutral).
Emotion Detection: Identifies specific emotions (joy, sadness, anger, etc.).
Confidence Scoring: Provides reliability metrics for each prediction.
Contradiction Detection: Flags mismatches between verbal and non-verbal cues.

### Processing Pipeline

- Data Preprocessing: Noise reduction, normalization, and format standardization.
- Feature Engineering: Extraction of relevant features from each modality.
- Model Inference: Individual predictions from specialized models
- Temporal Alignment: Synchronization of time-series data across modalities.
- Fusion Algorithm: Intelligent combination of multi-modal features.
- Post-Processing: Confidence calculation and result formatting.
- Output Generation: Structured results with visualizations and metrics.

### Real-Time Processing

- Streaming Analysis: Continuous processing of live audio/video feeds.
- Buffered Processing: Efficient handling of data chunks for real-time performance.
- Asynchronous Operations: Non-blocking processing for responsive user experience.
- Memory Management: Optimized resource usage for sustained operation.
## Contributing

Contributions are always welcome!

If you'd like to contribute to this project, feel free to open an issue or submit a pull request. Contributions are welcome!

