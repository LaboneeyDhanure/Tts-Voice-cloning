# 🎤 Voice Cloning with Tortoise TTS

This project demonstrates voice cloning using the Tortoise TTS model. Given short voice samples from a user, the system synthesizes new speech in the same voice for any input text.

## 🔧 Features
- Clone any speaker's voice using 2–5 short `.wav` samples
- High-quality audio synthesis using Tortoise TTS
- Easy-to-run Jupyter Notebook (Colab-friendly)
- Input/output `.wav` files managed in dedicated folders

## 📁 Project Structure
voice-cloning-project/
├── voice_cloning_tortoise_bark.ipynb # Main notebook
├── requirements.txt # Python dependencies
├── sample_input/ # User voice samples (.wav)
├── generated_output/ # Cloned output audio
└── README.md # Project guide

markdown
Copy
Edit

## 🚀 How to Run
1. Upload 2–5 `.wav` files to `sample_input/` (6–10 seconds each).
2. Open the notebook in Google Colab or locally.
3. Set your custom text.
4. Run all cells — output saved in `generated_output/cloned_voice.wav`.

## 📦 Requirements
Install via:
```bash
pip install -r requirements.txt
🧠 Models Used
Tortoise TTS for voice cloning

Optional: Bark for emotional/prosodic enhancement

📌 Notes
Ideal for poadcast, voice artist, or personal AI voice applications.

Works best with clear, high-quality audio samples.

Author: Laboneey Dhanure
Repo: github.com/LaboneeyDhanure/Tts-Voice-cloning 

