# 📝 Note Summary & AI Quiz Generator

A powerful AI-driven application that transforms images of notes into concise summaries and interactive quizzes. Built with **Streamlit** and powered by **Google Gemini AI**, this tool is designed to help students and professionals quickly digest information and test their knowledge.

## ✨ Features

- **🖼️ Image-to-Summary**: Upload up to 3 images of your notes (handwritten or printed).
- **🇧🇩 Bangla Support**: Generates summaries in Bangla for better accessibility.
- **🎙️ Audio Transcription**: Listen to your summaries with high-quality AI-generated speech.
- **🧠 AI Quiz Generator**: Automatically creates 3 quizzes based on your notes with adjustable difficulty:
  - 🟢 **Easy**
  - 🟡 **Medium**
  - 🔴 **Hard**
- **⚡ Real-time Processing**: Fast response times using the latest Gemini Flash models.

## 🚀 Getting Started

### Prerequisites

- Python 3.10+
- A [Google AI Studio](https://aistudio.google.com/) API Key

### Installation

1. **Clone the Repository** (or download the source):
   ```bash
   git clone <repository-url>
   cd Mod7_project
   ```

2. **Create a Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Environment Configuration**:
   Create a `.env` file in the root directory and add your Gemini API Key:
   ```env
   GEMINI_API_KEY=your_api_key_here
   ```

### Running the Application

Launch the Streamlit app with the following command:
```bash
streamlit run app.py
```

## 🛠️ Tech Stack

- **Framework**: [Streamlit](https://streamlit.io/)
- **AI Model**: Google Gemini (via `google-genai`)
- **Speech**: [gTTS](https://pypi.org/project/gTTS/) (Google Text-to-Speech)
- **Image Processing**: [Pillow](https://python-pillow.org/)
- **Environment**: [python-dotenv](https://pypi.org/project/python-dotenv/)

## 🔍 How it Works

1. **Upload**: Use the sidebar to upload photos of your notes.
2. **Select Difficulty**: Choose the level of challenge for the AI-generated quiz.
3. **Initiate AI**: Click the "Click the button to initiate AI" button.
4. **Learn**: Read the Bangla summary, listen to the audio, and take the quiz to verify your understanding!

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---
*Built with ❤️ for learners everywhere.*
