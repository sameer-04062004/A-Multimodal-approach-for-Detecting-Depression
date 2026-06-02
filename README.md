# A-Multimodal-approach-for-Detecting-Depression

This project is an AI-based multimodal depression detection system that analyzes multiple human behavior signals including text, audio, and video features. The system is based on the DAIC-WOZ dataset and uses machine learning/deep learning models to predict whether a person shows signs of depression.

The project extends an audio-only depression tendency detection approach into a multimodal framework by combining linguistic features from interview transcripts, acoustic features from speech, and visual/facial features from video recordings. Different models such as SVM, Random Forest, CNN, and LSTM with gating are used for individual modality analysis and final multimodal fusion.

## Main Features

- Text-based depression detection using interview transcripts
- Audio-based depression detection using speech/acoustic features
- Video-based depression detection using facial and behavioral features
- Multimodal fusion using LSTM with gating mechanism
- Binary classification: Depressed / Non-Depressed
- Based on the DAIC-WOZ depression interview dataset

## Modalities Used

1. Text Modality  
   Uses transcript data to analyze language patterns related to depression.

2. Audio Modality  
   Uses acoustic speech features to detect vocal patterns linked with emotional and mental state.

3. Video Modality  
   Uses facial expression, gaze, head pose, and facial action unit features.

4. Multimodal Fusion  
   Combines text, audio, and video features for final depression prediction.

## Dataset

This project uses the DAIC-WOZ dataset. The dataset is not included in this repository because access requires official approval from USC/ICT.

Users must apply for dataset access from the official DAIC-WOZ website and place the dataset in the required folder structure before running the notebooks.

## Technologies Used

- Python
- NumPy
- Pandas
- scikit-learn
- TensorFlow / Keras
- NLTK
- Gensim
- Matplotlib
- Google Colab

## Project Purpose

This project is developed as a Final Year Project for research and educational purposes. It is not intended to replace clinical diagnosis. The system only provides depression-related prediction support based on behavioral and physiological data.

## Disclaimer

This system is a research prototype and should not be used as a medical diagnostic tool. Depression diagnosis must always be performed by qualified mental health professionals.
