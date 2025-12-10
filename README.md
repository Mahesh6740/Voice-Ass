# 🎤 Voice Assistant (Web-Based)

A fully interactive **web-based Voice Assistant** built using **HTML, CSS, and JavaScript**.  
This assistant can respond to voice commands such as greetings, date/time, jokes, calculations, and more — directly from the browser using **Web Speech API** (Speech Recognition + Speech Synthesis).

---

## 🚀 Features

### 🔊 Speech Recognition
- Starts listening when the mic button is pressed  
- Converts speech → text using `webkitSpeechRecognition`  
- Detects common voice commands

### 🗣️ Speech Response
- Uses browser’s **SpeechSynthesis** to speak back
- Smooth and natural voice responses

### 📅 Supported Commands
The assistant can understand several built-in commands:
- **“Hello / Hi”** → Greeting  
- **“What’s the time?”** → Current time  
- **“What’s the date?”** → Today’s date  
- **“Tell me a joke”** → Random joke generator  
- **“Weather”** → Mock weather response  
- **Math calculations**  
  - Examples: `10 + 5`, `20 - 4`, `15 * 3`, `10 / 2`
- **“Who are you?”** → About assistant  
- **“Help”** → Shows available commands  

---

## 📝 Smart Command History
- Stores last **10 commands** using `localStorage`  
- Automatically displays recent commands with timestamps  
- Option to clear history

---

## 🎛️ UI Controls
- **🎤 Mic Toggle** – Starts/Stops listening  
- **📋 Copy** – Copies the assistant’s response to clipboard  
- **🗑️ Clear** – Clears command history  
- **❓ Help** – Shows available commands  

---

## 💻 Technologies Used

| Technology | Purpose |
|-----------|---------|
| **HTML5** | Interface layout |
| **CSS3**  | Modern UI styling |
| **JavaScript** | Core logic |
| **Web Speech API** | Speech Recognition + Speech Synthesis |
| **LocalStorage** | History storage |

---

## 📂 Project Structure

All logic and UI are contained in the single file `Voice.html` for easy deployment.

---

## 🛠️ How to Use

1. Open the **Voice.html** file in **Chrome** or **Edge**  
   (Firefox does NOT support Web Speech API fully)
2. Click the **microphone button**
3. Speak a command such as:
   - “Hello”
   - “What’s the time?”
   - “Tell me a joke”
   - “Calculate 10 + 5”
4. The assistant will:
   - Recognize your voice  
   - Show the result on screen  
   - Speak the answer aloud  

---

## 🔐 Browser Requirements

Because this project uses **webkitSpeechRecognition**, it works best on:

- ✔ Google Chrome  
- ✔ Microsoft Edge  
- ✖ Firefox (not supported)  
- ✖ Safari (partial support)

---

## 🧪 Demo Commands (Examples)

| Command | Response Example |
|--------|------------------|
| “Hello” | “Hello! How can I help you today?” |
| “What’s the date?” | “Today is 09/02/2025” |
| “Calculate 8 * 7” | “8 * 7 equals 56” |
| “Tell me a joke” | Random joke |

---

## 🙌 Future Enhancements

- Real weather API integration  
- ChatGPT API for advanced responses  
- Multi-language support  
- Dark/Light mode toggle  
- Save jokes or favorite commands  

---

## 📸 UI Preview

(Add screenshot here using `![Screenshot](screenshot.png)`)

---

## 👨‍💻 Author

**Mahesh Kummari**  
- GitHub: https://github.com/Mahesh6740  
- LinkedIn: https://www.linkedin.com/in/mahesh-kummari-a666bb266/

---

## 📜 License
This project is open-source and free to use for learning and development.
