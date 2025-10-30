# 🤖 AI Interview Evaluator

An **AI-powered interview evaluation system** that analyzes your spoken answers and provides **feedback on confidence, clarity, tone, and keyword usage**.  
Built using **Whisper** for speech-to-text and **Transformer-based NLP** for intelligent text analysis — all integrated beautifully with an interactive **Gradio dashboard**.

---

## 🎯 Features

✅ Real-time audio transcription using OpenAI Whisper  
✅ NLP analysis of spoken answers (confidence, clarity, keyword strength)  
✅ Tone and energy detection from voice  
✅ Interactive performance dashboard with progress bars and charts  
✅ Personalized improvement tips  
✅ Downloadable PDF report  
✅ Modern and professional Gradio UI with developer footer  

---

## 🧩 Tech Stack

| Component | Technology |
|------------|-------------|
| Speech Recognition | OpenAI Whisper |
| NLP Analysis | Transformers (e.g., BERT) |
| Interface | Gradio |
| Chart | Matplotlib |
| PDF Report | ReportLab |
| Language | Python 3.10+ |

---

## ⚙️ Installation (Google Colab)

Run these commands step-by-step in **Google Colab**:

```bash
!pip install -q openai-whisper==20240930
!pip install -q transformers==4.45.2
!pip install -q torch torchvision torchaudio
!pip install -q gradio matplotlib reportlab librosa soundfile
