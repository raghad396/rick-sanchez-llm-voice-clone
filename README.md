# Rick Sanchez AI Chatbot: Language Model Fine-Tuning & Voice Cloning

This project fine-tunes TinyLLaMA-1.1B-Chat on Rick Sanchez dialogues (Rick and Morty, seasons 1–8) using LoRA and 4-bit quantization for efficient adaptation. It also clones Rick’s voice using Tortoise TTS trained on emotion-rich audio clips. The result is an interactive AI chatbot that writes and speaks like Rick — sarcastic, scientific, and philosophically intense.

## Features

- Fine-tuned causal LLM with instruction-following dialogue data  
- Efficient adaptation with PEFT (LoRA) and quantization  
- Realistic voice cloning using Tortoise TTS  
- Integrated text generation and speech synthesis  
- Interactive chatbot emulating Rick Sanchez’s personality  

## Usage

1. Open the `rick_sanchez_chatbot.ipynb` notebook in Google Colab or Jupyter.  
2. Follow the cells to load data, fine-tune the model, train TTS, and run the chatbot.  
3. Requires Python 3.8+, PyTorch, Transformers, Tortoise TTS, and related dependencies.

## Requirements

- Python 3.8+  
- PyTorch  
- Transformers  
- PEFT (for LoRA)  
- Tortoise TTS  
- Jupyter or Google Colab  

## Dataset

The dialogue dataset was curated from Rick and Morty episodes (seasons 1–8) and formatted for instruction-following fine-tuning.
