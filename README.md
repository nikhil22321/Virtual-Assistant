# 🗣️ Virtual Assistant

An intelligent and interactive voice-based virtual assistant that greets users, takes voice input, responds to user queries based on a trained model, and executes commands like opening YouTube or other applications. Built using **Python**, it combines machine learning, speech recognition, and natural language processing for a real-time assistant experience.

---

## 🔗 **Live Demo**  

🎤 Currently not hosted online. Clone and run locally using Python (see instructions below).

---

## 🚀 Features

🧠 **Smart Interaction**  
- Greets users with voice on startup.  
- Understands and responds to questions using trained intents (`intents.json`).  
- Can open popular apps (e.g., YouTube, Chrome) with voice commands.

🎙️ **Voice Capabilities**  
- Converts speech to text using `SpeechRecognition`.  
- Responds using `pyttsx3` (text-to-speech).  
- Works offline after initial setup.

🧠 **Machine Learning Model**  
- Trained on custom intents using TensorFlow/Keras.  
- Uses tokenization and label encoding for accurate predictions.  
- Easily extendable to new intents and commands.

---

## 🛠️ Tech Stack

- **Python 3.8+**  
- **TensorFlow / Keras** – for neural network training  
- **NLTK** – for NLP preprocessing  
- **SpeechRecognition** – for capturing user voice  
- **pyttsx3** – for voice output  
- **pickle / JSON** – for storing and loading encoders and models

---

## 📂 Project Structure

```bash
voice-assistant/
├── chat_model.h5           # Trained neural network model
├── intents.json            # User intents and patterns
├── label_encoder.pkl       # Encoded output labels
├── tokenizer.pkl           # Tokenizer for input preprocessing
├── main.py                 # Main script to run assistant
├── model_test.py           # Test the trained model
├── model_train.py          # Train the assistant model
```


## ▶️ How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/voice-assistant.git
    cd voice-assistant
    ```

2. (Optional) Create a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate     # On Windows: venv\Scripts\activate
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the assistant:
    ```bash
    python main.py
    ```

> 💡 Make sure your microphone is working and Python 3.8+ is installed.


## 🔮 Future Improvements
1. Add context-based conversations
2. GUI-based interface for better usability
3. Add support for real-time weather, news, or reminders
4. Voice-based system settings control
5. Support for multiple languages


