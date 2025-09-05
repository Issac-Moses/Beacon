# 🔹 Beacon – Voice Controlled AI Assistant  

Beacon is a lightweight AI-powered desktop assistant that listens to your voice, executes commands, and assists you with daily tasks.  
It uses **Whisper.cpp** for speech recognition and integrates automation features to make your workflow faster and more accessible.  

[![Beacon Logo](BEACON.png)](https://github.com/Issac-Moses/Beacon/blob/main/BEACON.png)


## 🚀 Features
- 🎙️ **Wake Word Activation** → Say *"Hey Beacon"* to start listening  
- 🗣️ **Voice Commands** → Perform tasks hands-free  
- 📸 **Screenshot Capture** → Automatically take desktop screenshots  
- 📂 **Cross-Platform Support** → Works on Windows, Linux, and macOS  
- ⚡ **Optimized Performance** → Runs efficiently on your CPU with full resource utilization  
- 🛠️ **Customizable Shortcuts** → Desktop shortcut & Start Menu integration  
- 📜 **License Window** → Displays license agreement during installation  



## 📦 Installation
1. Download the **Beacon Installer (SFX Archive)**  
2. Run the installer and follow the setup instructions  
3. The installer will:
   - Extract required files  
   - Run `windows.bat` automatically  
   - Create a **desktop shortcut** for `Beacon.exe`  



## 🖥️ Usage
- Say **"Hey Beacon"** → Assistant activates  
- Speak your command clearly → Example: *"Take screenshot"*  
- Beacon executes the action and gives feedback  
- Screenshots are saved in the default folder (`G:\Assistant\screen.png` by default)  



## 📁 Project Structure
```bash
      Beacon/
      │── beacon/                   # Core assistant files
      │── models/                   # AI/Whisper models
      │── whisper.cpp/           # Speech-to-text engine
      │── Beacon.exe             # Main application
      │── accuracy.py            # Accuracy testing script
      │── speed.py                # Performance testing script
      │── windows.bat          # Windows startup script
      │── Mac.bat                 # MacOS startup script
      │── Linux.bat               # Linux startup script
      │── requirements.txt   # Dependencies
      │── LICENSE.txt           # License agreement
      │── gemini_key.txt      # API key storage
      │── logo.ico                # Application icon
      │── screen.png           # Screenshot output
```

## 🛠️ Requirements
- **OS**: Windows / Linux / MacOS  
- **CPU**: Intel i5-2400 or higher (Beacon is optimized to use full CPU power)  
- **RAM**: 8 GB minimum (16 GB recommended)  
- **Dependencies**: Listed in `requirements.txt`  

Install dependencies with:
```bash
pip install -r requirements.txt
```
## 🔮 Future Upgradation  
Beacon is designed with scalability in mind. In future updates, the assistant will be enhanced with:  
- **Smarter Voice Recognition** using advanced ML models.  
- **Multi-language Support** for a wider audience.  
- **Plugin System** to allow developers to integrate custom commands.  
- **Cross-Platform Compatibility** (Windows, Linux, macOS).  
- **Accessibility Features** for people with disabilities, ensuring inclusivity.  

---

## ⚙️ How to Run My Code  

Follow these steps to set up and run Beacon on your system:  

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/YourUsername/beacon.git
   cd beacon
   ```
2. **Set Up Virtual Environment (Recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Linux/Mac
   venv\Scripts\activate      # On Windows
   ```
3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```
4. **Run Beacon**
   ```bash
   python beacon.py
   ```
- Beacon will now listen for your commands and respond through voice + automation features.

##🎤 How to Use Beacon (Accuracy.py Explained)
- The accuracy.py file helps improve the command recognition accuracy by:
- Listening to Input – Captures your microphone input via Whisper.cpp.
- Processing the Text – Converts speech into structured text commands.
- Matching Commands – Compares spoken commands with the pre-defined dictionary.
- Example: “open browser” → maps to open_browser() function.
- Error Handling – If input is unclear, it prompts you to repeat.
- Logging Results – Stores recognition results for accuracy analysis and debugging.
- This ensures Beacon doesn’t just “hear” you but also understands you correctly.

## Upcoming Version Release
- We are already planning Beacon V2.0, with a focus on accessibility and real-world utility:
- Blind-Friendly Mode:
1. Full voice feedback for every action.
2. Auto-reading system messages, errors, and outputs.
3. Hands-free navigation support.
- Smart Task Scheduling: Set reminders, timers, and voice-controlled notes.
- IoT Integration: Control smart devices like lights, fans, or appliances.
- Improved Context Awareness: Beacon will remember past commands for a smoother conversation.

**👉 Stay tuned for release updates in the Releases tab of this repo!**
