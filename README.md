# JARIVSedu
Students struggle with managing assignments, staying focused, and organizing their study time. Existing tools are often fragmented—calendars, to-do lists, music apps, and timers all live separately—and require constant manual interaction. 


## API Keys Required

This project uses third-party services. Please obtain your own free API keys:

- **Picovoice (Porcupine wake-word detection)**  
  Get a free API key from: https://console.picovoice.ai

- **Groq (LLM inference)**  
  Get a free API key from: https://console.groq.com
# JARVIS-edu

Notes:
Some packages have specific requirements:
pvporcupine: Requires a Picovoice access key (set in code).
groq: Requires a Groq API key.
faster-whisper: GPU acceleration is optional (uses CPU by default, but torch with CUDA if available).
silero-vad-utils: The package providing load_silero_vad (commonly installed as silero-vad-utils or via torch hub).
To install: pip install -r requirements.txt
The project also uses audio files (*.mp3) and a JSON data file, but no additional Python packages for those.
AI based question handling.JARVIS can answer to any questions.

llama-3b-8b-instant
