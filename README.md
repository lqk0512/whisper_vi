# Vietnamese Speech Recognition using Fine-tuned Whisper

## 📌 Overview

This project focuses on improving Vietnamese Automatic Speech Recognition (ASR) by fine-tuning a Whisper-based model on a dedicated Vietnamese speech dataset. The goal is to enhance transcription accuracy, especially for real-world audio conditions.

A complete speech-to-text pipeline was developed, covering data preprocessing, model training, and inference.

---

## 🚀 Key Features

* Fine-tuned a Whisper-based ASR model for Vietnamese speech recognition
* Improved transcription performance on Vietnamese audio data
* Built an end-to-end speech-to-text pipeline
* Integrated audio preprocessing for better robustness in noisy environments

---

## 🧠 Model

* Base model: Whisper (pretrained)
* Fine-tuning on Vietnamese dataset
* Optimized for:

  * Vietnamese pronunciation nuances
  * Noisy and real-world audio inputs

---

## ⚙️ Pipeline Architecture

### 1. Preprocessing

* Audio resampling (standardized sample rate)
* Noise filtering and cleaning
* Feature extraction using Librosa

### 2. Model Inference

* Input audio → processed waveform
* Tokenization and feature encoding
* Speech-to-text inference using fine-tuned model

### 3. Output

* Generated Vietnamese text transcription

---

## 🛠️ Technologies Used

* **PyTorch** – model training and inference
* **HuggingFace Transformers** – Whisper integration and fine-tuning
* **Whisper** – base ASR model
* **Librosa** – audio preprocessing and feature extraction

---

## 📊 Results

* Improved word error rate (WER) compared to baseline Whisper model
* Better handling of:

  * Accents and dialects
  * Background noise
  * Conversational speech


