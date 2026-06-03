# reacoaxer

**A real-time extension for Reaper (Digital Audio Workstation by Cockos Incorporated) that analyzes live audio stems and generates musician-friendly performance cues.**

Designed for live performers, `reacoaxer` "coaxes" optimal performance from WAV stems through adaptive, low-latency feedback.

## ✨ Features
- **Real-Time Analysis**: Monitors live stems with low-latency Lua scripting.
- **Actionable Cues**: Translates audio data into visual or OSC prompts.
- **Adaptive Feedback**: Adjusts suggestions based on performance context.
- **Workshop Ready**: Ideal for stage shows and interactive installations.

## 🚀 Installation
1. Download the `.lua` script from the [Releases](../../releases) tab.
2. Place it in your Reaper Scripts folder:
   - **Win**: `%APPDATA%\REAPER\Scripts\`
   - **Mac**: `~/Library/Application Support/REAPER/Scripts\`
   - **Lin**: `~/.config/REAPER\Scripts\`
3. Restart Reaper or select **Actions > Reload extension scripts**.

## 🎮 Usage
1. Load live WAV stems into tracks.
2. Run action: **`reacoaxer: Start live stem coaxing`**.
3. Follow on-screen cues or OSC output.
4. Adjust sensitivity via **`reacoaxer: Settings`**.

## 🛠 Development
Built with **Lua** (Reaper API v6.0+).

To download the source code:
```bash
git clone https://github.com/spunkshadows/reacoaxer.git
```
