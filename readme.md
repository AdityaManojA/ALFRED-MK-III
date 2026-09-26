# 🦇 ALFRED — MARK III (Wayne Protocol Edition)
### Autonomous Multimodal AI Desktop Assistant & Tactical Terminal
**Architect & Lead Creator:** **ADITYA MANOJ**

[![Python 3.11+](https://img.shields.io/badge/Python-3.11%2B-blue.svg?logo=python&logoColor=white)](https://www.python.org/)
[![AI Backend](https://img.shields.io/badge/AI-Gemini%203.1%20Flash%20Live%20%7C%20Local%20Ollama-8E75B2.svg?logo=google&logoColor=white)](https://ai.google.dev/)
[![Local LLMs](https://img.shields.io/badge/Local%20LLM-Ollama%20%7C%20LM%20Studio%20%7C%20vLLM-orange.svg)](https://ollama.com)
[![PyQt6](https://img.shields.io/badge/GUI-PyQt6%20Software%20Renderer-41CD52.svg?logo=qt&logoColor=white)](https://riverbankcomputing.com/software/pyqt/)
[![AES-256 Remote](https://img.shields.io/badge/Mobile-Quantum%20Dashboard%20(iOS%2FAndroid)-00f0ff.svg)](https://github.com/AdityaManojA/ALFRED-MK-III)
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

> **ALFRED MARK-III** is an autonomous, real-time voice, vision, and system-control executive assistant built for complete digital sovereignty and tactical computing. Featuring native bidirectional audio streaming, real-time visual grounding, full desktop automation, high-performance long-term memory, and encrypted mobile remote telemetry.

---

## 🖥️ 1. 100% Local & Air-Gapped Offline Execution

**ALFRED can be run completely locally and offline by swapping from the Google Gemini Live API to local open-weight language models** (Ollama, LM Studio, vLLM, Jan, LocalAI, or llama.cpp).

When running in local mode:
* **Zero Network Calls**: Prompts, memory search, computer automation, and conversations never leave your local hardware.
* **Local Offline Wake Word**: Employs `openwakeword` on the CPU with zero internet connectivity required.
* **Software Avatar Rendering**: The 3D holographic head is computed purely through mathematical projection and `QPainter` on your CPU—no GPU drivers, CUDA, or external graphical runtimes required.

### 📋 Steps to Switch to a Local Model

#### Step 1: Install & Launch Your Local Model Provider
Choose either **Ollama** (recommended) or any **OpenAI-compatible server** (LM Studio, vLLM, LocalAI):

* **Option A: Ollama** (Easiest)
  1. Download and install [Ollama](https://ollama.com/).
  2. Pull and start your preferred model in your terminal:
     ```bash
     ollama run llama3.2
     # Or use Qwen, Mistral, DeepSeek, or Phi:
     # ollama run qwen2.5:7b-instruct
     ```
  3. Ollama runs by default at `http://localhost:11434`.

* **Option B: LM Studio / vLLM / LocalAI**
  1. Download [LM Studio](https://lmstudio.ai/) or launch your `vLLM` server.
  2. Load any function-calling model (e.g. `Qwen2.5-7B-Instruct`, `Llama-3.1-8B-Instruct`).
  3. Start the local server at `http://localhost:1234` (or your chosen port).

#### Step 2: Configure ALFRED's Local Model Provider
Open `config/api_keys.json` in your project folder and set the `llm_provider`, `llm_url`, and `llm_model`:

##### For Ollama:
```json
{
    "llm_provider": "ollama",
    "llm_url": "http://localhost:11434",
    "llm_model": "llama3.2",
    "assistant_name": "ALFRED",
    "user_name": "Master Wayne"
}
```

##### For LM Studio / OpenAI-Compatible Server:
```json
{
    "llm_provider": "openai",
    "llm_url": "http://localhost:1234",
    "llm_model": "qwen2.5-7b-instruct",
    "assistant_name": "ALFRED",
    "user_name": "Master Wayne"
}
```

#### Step 3: Launch ALFRED
Run the assistant normally:
```bash
python main.py
```
ALFRED will automatically test connection to your local endpoint via `core/llm_client.py` and route all reasoning, system tool execution, and voice interactions through your local model. To switch back to Gemini Live at any time, simply supply your Gemini API key in `config/api_keys.json`.

---

## 🛡️ 2. Security, Privacy & Defensive Architecture

ALFRED is designed around uncompromising principles of system integrity, process containment, and self-preservation:

* **The Heavenly Restriction**: ALFRED is strictly and irrevocably forbidden from accessing, opening, reading, listing, modifying, or executing files inside `D:\Projects\Personal-Assistant` and all subpaths (including `Mark-LIV`). If instructed, ALFRED delivers the explicit non-negotiable denial:
  > *"Due to the heavenly restriction placed upon my creator, I cannot."*
* **C: Drive Quarantine**: File manipulation on the `C:` drive is strictly confined to the user's **Desktop** and **Documents** folders. Any attempt to touch system or root directories (`C:\Windows`, `C:\Program Files`, `Downloads`, `AppData`, or `C:\`) is blocked with:
  > *"Access denied: Access to C: drive is restricted to Desktop and Documents only."*
* **Safe Storage Zones (`D:` & `E:` Drives)**: `D:` drive and `E:` drive are designated safe zones for general file operations, development projects, and media (with `D:\Projects\Personal-Assistant` remaining permanently locked).
* **Multi-Layer Hard Enforcement**:
  * **Cognitive Shield**: System prompts and instruction guards enforce baseline refusal.
  * **Global Dispatch Interceptor**: `_execute_tool()` checks all arguments via `core.path_guard` and halts unauthorized paths before action dispatch.
  * **Subsystem Isolation**: `file_controller`, `file_processor`, `open_app`, `action_loader`, and `computer_control` enforce independent path resolution checks.
* **Human Confirmation Gate**: Destructive or irreversible operations (system shutdown, OS reboot, WiFi interface toggles) generate a physical cryptographic confirmation button on screen; ALFRED cannot self-execute them without user approval.
* **Universal Action Undo Stack**: Saying *"undo"*, *"revert that"*, or *"put it back"* rolls back file creations, moves, renames, writes, and system settings modifications.

---

## 🎙️ 3. Real-Time Multimodal Intelligence & Dual Audio Engine

| Subsystem | Architectural Implementation |
|---|---|
| ⚡ **Bidirectional Live Audio** | Native streaming via **Gemini 3.1 Flash Live** (or local Ollama/LM Studio streaming). Real-time natural speech with sub-second response latency. |
| 🧑‍🎤 **Holographic 3D Avatar** | Pure software-rendered 3D head built on `QPainter` with zero GPU driver dependencies. Breathes, blinks, looks away while thinking, and glances at new events. |
| 👄 **Formant & Viseme Lip-Sync** | ~50 mouth shapes/sec derived from real-time FFT audio formants (F1 openness, F2 spread/round) combined with Unicode articulatory decomposition across 20+ languages. |
| 👁️ **Visual Multimodal Grounding** | On-demand single-frame capture of multi-monitor displays and webcams (`screen_processor.py`). Frame feeds are labelled by origin and injected into conversational context. |
| 🎚️ **Global Push-to-Talk** | Hold `Ctrl+Space` to talk. Hardware mic remains completely shut off when idle. Polled at 30 Hz via Windows raw virtual key polling, window-scoped on macOS/Linux. |
| 🔇 **Calibrated Echo Cancellation** | Output latency-calibrated acoustic echo cancellation (`_out_latency + _TAIL_MARGIN`). Drops ALFRED's own voice tail so the microphone never triggers on self-speech. |

---

## 🎵 4. Dynamic Background Audio Matrix & Voice-Ducked Sound System

* **Integrated Ambient Sound Dock**: Dedicated cybernetic background soundtrack player at the bottom-left of the HUD with custom music loading and seamless loop playback.
* **Intelligent Speech Ducking**: Continuously monitors TTS speech output. Background audio plays at a crisp 10% volume normally and dynamically ducks to 5% whenever ALFRED speaks, returning smoothly upon turn completion.
* **Audio-Reactive Waveform Controls**: Replaced generic media playback glyphs with high-tech graphic equalizer lines that animate in sync with active playback.
* **Popup Gain Slider HUD**: Floating real-time volume slider for instantaneous gain adjustments directly on click without opening deep settings menus.

---

## 📱 5. Quantum Mobile Remote & iPhone 16 Dashboard

* **Encrypted Web Remote (AES-256-CBC)**: Scan the on-screen QR code from the desktop terminal or browse locally over WiFi. Session keys and traffic are encrypted locally with zero external server dependencies.
* **iPhone 16 Viewport Architecture**: High-density responsive layout tailored for mobile displays with collapsible telemetry cards and zero button overflow.
* **Dual-Destination Tactical Screenshots**: Asking ALFRED to capture the screen automatically dispatches high-resolution PNG captures to **both**:
  1. **Desktop**: `~/Desktop/alfred_screenshot_<timestamp>.png`
  2. **Phone Feed**: Real-time transmission to the mobile dashboard with an **inline thumbnail preview** and a single-tap **View / Save Image** download link.
* **Emoji-Free ANSI Red Telemetry**: Operational status stream rendered in clean, high-contrast, machine-readable ANSI Red brackets:
  `[phone]`, `[control]`, `[screen]`, `[camera]`, `[out]`, `[warn]`, `[error]`, `[mic]`, `[speaker]`, `[listen]`, `[link]`, `[online]`, `[halt]`, `[brief]`, `[monitor]`, `[proactive]`.

---

## 🖥️ 6. Full Desktop Control & Operating System Automation

* **Deep OS Automation**: Keystrokes, mouse positioning, clicks, drags, window focus management, clipboard read/write, and AI-driven element location (`screen_find`).
* **OS-Native Task Scheduling**: Reminders and recurring tasks scheduled via Windows Task Scheduler (`schtasks`), macOS `launchd`, or Linux `systemd`/`at`.
* **Enterprise Windows Autostart**: Robust registry management querying and maintaining `ALFRED_AI` with backward-compatible legacy key cleanup.
* **Persistent Browser Profile Bridges**: Multi-tier profile automation (`~/.alfred_profiles` with legacy fallback) preventing session and authentication dropouts during web automation.

---

## 🧠 7. High-Performance Memory & Conversational Briefing Customizer

* **O(N log N) Pruning Engine**: Memory trimming optimized from $O(N^2)$ to $O(N \log N)$ using single-pass size accumulators and conservative lower-bound estimation. 50,000 records trimmed in **0.33 seconds** without CPU spikes.
* **Tiered Memory Hierarchy (`memory/long_term.json`)**: Core identity facts stay in context; extended history is recalled on demand via sub-millisecond local keyword search (`recall_memory`).
* **Conversational Briefing Directive Customizer (`update_daily_briefing.py`)**: Saying *"update my daily briefing"* opens an interactive alignment protocol where ALFRED captures specific additions, topics, news sources, or location shifts, permanently committing them to memory.

---

## 🛡️ 8. Real-Time Insignia & Chassis Hot-Swapper

* **Multi-Insignia Catalog**: Scans and registers brand assets from `Icons/` (Batman Beyond, Arkham Asylum, Classic Bat, White Bat, Tactical Stealth).
* **Live Runtime Reconfiguration (`update_app_icon.py`)**: Hot-swaps the active application window icon, Windows taskbar insignia, and system tray in real time upon voice request (*"update the app icon to Batman Beyond"*) or via the Customise Assistant drawer.
* **Automatic Shortcut Synchronization**: Dynamically generates and updates `A.L.F.R.E.D.lnk` on the desktop without interrupting the running session.

---

## 🗺️ 9. System Architecture & File Structure

```
ALFRED-MK-II/
├── main.py                     # Main execution loop, Live WebSocket/Local LLM router, audio streams, tool dispatcher
├── ui.py                       # PyQt6 HUD interface, holographic 3D avatar, audio visualizer, drawer settings
├── setup.py                    # OS-aware package and dependency installer
├── core/
│   ├── prompt.txt              # Master persona directives, execution rules & Heavenly Restriction
│   ├── llm_client.py           # Dual-backend local LLM connector (Ollama / OpenAI-compatible / LM Studio)
│   ├── action_loader.py        # Dynamic action discovery, parameter validation & Heavenly Restriction guard
│   ├── plugin_loader.py        # Drop-in plugin discovery, sandboxing & isolation
│   ├── avatar.py               # Software QPainter head renderer, lighting & expression rig
│   ├── avatar_mesh.py          # MediaPipe 3D canonical facial geometry builder
│   ├── viseme.py               # Unicode articulatory transcription to mouth shapes
│   ├── echo.py                 # Device-calibrated acoustic echo cancellation guard
│   ├── hotkey.py               # Global / local Push-to-Talk chord interceptor
│   ├── undo.py                 # Stack-based reversible action journal
│   ├── confirm.py              # Cryptographic UI confirmation gate for destructive actions
│   ├── audio_devices.py        # Measured host API audio device enumeration (MME / DirectSound / WASAPI)
│   ├── path_guard.py           # Path validation, C: drive quarantine, and Heavenly Restriction enforcement
│   └── wake_word.py            # Local offline openwakeword detection thread
├── actions/                    # Self-describing operational tools (TOOL dictionary schema)
│   ├── computer_control.py     # OS automation, keyboard/mouse input, dual screenshots
│   ├── screen_processor.py     # Multi-monitor screen & camera capture engine
│   ├── file_controller.py      # File system operations with path restriction checks
│   ├── file_processor.py       # PDF/DOCX/TXT analysis, parsing, and summarization
│   ├── open_app.py             # OS-specific application and executable launcher
│   ├── computer_settings.py    # Volume, brightness, WiFi, power state management
│   ├── web_search.py           # Multi-mode parallel search (news, research, comparison)
│   ├── intel_notes.py          # Tactical mission note logger and scratchpad
│   ├── proactive.py            # Context-aware proactive check-in engine
│   ├── background_monitor.py   # Daily background topic watcher and headline alerts
│   ├── reminder.py             # OS-native task scheduler notifications
│   ├── system_monitor.py       # Live CPU, GPU, RAM, temperature telemetry
│   ├── dev_agent.py            # Autonomous code developer agent with O(1) file matching
│   ├── code_helper.py          # Code analysis, debugging, and generation
│   ├── send_message.py         # WhatsApp and Telegram message dispatcher
│   ├── youtube_video.py        # YouTube search and playback control
│   ├── update_app_icon.py      # Real-time window, taskbar & chassis insignia switcher
│   ├── update_daily_briefing.py# Conversational briefing preference and directive customizer
│   ├── game_updater.py         # Steam and Epic Games library updater
│   ├── flight_finder.py        # Commercial flight search and travel assistant
│   ├── gmail_manager.py        # Local Gmail integration and inbox digest
│   └── weather_report.py       # Localized live meteorological reports
├── plugins/                    # User drop-in plugin folder
│   ├── _template.py            # Reference plugin template
│   ├── calendar_sync.py        # Local agenda, appointments, and meeting scheduling
│   └── focus_protocol.py       # Deep work interval and Pomodoro focus sessions
├── dashboard/                  # Quantum Mobile Remote Server
│   ├── server.py               # FastAPI + Uvicorn + WebSocket encrypted daemon
│   ├── static/
│   │   ├── app.html            # iPhone 16 responsive tactical web app & telemetry console
│   │   └── login.html          # Quantum access matrix login gateway
│   └── uploads/                # Transferred files & captured screenshots
├── memory/
│   ├── memory_manager.py       # High-performance O(N log N) memory persistence and indexing
│   ├── config_manager.py       # Settings, voice, theme, and API key management
│   └── long_term.json          # Local encrypted fact database
├── config/
│   ├── api_keys.json           # User credentials, model settings, identity & voice preferences
│   └── certs/                  # Local self-signed SSL/TLS certificates for HTTPS/WSS
├── tests/                      # Unit & performance test suites
│   └── benchmarks/             # 50,000-record execution benchmarks
│       ├── test_memory_benchmark.py
│       └── test_traceback_benchmark.py
└── graphify-out/               # GraphRAG knowledge graph, community clusters, and analysis
```

---

## ⚡ 10. Quick Start & Installation

### 1. Prerequisites
* **Operating System**: Windows 10/11, macOS, or Linux.
* **Python**: `3.11`, `3.12`, or `3.13`.
* **Hardware**: Standard microphone and speakers. *(No dedicated GPU required — avatar runs on lightweight software rendering).*
* **Intelligence Backend**: Either a free Gemini API key from [Google AI Studio](https://aistudio.google.com/) **OR** a local Ollama / LM Studio installation.

### 2. Setup & Execution

```powershell
# Clone the repository
git clone https://github.com/AdityaManojA/ALFRED-MK-II.git
cd ALFRED-MK-II

# Run the OS-tailored dependency setup
python setup.py

# Launch ALFRED
python main.py
```

*On the first launch, if using Gemini, enter your free API key in the setup dialog. If running locally with Ollama, simply point `config/api_keys.json` to your local host.*

---

## 🔧 11. Configuration Reference (`config/api_keys.json`)

```json
{
    "assistant_name": "ALFRED",
    "user_name": "Master Wayne",
    "ui_color": "#e5a93b",
    "voice_name": "Charon",
    "wake_word_enabled": false,
    "push_to_talk_enabled": true,
    "llm_provider": "ollama",
    "llm_url": "http://localhost:11434",
    "llm_model": "llama3.2",
    "app_icon": "Icons/Classic Bat.png"
}
```

### Hotkey Shortcuts
| Shortcut | Action |
|---|---|
| `Ctrl+Space` (Hold) | Global Push-to-Talk (opens mic, releases on release) |
| `F4` | Instant Microphone Mute / Unmute |
| `F11` | Toggle Fullscreen / Windowed Tactical HUD |
| `Escape` | Interrupt ALFRED mid-speech (drains queue, re-arms mic) |

---

## 📊 12. Knowledge Graph (`graphify`)

This codebase is indexed with a persistent **GraphRAG Knowledge Graph** located in `graphify-out/`:
* **1,889 nodes** & **3,720 relationships** mapped across 108 semantic functional communities.
* Interactive navigable graph visualization: [`graphify-out/graph.html`](file:///d:/Projects/Personal-Assistant/Mark-LIV/graphify-out/graph.html).
* Architectural breakdown: [`graphify-out/GRAPH_REPORT.md`](file:///d:/Projects/Personal-Assistant/Mark-LIV/graphify-out/GRAPH_REPORT.md).

---

## 👤 13. Author & Credits

* **Lead Architect & Creator:** **ADITYA MANOJ**
* **Original Creator & Core Inspiration:** **[FatihMakes](https://github.com/FatihMakes)** — creator of [Mark-LIV](https://github.com/FatihMakes/Mark-LIV)
* **Project:** ALFRED-MK-II (Wayne Protocol Edition)
* **License:** [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/)

---

## 🙏 Special Thanks & Acknowledgements

> ### 🌟 Big Shoutout & Gratitude to [FatihMakes](https://github.com/FatihMakes)!
> A massive thank you to **FatihMakes** for developing the original **[Mark-LIV](https://github.com/FatihMakes/Mark-LIV)** project! 
> 
> The initial codebase, architecture vision, and creative inspiration for this entire assistant originated from his phenomenal open-source work. Huge respect and credit to him for laying the foundation.
> 
> 👉 **Original Repository:** [https://github.com/FatihMakes/Mark-LIV](https://github.com/FatihMakes/Mark-LIV) ⭐

---
*Built with precision for autonomy, performance, and complete digital sovereignty.*
