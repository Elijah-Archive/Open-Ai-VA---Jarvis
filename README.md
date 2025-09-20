# Jarvis AI Assistant (Archive)

**Originally built:** ~2023 • **Status:** Archived • **Stack:** Python (OpenAI, Pygame, RealtimeSTT, Spotipy)

## What it does
A Jarvis-like voice assistant inspired by Iron Man.  
- Responds conversationally with time-aware greetings.  
- Executes functions (Spotify, web search, light control, silent mode).  
- Provides voice and text interaction (TTS + STT).  

## Quickstart
```bash
# prerequisites
Python 3.10+
pip install -r requirements.txt

# setup
export OPENAI_API_KEY=your_key_here
# (Optional) Spotify client_id, client_secret, redirect_uri in tools.py

# run
python jarvis.py
