# Tafseel: Real-Time Arabic Speech-to-Text

🎙️ **Tafseel** (تفصيل) brings Arabic speech to life as text in real-time! This sleek, web-based app, powered by Streamlit and the faster-whisper model, transcribes spoken Arabic instantly using your browser’s microphone. No installation needed—just open, speak, and download your transcription as a .txt file. Upload audio files for quick conversion, too!

[![Demo](https://img.shields.io/badge/Demo-Live-green)](https://hussiensehs-tafseel.streamlit.app)
[![License](https://img.shields.io/badge/License-MIT-blue)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.8%2B-yellow)](https://www.python.org)

## 🌟 Why Tafseel?

- **🎤 Instant Transcription**: Convert Arabic speech to text in real-time with precision.  
- **⬇️ Download with Ease**: Save your transcriptions as .txt files in one click.  
- **🎵 Audio File Support**: Upload .wav, .mp3, or .m4a files for seamless transcription.  
- **☁️ Fully Online**: Hosted on Streamlit Cloud for instant access anywhere.  
- **⚡ Fast & Lightweight**: Optimized for speed using the faster-whisper base model.  

## 🚀 Get Started

1. Visit [Tafseel on Streamlit Cloud](https://hussiensehs-tafseel.streamlit.app).  
2. Grant microphone access and click **🎤 ابدأ التسجيل** to capture your speech.  
3. Hit **🛑 إيقاف التسجيل** to view your text, then **⬇️ تحميل النص كملف** to download.  
4. Or, upload an audio file (.wav, .mp3, .m4a) for instant transcription!

## 🛠 Setup for Developers

### 📥 Clone the Repository
```bash
git clone https://github.com/hussiensehs/Tafseel.git
cd Tafseel
```

### 📦 Install Dependencies (Optional, for Local Testing)
```bash
pip install -r requirements.txt
```
> **Note**: Ensure `ffmpeg` is installed for audio processing ([Install Guide](https://ffmpeg.org/download.html)).

### 🚀 Run Locally
```bash
streamlit run app.py
```

### ☁️ Deploy to Streamlit Cloud
1. Log into [Streamlit Cloud](https://streamlit.io/cloud).  
2. Connect your GitHub account and select `hussiensehs/Tafseel`.  
3. Set `app.py` as the main file and click **Deploy**.  
4. Access your app at the provided URL (e.g., `https://hussiensehs-tafseel.streamlit.app`).

## 📂 Project Structure
```
Tafseel/
├── app.py                # Main Streamlit application
├── requirements.txt      # Python dependencies
├── LICENSE               # MIT License
├── README.md             # This file
```

## 📦 Dependencies
- `streamlit`  
- `faster-whisper`  
- `pydub`  
- `ffmpeg-python`  
- `soundfile`  
- `numpy`  
- `torch`  
> Full list in `requirements.txt`.

## ⚠️ Notes
- Uses the faster-whisper base model for efficient Arabic transcription.  
- Requires a browser with MediaRecorder API support (Chrome, Firefox, Edge).  
- For enhanced accuracy, a medium model upgrade is planned.

## 🔮 Future Enhancements
- 🌍 Automatic language detection.  
- 📈 Support for multiple faster-whisper models (tiny, medium).  
- 🌐 Translation of transcribed text.  
- ⏲️ Recording timer display.  
- 📧 Email export for transcriptions.

## 📜 License
MIT © hussien elgamal

## 🎯 Contribute
Love Tafseel? Help make it better!  
- 🐛 Found a bug? Open an [Issue](https://github.com/hussiensehs/Tafseel/issues).  
- 💡 Got an idea? Submit a [Pull Request](https://github.com/hussiensehs/Tafseel/pulls).
