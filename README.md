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
