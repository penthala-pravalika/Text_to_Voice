# 🔊 Text to Voice – Text-to-Speech App

## 📌 Project Overview

Text to Voice is a Python-based web application built using **Streamlit** and **Google Text-to-Speech (gTTS)**. It converts written text into speech in multiple languages, including Indian languages such as Telugu, Hindi, Tamil, Kannada, and Malayalam.

Users can type text or upload a `.txt` file, select a language and speech settings, listen to the generated audio, and download it as an MP3 file.

This project provides a simple and user-friendly way to convert written content into spoken audio without requiring an API key.

## ✨ Features

* 🔊 Converts text into speech.
* 🌐 Supports multiple languages.
* 🇮🇳 Includes Indian languages such as Telugu, Hindi, Tamil, Bengali, Marathi, Kannada, Malayalam, Gujarati, and Urdu.
* 🗣️ Supports Indian, American, British, and Australian English accents.
* 🐢 Slow speech option for easier listening.
* 📝 Accepts manually typed text.
* 📂 Supports uploading `.txt` files.
* ▶️ Plays generated audio directly in the application.
* ⬇️ Downloads speech as an MP3 file.
* 🔑 No API key required.
* 💻 Simple and interactive Streamlit interface.

## 🛠️ Technologies Used

* **Python** – Application logic
* **Streamlit** – Web application interface
* **gTTS (Google Text-to-Speech)** – Text-to-speech conversion
* **BytesIO** – In-memory audio processing

## 🌍 Supported Languages

| Language  | Code |
| --------- | ---- |
| English   | `en` |
| Hindi     | `hi` |
| Telugu    | `te` |
| Tamil     | `ta` |
| Bengali   | `bn` |
| Marathi   | `mr` |
| Kannada   | `kn` |
| Malayalam | `ml` |
| Gujarati  | `gu` |
| Urdu      | `ur` |
| French    | `fr` |
| Spanish   | `es` |
| German    | `de` |
| Japanese  | `ja` |

## 📁 Project Structure

```text
Text_to_Voice/
│
├── app.py
├── requirements.txt
├── README.md
└── .gitignore
```

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with your GitHub repository URL.

### 2. Navigate to the project folder

```bash
cd Text_to_Voice
```

### 3. Create a virtual environment (recommended)

```bash
python -m venv venv
```

### 4. Activate the virtual environment

**Windows PowerShell:**

```powershell
.\venv\Scripts\Activate.ps1
```

### 5. Install dependencies

Create a `requirements.txt` file containing:

```text
streamlit
gTTS
```

Install the packages:

```bash
pip install -r requirements.txt
```

### 6. Run the application

```bash
streamlit run app.py
```

The application will open in your browser, usually at:

```text
http://localhost:8501
```

## 🚀 How to Use

1. Launch the application.
2. Select your preferred language from the sidebar.
3. If you select English, choose an accent.
4. Enable slow speech if needed.
5. Select **Type text** or **Upload .txt**.
6. Enter your text or upload a text file.
7. Click **Convert to speech**.
8. Listen to the generated audio in the application.
9. Click **Download MP3** to save the audio.

## 💡 Example

**Input text:**

```text
Hello! Welcome to my text to speech project. Have a great day.
```

**Selected settings:**

* Language: English
* Accent: Indian
* Speech speed: Normal

**Expected output:**

The application generates an MP3 audio file containing the spoken version of the input text. You can listen to it directly or download it.

You can also enter Telugu text and select Telugu as the language to generate Telugu speech.

## 📦 Requirements

* Python 3.9 or later
* Internet connection
* Required Python packages: `streamlit` and `gTTS`
* A modern web browser

## ⚠️ Limitations

* An active internet connection is required for speech generation.
* The application supports a maximum of 5,000 characters in the text input box.
* Speech quality and pronunciation depend on the selected language and the gTTS service.
* Accent selection applies only to English in this application.
* The app may fail if the speech service is unavailable or the network connection is interrupted.

## 🔮 Future Improvements

* Add more supported languages.
* Add voice and speech-speed controls.
* Support PDF and Word document uploads.
* Add audio playback controls.
* Allow users to choose custom output filenames.
* Improve error handling and input validation.

## 🎯 Learning Outcomes

Through this project, I learned how to:

* Build interactive applications using Streamlit.
* Integrate a text-to-speech library into Python.
* Handle text input and file uploads.
* Process audio data in memory using `BytesIO`.
* Generate and download MP3 audio files.
* Manage Python dependencies and organize a GitHub project.

## 👩‍💻 Author

**Pravalika Penthala**

B.Tech CSE Student | Python | AI & Machine Learning | Streamlit

## 📄 License

This project is available for educational and learning purposes. You may add an open-source license, such as the MIT License, if you want others to reuse and modify the project.
