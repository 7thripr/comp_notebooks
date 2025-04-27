# Multi-Lingual Sentiment Analysis Competition

## Results
- **F1 Score:** 0.96551  
- **Leaderboard Position:** 5 (at the time of submission)

## Competition Overview
The goal of this competition was to explore fine-tuning as an art, specifically understanding how **LoRA-based parameter-efficient fine-tuning** can enhance the multilingual capabilities of a large-scale model like **LLaMA 3.1-8B**.  

Participants needed to balance:
- **Data efficiency**
- **Compute limitations** (Kaggle Notebooks only)
- **Model adaptation techniques**

The objective was to achieve **high sentiment classification accuracy** across **13 supported languages**, each represented in its **native script**.

---

# IndicTTS Deepfake Challenge

## Results
- **ROC-AUC Score:** 1.0  
- **Leaderboard Position:** 1 (based on private leaderboard after competition close)

## Competition Overview
The **IndicTTS Deepfake Challenge** focused on detecting AI-generated speech across **16 Indian languages**, including Assamese, Bengali, Bodo, Dogri, Kannada, Malayalam, Marathi, Sanskrit, Nepali, English, Telugu, Hindi, Odia, Manipuri, Gujarati, and Tamil.  

Participants were tasked with developing models that predict the probability of an audio sample being AI-generated, evaluated based on the **ROC-AUC score**. Final rankings were determined by performance on a **private leaderboard**.

The competition dataset included over **63 hours** of audio and **33,737 samples**, offering a unique opportunity to work on **real-world TTS deepfake detection**—a critical area for AI security and speech verification research.

## My Approach
- **First Model:** Used **ResNet architecture** combined with **spectrogram representations** of audio.
- **Second Model:** Developed a **custom CNN** with **channel attention mechanisms**, again leveraging **spectrogram features**.

Both models were carefully validated to ensure stability and generalization, leading to a **perfect ROC-AUC score of 1.0** on the private leaderboard.

## Key Learnings
- Efficient GPU usage and strategic data handling to manage large datasets.
- Importance of cross-validation to avoid overfitting on public leaderboards.
- Robust feature extraction techniques for audio-based classification tasks.

---
