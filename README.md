# MrBangerClips

AI-powered clip maker for long videos and live streams.

Paste a YouTube, Twitch or Kick link (or upload a file) and MrBangerClips finds the moments worth clipping, cuts them to vertical 9:16 video, adds styled word-by-word captions, and writes hooks and titles. It can also watch a creator while they are live and produce clips as things happen.

Everything runs on your own machine. There are no limits, no subscriptions, and clips are rendered without watermarks.

## Quick Start

### 1. Requirements
- Python 3.10+
- `ffmpeg` (installed and added to PATH)

### 2. Clone and Setup
```bash
git clone https://github.com/saivi/MrBangerClips.git
cd MrBangerClips
pip install -r requirements.txt
```

### 3. Run MrBangerClips
```bash
python -m studio.server
```
Open [http://127.0.0.1:8765](http://127.0.0.1:8765) in your browser.

## Features
- **Smart AI Clipping**: Automatically finds the most viral, engaging moments.
- **Word-by-Word Captions**: High-visibility animated captions with custom fonts (Bounce, Clean, Hype).
- **Live Stream Monitoring**: Records live streams on Twitch, Kick, and YouTube and clips highlights in real-time.
- **Multi-Platform Support**: Export ready-to-post vertical shorts for TikTok, Instagram Reels, and YouTube Shorts.
- **Bring Your Own AI**: Connect Gemini, OpenAI, Claude, Groq, xAI, Ollama, or any compatible model.
- **Self-Hosted & Private**: Your videos and data stay completely on your computer or private server.

## License
MIT License. Free and open source.
