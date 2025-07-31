# Whispertranscriptionptoject – Audio Transcription with Multiple Models

This project focuses on audio transcription using OpenAI’s Whisper and other transcription models. It includes silence-based segmentation, noise reduction, and speaker diarization. Transcriptions are compared across models **per speaker** to evaluate performance.

## Project Structure

- **`transcription.ipynb`**: Main Jupyter notebook for preprocessing and transcription.
- **`Audio_segments_with_silence/`**: Folder storing audio segments after silence detection.

## Objectives

- Transcribe a large audio dataset using multiple models (including Whisper)
- Segment audio using silence detection  
- Apply noise reduction and speaker diarization  
- **Compare transcriptions per speaker** across models

## Requirements

- Python 3.8+  
- Libraries: `openai-whisper`, `numpy`, `pandas`, `os`, etc.
