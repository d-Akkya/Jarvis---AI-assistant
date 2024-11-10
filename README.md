# Jarvis - AI Assistant 🤖

Jarvis is an AI-powered voice assistant designed to perform various tasks like browsing the internet, playing music, reading the latest news and interacting with OpenAI GPT models. This project offers users a smart, conversational assistant to streamline daily activities and provide a personalized interaction experience.

## 🚀 Features
- **Voice Activation**: Activate using "Hey Jarvis" and perform various tasks through voice commands.
- **Web Browsing**: Open popular websites like Google, YouTube, Facebook, and LinkedIn using voice commands.
- **Music Playback**: Play your favorite tracks directly from YouTube.
- **News Headlines**: Fetch and read out the latest news updates using the News API.
- **OpenAI GPT Integration**: Provides AI-generated responses for complex queries using OpenAI's GPT models.
- **Conversational AI**: Offers a friendly interaction with personalized responses and context retention.

## 🛠️ Technologies Used
- **Python**: Core language for development.
- **SpeechRecognition**: For converting speech to text.
- **Google Text-to-Speech (gTTS)**: For generating voice responses.
- **Pygame**: For playing audio files.
- **OpenAI API**: To generate responses using GPT models.
- **Web Browser**: For handling URL redirections.
- **News API**: For fetching the latest news updates.

## 📂 Project Structure
```plaintext
jarvis-ai-assistant/
├── src/
│   ├── main.py                  # Main script to run the assistant
│   ├── musicLibrary.py          # Stores links to music tracks
│   ├── newsapi.py               # Contains the News API key
│   ├── client.py                # Contains the OpenAI API key
├── requirements.txt             # Dependencies for the project
└── README.md                    # Project documentation
```

## 🗝️ Configuration
Before running the project, make sure to set up the API keys:

1. newsapi.py:
   ```python
   newsapi = "YOUR_NEWS_API_KEY"
   ```
2. client.py:
   ```python
   import openai
   client = openai
   client.api_key = "YOUR_OPENAI_API_KEY"
   ```

## ⚙️ Installation
1. Clone the Repository
   ```bash
   git clone https://github.com/d-Akkya/Jarvis.ai_assistant.git
   cd Jarvis.ai_assistant
   ```
2. Create and Activate Virtual Environment
   ```bash
   virtualenv .venv
   ./.venv/Scripts/activate.ps1
   ```
4. Install Dependencies
   ```bash
   pip install -r requirements.txt
   ```

## 🧩 Usage
1. Run Jarvis
   ```bash
   python main.py
   ```
2. Example Commands:
   - **"Hey Jarvis, open Google"**: Opens Google in the web browser.
   - **"Play stealth"**: Plays the specified song from YouTube.
   - **"Get news"**: Reads the latest news headlines.
   - **"Who is Akkya"**: Provides information about the creator.
   - **"Appreciate that"**: Acknowledges with a response.

## 📌 Dependencies
Ensure you have the following Python packages installed:
```plaintext
SpeechRecognition
webbrowser
pyttsx3
gtts
pygame
requests
openai
```
Install them using:
```bash
pip install SpeechRecognition webbrowser pyttsx3 gtts pygame requests openai
```

## 📂 File Explanations
- main.py : The core file to run the voice assistant. It handles listening for the wake word, processing commands, and generating responses.
- musicLibrary.py : A dictionary of songs mapped to YouTube links for playback.
- newsapi.py : Contains the News API key for fetching top news headlines.
- client.py : Manages the OpenAI API key for generating AI responses.
- requirements.txt : List of dependencies required for the project.

## 🛠️ Known Issues
- The OpenAI GPT integration may require additional setup to function properly.
- The **gTTS** & **Pygame** audio playback might have compatibility issues on some operating systems.
- Ensure your microphone is properly configured to avoid recognition errors.

## 🤝 Contributing
Contributions are welcome! If you'd like to contribute, follow these steps:
1. Fork the project.
2. Create your feature branch:
   ```bash
   git switch -c feature-branch
   ```
3. Commit you changes:
   ```bash
   git commit -m 'Add new feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature-branch
   ```
5. Open a pull request.

## 📞 Contact
For any inquiries, feel free to reach out :

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:akhileshbamane26@gmail.com)
   [![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/d-akkya/)
         [![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white)](https://www.instagram.com/d_akkya_007/)
