
# ADAM - Voice Assistant

**ADAM** is a Python-based voice assistant that can help you perform a variety of tasks through voice commands, such as checking the time and date, opening websites, searching Wikipedia, playing music, sending emails, and launching system tools.

## 🧠 Features

- Voice command recognition using `speech_recognition`
- Text-to-speech responses with `pyttsx3`
- Get the current **time** and **date**
- Search summaries on **Wikipedia**
- Open websites like **Google** and **YouTube**
- Play music from a local directory
- Send emails via Gmail SMTP
- Launch system applications like Notepad and Calculator

## 🚀 Getting Started

### Prerequisites

Install the required Python libraries:

```bash
pip install SpeechRecognition pyttsx3 wikipedia
```


If you encounter issues with `pyaudio`, use:

```bash
pip install pipwin
pipwin install pyaudio
```

### Configuration

1. **Email Sending**

   - Replace placeholder credentials in the `send_email()` function:

     ```python
     your_email = "youremail@gmail.com"
     your_password = "yourapppassword"
     ```

   - For security, consider using environment variables instead of hardcoding.

2. **Music Directory**

   - Set the correct path to your music folder in the `play_music()` function:

     ```python
     music_folder = "C:\\Users\\YourUsername\\Music"
     ```

## 🛠 How to Use

1. Run the script:

   ```bash
   python main.py
   ```

2. Speak into the microphone when prompted.

3. Example commands:

   - "What is the time?"
   - "Search Python on Wikipedia"
   - "Open YouTube"
   - "Play music"
   - "Send email"

## 📁 Project Structure

```
.
├── main.py         # Main voice assistant script
├── README.md       # Project documentation
```



## 👤 Author

Developed by **Arya Kumar Dubey**
Feel free to fork and customize as needed!

```



