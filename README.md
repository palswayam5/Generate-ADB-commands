# Generate-ADB-commands

**Automate Android interactions using natural language prompts with LLM-powered ADB command generation.**

## 🚀 Overview
This project leverages **LLMs (Large Language Models)** to convert natural language instructions into **Android Debug Bridge (ADB) commands**, enabling seamless mobile automation. It eliminates the need for manual ADB command lookup, making mobile testing and automation more efficient.

## 🔥 Features
✅ **Natural Language to ADB Command Conversion** – Generate ADB commands using simple English prompts.  
✅ **LLM-Powered Parsing** – Uses AI for better accuracy and robustness across different command variations.  
✅ **Enhanced Mobile Automation** – Works with tools like Appium and Uiautomator2 for testing and UI interactions.  
✅ **Supports Various ADB Actions** – Includes taps, swipes, text input, screenshots, and more.  

## 🛠️ Setup & Installation
### Prerequisites
- Python 3.8+
- OpenAI API / Gemini API (for LLM processing)
- ADB Installed (`adb` should be accessible from the command line)

### Installation Steps
1. **Clone the repository**
   ```bash
   git clone https://github.com/palswayam5/Generate-ADB-commands.git
   cd Generate-ADB-commands
   ```  
2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```  
3. **Set up API key** (if using OpenAI or Gemini)
   ```bash
   export OPENAI_API_KEY="your-api-key-here"
   ```  

## 🚀 Usage
1. **Run the script**
   ```bash
   python generate_adb.py "Open the settings app"
   ```  
2. **Example Commands:**  
   - `"Take a screenshot"` → `adb exec-out screencap -p > screen.png`  
   - `"Swipe left on the home screen"` → `adb shell input swipe 900 1000 100 1000`  
   - `"Tap on coordinates (500, 1200)"` → `adb shell input tap 500 1200`  

## 📌 Applications
- **Mobile App Testing** – Automate UI interactions without manual ADB command writing.  
- **Device Control** – Perform remote actions on Android devices.  
- **Task Automation** – Use natural language to automate routine actions like unlocking the device, opening apps, and navigating.  

## 🎯 Future Improvements
- Expand LLM support for more precise command generation.
- Enhance context awareness for complex multi-step interactions.
- Integrate with voice-based assistants for hands-free automation.
