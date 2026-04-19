# -Multilingual-Expressive-Text-to-Speech-TTS-System


This project is a multilingual Text-to-Speech (TTS) system that generates natural, human-like speech with expressive tones across multiple Indian languages. It uses an open-source model and provides an interactive web UI.

---

## 🚀 Features

* 🌍 Multilingual support:

  * English
  * Hindi
  * Kannada
  * Telugu
  * Marathi
  * Gujarati
* 🎤 Male and Female voice generation
* 🎧 Audio playback in browser
* ⬇️ Download generated speech as `.wav`
* 💻 Simple and clean web UI using Gradio
* 🔓 Fully open-source (no paid APIs)

---

## 🧠 Model Used

This project uses the Indic Parler-TTS model from Hugging Face, which supports expressive and multilingual speech generation.

---

## ⚙️ Environment Setup

```bash
# Create virtual environment (recommended)
python -m venv tts_env
source tts_env/bin/activate   # Windows: tts_env\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

---

## 📦 Install Additional Dependencies

```bash
pip install git+https://github.com/huggingface/parler-tts.git
pip install transformers torch torchaudio gradio soundfile
```

---

## 🔐 Hugging Face Login (Required)

```bash
hf auth login
```

Paste your Hugging Face token when prompted.

---

## ▶️ Running the Application

### If using Notebook:

```bash
jupyter notebook app.ipynb
```

Run all cells step-by-step.

---

## 🌐 UI Usage

1. Enter or paste text
2. Select language
3. Choose voice (male/female)
4. Click **Generate Speech**
5. Listen or download the audio

---

## 📴 Offline Capability

After the first run, all model weights are cached locally. The application can then run fully offline without requiring an internet connection.

---

## ⚠️ Notes

* GPU (CUDA) is recommended for faster generation
* CPU mode works but may be slower
* If the notebook does not render on GitHub, please download and run locally

---

## 📊 Supported Languages

* English
* Hindi
* Kannada
* Telugu
* Marathi
* Gujarati

---

## 📁 Project Structure

```
project/
│
├── app.ipynb
├── requirements.txt
├── README.md
```

---

## 🧾 Conclusion

This project demonstrates a multilingual expressive TTS system with a user-friendly interface. It successfully generates natural-sounding speech across multiple Indian languages using open-source tools.

---

## 📌 Future Improvements

* Emotion control (happy, sad, etc.)
* Speed and pitch adjustment
* Voice cloning feature
