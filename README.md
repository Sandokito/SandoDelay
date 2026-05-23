# SandoDelay
# SandoDelay

Dynamic live stream delay system for OBS, Twitch

SandoDelay is a RAM-based dynamic stream delay application designed for creators who need instant LIVE/DELAY switching with minimal latency and low CPU usage.

---

# Features

- Dynamic delay system
- Instant LIVE ↔ DELAY switching
- RAM ring buffer architecture
- No TS segment files
- FFmpeg passthrough (copy codec)
- OBS integration
- Stream Deck support
- Twitch compatible
- Kick compatible
- YouTube compatible
- Low CPU usage
- Stable playback pipeline

---

# Architecture

```text
OBS → FFmpeg → RAM Ring Buffer → FFmpeg Output → Twitch

Installation
Download SandoDelaySetup.exe
Run installer
Configure your stream settings
Start streaming
SmartScreen Warning

Windows may display a SmartScreen warning because the application is new and not digitally signed yet.

To continue:

Click "More info"
Click "Run anyway"

The application does NOT contain malicious behavior.
v2.0 Beta

Technologies
Go
Wails
FFmpeg
OBS
Planned Features
Multi-platform streaming
Advanced monitoring
Better OBS dock sync
Signed binaries
Auto updates
Web dashboard
Stream Deck Support

The Stream Deck plugin supports:

LIVE mode switching
DELAY mode switching
Real-time status sync
OBS panel sync
Performance

Designed for:

Low CPU usage
Stable RAM buffering
Fast recovery
Instant mode switching
License

MIT
