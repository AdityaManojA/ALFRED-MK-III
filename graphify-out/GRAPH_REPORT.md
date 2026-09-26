# Graph Report - Alfred-Mark-III  (2026-09-26)

## Corpus Check
- 79 files · ~170,497 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 8 file(s) not represented in the graph (top: (none) 3, .ico 2, .obj 2)

## Summary
- 2026 nodes · 3976 edges · 116 communities (92 shown, 24 thin omitted)
- Extraction: 96% EXTRACTED · 4% INFERRED · 0% AMBIGUOUS · INFERRED: 165 edges (avg confidence: 0.86)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `d619ac95`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- game_updater.py
- cache.py
- computer_settings.py
- TronScoreBackgroundPlayer
- file_controller.py
- KokoroTTSEngine
- HoloAvatar
- MainWindow
- TacticalAudioPlayerWidget
- gemini.py
- .__init__
- llm_client.py
- code_helper.py
- ui.py
- memory_manager.py
- _BrowserSession
- computer_control.py
- dev_agent.py
- file_processor.py
- mono_font
- EchoGuard
- JarvisUI
- 🦇 ALFRED — MARK III (Wayne Protocol Edition)
- .__init__
- JarvisLive
- is_heavenly_restricted
- crypto-js.min.js
- config_manager.py
- ._apply_ptt_shortcut
- send_message.py
- confirm.py
- server.py
- background_monitor.py
- HudCanvas
- computer_settings
- TestCentralizedCache
- avatar_mesh.py
- system_monitor.py
- action_loader.py
- pathlib
- CentralizedCache
- _SessionRegistry
- web_search.py
- RemoteKeyOverlay
- qcol
- .run
- ._build_app
- save_app_icon
- _SysMetrics
- load_api_keys
- NotesTerminalWidget
- screen_processor.py
- DashboardServer
- browser_control.py
- PushToTalk
- format_memory_for_prompt
- setter
- gmail_manager.py
- CustomizeOverlay
- ._build_right_panel
- main.py
- ._play_audio
- MemoryOverlay
- Graphify + Antigravity Project Workflow & Setup Guide
- _get_macos_wifi_interface
- ._launch
- _ensure_network_access
- rules/graphify.md
- weather_report.py
- workflows/graphify.md
- _detect_action
- ._apply_name_update
- WhisperSTT
- daily_brief.py
- WakeWordDetector
- tech_font
- datetime
- get_input_device
- _trim_to_limit
- _template.py
- _get_base_dir
- LogWidget
- _tlog
- ._wake_state
- _RootShim
- .__init__
- get_plugin_config
- ._build_jarvis_icon
- type_text
- json
- ._build_config
- Daily Brief Protocol
- Email Handling Rules
- Executive Assistant Persona & Behavioral Standards
- .clear_chat
- /email-triage Workflow
- get_plugin_enabled
- ClipboardPanel
- intel_notes.py
- pil
- _VolumeSliderPopup
- .request_reconnect
- calendar_sync.py
- _HudOverlay
- focus_protocol.py
- ._decrypt
- ._save_session_summary
- ._listen_audio
- SubjectDossierCard
- Steps

## God Nodes (most connected - your core abstractions)
1. `MainWindow` - 91 edges
2. `JarvisLive` - 53 edges
3. `JarvisUI` - 45 edges
4. `tech_font()` - 35 edges
5. `mono_font()` - 35 edges
6. `_BrowserSession` - 32 edges
7. `TronScoreBackgroundPlayer` - 26 edges
8. `qcol()` - 25 edges
9. `_resolve_path()` - 24 edges
10. `file_controller()` - 24 edges

## Surprising Connections (you probably didn't know these)
- `3. Dedicated Intel & Notes Terminal (`intel_notes`)` --references--> `intel_notes()`  [INFERRED]
  .agents/rules/file_exploration.md → actions/intel_notes.py
- `🛡️ 2. Security, Privacy & Defensive Architecture` --references--> `computer_control()`  [INFERRED]
  readme.md → actions/computer_control.py
- `Steps` --references--> `daily_brief()`  [INFERRED]
  .agents/workflows/daily_brief.md → actions/daily_brief.py
- `1. File Opening (`open`)` --references--> `file_controller()`  [INFERRED]
  .agents/rules/file_exploration.md → actions/file_controller.py
- `2. Folder Exploration (`explore`)` --references--> `file_controller()`  [INFERRED]
  .agents/rules/file_exploration.md → actions/file_controller.py

## Import Cycles
- None detected.

## Communities (116 total, 24 thin omitted)

### Community 0 - "game_updater.py"
Cohesion: 0.06
Nodes (78): _build_google_flights_url(), flight_finder(), _format_spoken(), _format_text_report(), _get_base_dir(), _parse_date(), _parse_flights_with_gemini(), Path (+70 more)

### Community 1 - "cache.py"
Cohesion: 0.16
Nodes (12): _get_live_weather(), Fetch live weather conditions without opening an external browser., get_cache(), core/cache.py — Centralized Caching Layer for ALFRED Mark-II. Provides high-…, Returns the centralized cache client singleton., functools, hashlib, patch (+4 more)

### Community 3 - "TronScoreBackgroundPlayer"
Cohesion: 0.11
Nodes (7): QObject, _base_dir(), Path, Background music audio engine. Plays background score continuously on loop…, Set base normal volume (0.0 to 1.0). Speech ducking scales to 50% of base., Duck to 50% of base volume when speaking, restore to base volume when…, TronScoreBackgroundPlayer

### Community 4 - "file_controller.py"
Cohesion: 0.09
Nodes (53): copy_file(), create_file(), create_folder(), delete_file(), explore_folder(), file_controller(), find_files(), _format_size() (+45 more)

### Community 5 - "KokoroTTSEngine"
Cohesion: 0.06
Nodes (22): _compress_silence(), create_tts_player(), EdgeTTSEngine, ElevenLabsTTSEngine, _import_kokoro_pipeline(), KokoroTTSEngine, _synth(), _play_audio_bytes() (+14 more)

### Community 6 - "HoloAvatar"
Cohesion: 0.11
Nodes (19): _blend(), _c(), HoloAvatar, QColor, QPainter, _rate(), `col` at alpha `a` pre-mixed onto `bg`, returned fully **opaque**. Qt's raster…, Animated holographic head. One instance per HUD canvas. Lifecycle: av =… (+11 more)

### Community 7 - "MainWindow"
Cohesion: 0.06
Nodes (8): QMainWindow, MainWindow, Slot — display camera preview overlay (main thread)., Slot — runs on Qt main thread. Updates and shows the content panel., Slot — Qt main thread. Lays a document review into the content panel., Slot — Qt main thread. Puts a fresh quiz on the board., Returns True if auto-start is currently registered on this OS., Place a floating overlay in the middle of the HUD and show it.

### Community 8 - "TacticalAudioPlayerWidget"
Cohesion: 0.16
Nodes (4): _EqualizerBarsWidget, Mini animated cyber audio wave visualizer., Bottom-Left Cyber Tactical Audio Player Widget. Styled matching the HUD /…, TacticalAudioPlayerWidget

### Community 9 - "gemini.py"
Cohesion: 0.07
Nodes (42): _ask_gemini_for_desktop_action(), _build_sandbox(), clean_desktop(), desktop_control(), _execute_generated_code(), _get_api_key(), _get_base_dir(), get_current_wallpaper() (+34 more)

### Community 10 - ".__init__"
Cohesion: 0.11
Nodes (5): QDragEnterEvent, QDropEvent, CyberGraphicLineButton, FileDropZone, Tactical button rendered strictly with vector graphic lines, sharp 2px border…

### Community 11 - "llm_client.py"
Cohesion: 0.13
Nodes (23): call_llm(), call_llm_stream(), _do_stream(), call_llm_text(), check_model_available(), ensure_ollama_running(), get_base_dir(), get_llm_provider() (+15 more)

### Community 12 - "code_helper.py"
Cohesion: 0.18
Nodes (25): _build(), _clean_code(), code_helper(), _detect_intent(), _edit_action(), _explain_action(), _fix_code(), _get_gemini() (+17 more)

### Community 13 - "ui.py"
Cohesion: 0.20
Nodes (10): Holographic AI head for the HUD centre — the thing that used to be a ring stack…, math, get_brief_enabled(), save_brief_enabled(), pyqt6_qtcore, pyqt6_qtgui, pyqt6_qtmultimedia, pyqt6_qtwidgets (+2 more)

### Community 14 - "memory_manager.py"
Cohesion: 0.17
Nodes (17): Update Daily Briefing Preferences Action for ALFRED Mark-LIV. Permanently…, Permanently saves daily briefing preferences into long-term memory., update_daily_briefing(), _empty_memory(), forget(), get_base_dir(), load_memory(), pop_last_session() (+9 more)

### Community 16 - "computer_control.py"
Cohesion: 0.14
Nodes (30): _base_dir(), _clear_field(), _click(), _clipboard_get(), _clipboard_paste(), computer_control(), _drag(), _focus_window() (+22 more)

### Community 17 - "dev_agent.py"
Cohesion: 0.09
Nodes (38): apply_heal_patch(), _build_project(), _classify_error(), dev_agent(), _diagnose_trace(), _extract_culprit_script(), _fix_files(), _get_model() (+30 more)

### Community 18 - "file_processor.py"
Cohesion: 0.08
Nodes (45): _detect_type(), file_processor(), _file_size_str(), _gemini_client(), _output_path(), _process_archive(), _process_audio(), _process_code() (+37 more)

### Community 19 - "mono_font"
Cohesion: 0.07
Nodes (18): QFont, QWidget, BiometricFingerprintWidget, _CameraPreview, CRTReconWidget, _fl(), MetricBar, mono_font() (+10 more)

### Community 20 - "EchoGuard"
Cohesion: 0.08
Nodes (14): band_energies(), EchoGuard, ndarray, Classifies microphone blocks while the assistant is speaking. Usage:…, True once the estimate rests on enough real echo to be trusted., Residual left by this room's own echo. Higher = harder to separate., False when the acoustics are too poor to judge on content alone. Speakers…, The residual a block must clear right now to count as a voice. (+6 more)

### Community 21 - "JarvisUI"
Cohesion: 0.05
Nodes (18): JarvisUI, Update application and window icon in realtime., Thread-safe: raise the irreversible-action gate. Called from action handlers…, Thread-safe: take the gate down., Thread-safe: feed a 0.0–1.0 live audio level to the HUD waveform. Called from…, Ask the avatar to look somewhere for a moment (see HoloAvatar.glance)., Thread-safe: post a schedule of (level, openness, width) mouth frames for…, Thread-safe: wipe the on-screen conversation chat feed. (+10 more)

### Community 22 - "🦇 ALFRED — MARK III (Wayne Protocol Edition)"
Cohesion: 0.08
Nodes (24): ⚡ 10. Quick Start & Installation, 🔧 11. Configuration Reference (`config/api_keys.json`), 📊 12. Knowledge Graph (`graphify`), 👤 13. Author & Credits, 🖥️ 1. 100% Local & Air-Gapped Offline Execution, 1. Prerequisites, 2. Setup & Execution, 🎙️ 3. Real-Time Multimodal Intelligence & Dual Audio Engine (+16 more)

### Community 23 - ".__init__"
Cohesion: 0.12
Nodes (9): ProactiveEngine, Decides when ALFRED should speak unprompted and builds a context-rich prompt.…, _Popen, Exception, Raised inside the session TaskGroup to force a clean, voluntary reconnect (e.g.…, Session-scoped task: when a voluntary reconnect is requested, raise a signal…, Turn hold-to-talk on or off. Returns the scope actually achieved., _ReconnectSignal (+1 more)

### Community 24 - "JarvisLive"
Cohesion: 0.09
Nodes (11): JarvisLive, Called from the detector thread when 'Hey Jarvis' is heard., Auto-sleep after the configured silence window (wake-word mode only)., Enable/disable wake word from the settings UI. Returns a status token:…, Manual sleep/wake button in the UI., Download openwakeword + the model (runs in a UI worker thread)., Called from Qt main thread when user presses Remote Control., Called when user clicks the CLEAR button in desktop GUI. (+3 more)

### Community 25 - "is_heavenly_restricted"
Cohesion: 0.11
Nodes (21): _normalize(), open_app(), _is_heavenly_restricted_params(), check_action_params(), check_path_access(), get_allowed_c_roots(), is_heavenly_restricted(), is_safe_path() (+13 more)

### Community 27 - "config_manager.py"
Cohesion: 0.14
Nodes (21): ensure_config_dir(), get_base_dir(), get_gemini_key(), is_configured(), Path, Read-modify-write one key without disturbing the rest of the config., Merge `values` into a namespace's stored config (read-modify-write, like every…, Persist assistant name and user name to config. (+13 more)

### Community 28 - "._apply_ptt_shortcut"
Cohesion: 0.14
Nodes (8): chord_label(), qt_sequence(), Human-readable name of the chord, for the UI and the logs., The same chord as a QKeySequence string., _press(), Repaint the push-to-talk row from the saved setting., Bind the chord inside the window when no global hook is available. On macOS and…, Report a windowed press/release to whoever owns the microphone.

### Community 29 - "send_message.py"
Cohesion: 0.23
Nodes (20): _base_dir(), _clear_and_paste(), _desktop_send(), _get_os(), _open_app(), _open_browser_url(), _paste_text(), Path (+12 more)

### Community 30 - "confirm.py"
Cohesion: 0.25
Nodes (10): bind(), _log(), _Pending, core/confirm.py — a confirmation the model cannot forge. THE PROBLEM WITH THE…, Called by the UI when the user presses CONFIRM or CANCEL. Runs the stored…, Wire this module to the HUD. Called once from main.py at startup., Park an irreversible action behind the on-screen gate. Returns the sentence the…, request() (+2 more)

### Community 31 - "server.py"
Cohesion: 0.12
Nodes (13): base64, _derive_key(), _make_uploads_dir(), Path, dashboard/server.py — ALFRED Local HTTP Dashboard Plain HTTP on port 8000 (no…, Return (and create) the cross-platform uploads folder., SHA-256(sessionKey‖salt) → 32-byte AES-256 key (microseconds, no PBKDF2 needed)., fastapi (+5 more)

### Community 32 - "background_monitor.py"
Cohesion: 0.23
Nodes (13): add_monitor(), check_all(), _is_blocked(), list_monitors(), _load(), BackgroundMonitor — user-configured topic watching. Checks DDG news once per…, Run all pending topic checks (once per day per topic). Returns a list of…, remove_monitor() (+5 more)

### Community 33 - "HudCanvas"
Cohesion: 0.09
Nodes (15): HudCanvas, QPainter, Thread-safe entry point for the audio threads. Stores the louder of the…, True only when this canvas can actually be seen by the user., Draw the Avengers: Endgame Stark Arc Reactor at (cx, cy) with outer radius r., Draw subtle background CRT coordinate grid with + crosshairs (Screenshot 2)., 3D Rotating Vector Wireframe Globe (Matching Screenshot 2: WAKU CRT Globe).…, Futuristic Oscilloscope Waveforms spanning across the globe (Screenshot 1 & 2… (+7 more)

### Community 34 - "computer_settings"
Cohesion: 0.12
Nodes (16): brightness_get(), brightness_set(), computer_settings(), dark_mode(), press_key(), Current brightness 0-100, or None where it cannot be read., Set brightness to an absolute percentage. Only used to restore a value captured…, Current master volume 0-100, or None if this platform will not say. Undo needs… (+8 more)

### Community 35 - "TestCentralizedCache"
Cohesion: 0.12
Nodes (8): Verifies that cache errors do not crash callers., Verifies that key generation is deterministic across varying argument orders., Tests basic cache-aside hit and miss lifecycle., Verifies that entries expire after their TTL has elapsed., Tests prefix-based bulk invalidation for mutation hooks., Verifies that exceeding max_entries triggers eviction without unbounded growth., Tests @cached decorator with automatic cache-aside resolution., TestCentralizedCache

### Community 36 - "avatar_mesh.py"
Cohesion: 0.07
Nodes (34): collections, _add_cowl_ears(), _add_cranium(), _add_neck(), _boundary_loop(), build_head(), _check_landmarks(), get_head_mesh() (+26 more)

### Community 37 - "system_monitor.py"
Cohesion: 0.20
Nodes (10): _get_cpu_temp(), _get_gpu_usage(), get_system_status(), _nvml_gpu(), System Monitor — background metric checks with voice alert support. Zero…, Snapshot of current system metrics for the system_status tool., Stateful monitor — cooldown state persists across session reconnections. Call…, GPU utilisation via NVML — zero subprocess on all platforms. (+2 more)

### Community 38 - "action_loader.py"
Cohesion: 0.11
Nodes (17): ActionRecord, ActionRegistry, _call_handler(), discover_actions(), _opt_upper(), Path, Action discovery, validation, and dispatch — the built-in twin of…, Invoke the handler passing only the context kwargs it actually declares (or all… (+9 more)

### Community 39 - "pathlib"
Cohesion: 0.11
Nodes (23): _available(), install_for_config(), _pip(), MARK XL — Dependency auto-installer. Called automatically on first launch and…, Return True if the module can be imported (no actual import)., Install all missing packages required by *config*. Blocking — always call from…, install_and_download(), is_installed() (+15 more)

### Community 40 - "CentralizedCache"
Cohesion: 0.12
Nodes (14): CentralizedCache, _canonicalize(), decorator(), wrapper(), Any, Stores value in cache with TTL. Fails open gracefully if storage fails., Deletes a key from cache. Fails open gracefully., Invalidates all keys starting with prefix. Useful for mutation hooks. (+6 more)

### Community 41 - "_SessionRegistry"
Cohesion: 0.15
Nodes (5): _detect_default_browser(), Manages all active browser sessions., Is there an active automation session for this browser (or any)?, Returns the last natively-opened URL once (consumed to avoid repeats)., _SessionRegistry

### Community 42 - "web_search.py"
Cohesion: 0.11
Nodes (33): _compare(), _ddg_news(), _ddg_search(), _format_ddg(), _format_news(), _gemini_available(), _gemini_search(), _get_base_dir() (+25 more)

### Community 43 - "RemoteKeyOverlay"
Cohesion: 0.27
Nodes (4): Floating overlay — QR code for instant phone pairing + manual key fallback., Call from any thread when a phone successfully connects., RemoteKeyOverlay, _lbl()

### Community 44 - "qcol"
Cohesion: 0.16
Nodes (7): QPixmap, _DropCanvas, _file_category(), _fmt_size(), QColor, qcol(), Pre-render the static grid-dot background into a transparent pixmap so…

### Community 45 - ".run"
Cohesion: 0.16
Nodes (9): BaseException, _get_api_key(), _is_reconnect_signal(), _keep_context_of(), Background task: voice alerts when metrics exceed thresholds., Check user-configured topics once per day; speak alerts when new headlines…, Forward phone mic PCM chunks from dashboard queue into the Gemini Live session., True if `exc` is a _ReconnectSignal, or a(n) (Base)ExceptionGroup that wraps… (+1 more)

### Community 46 - "._build_app"
Cohesion: 0.20
Nodes (11): _auth(), auto_login(), clear_chat_ep(), device_login_ep(), list_files(), login(), phone_audio_ws(), revoke_devices() (+3 more)

### Community 47 - "save_app_icon"
Cohesion: 0.20
Nodes (10): Update App Icon Action for ALFRED Mark-LIV. Switches the application window,…, Updates the main application icon and taskbar badge in realtime., update_app_icon(), Save the chosen app icon setting to config., save_app_icon(), format_icon_display_name(), get_available_app_icons(), Format an icon file name into an authentic, sleek tactical insignia title. (+2 more)

### Community 48 - "_SysMetrics"
Cohesion: 0.21
Nodes (4): Thread-safe speech channel for plugins: lets a plugin ask JARVIS to say…, _nvml_gpu_windows(), Return NVIDIA GPU utilisation % using nvml.dll directly — zero subprocess., _SysMetrics

### Community 49 - "load_api_keys"
Cohesion: 0.10
Nodes (18): The optional knobs, kept apart so one bad field can be dropped wholesale. Every…, get_app_icon(), get_assistant_name(), get_hud_style(), get_media_resolution(), get_push_to_talk_enabled(), get_thinking_enabled(), get_turn_tuning() (+10 more)

### Community 51 - "screen_processor.py"
Cohesion: 0.05
Nodes (49): _base_dir(), _capture_camera(), capture_screen(), _capture_screen(), _compress(), _cv2_backend(), _detect_camera_index(), format_visual_payload() (+41 more)

### Community 52 - "DashboardServer"
Cohesion: 0.23
Nodes (3): DashboardServer, URL for manual browser entry. When HTTPS active, points to alias port (also…, Second HTTPS server on PORT+1 sharing the same app and in-memory state. Chrome…

### Community 53 - "browser_control.py"
Cohesion: 0.24
Nodes (11): browser_control(), _find_exe_windows(), _find_opera_windows(), _log(), _normalize_url(), _open_native(), Bare words like "instagram" → "https://instagram.com" Domains like…, Opens the user's REAL browser normally — with their own profile, logged-in… (+3 more)

### Community 54 - "PushToTalk"
Cohesion: 0.20
Nodes (5): PushToTalk, Begin watching. Returns the scope actually achieved., Feed a press/release from a Qt shortcut (non-Windows, or no hook)., Calls `on_change(held: bool)` whenever the chord is pressed or released. Start…, global' once a system-wide hook is running, else 'window'.

### Community 55 - "format_memory_for_prompt"
Cohesion: 0.22
Nodes (10): Build a context snapshot for Gemini. Rotates through three focus areas so…, _entry_value(), format_memory_for_prompt(), _pretty(), Accept both the {'value': ..., 'updated': ...} shape and a bare string, because…, Build the memory block that goes into the system prompt. This used to dump…, Cheap lexical relevance. No embeddings, no network, no model call - this runs…, Find stored facts matching `query`. Backs the recall_memory tool. An empty… (+2 more)

### Community 57 - "gmail_manager.py"
Cohesion: 0.12
Nodes (21): _clean_header_str(), _extract_body_snippet(), fetch_unread_emails(), gmail_manager(), _load_gmail_creds(), Any, Gmail Manager Action for ALFRED Mark-LIV. Provides full Gmail connectivity: -…, Send an email using Gmail SMTP SSL. (+13 more)

### Community 58 - "CustomizeOverlay"
Cohesion: 0.10
Nodes (9): QPointF, QRectF, CustomizeOverlay, _lbl(), HueWheel, Circular colour picker. The user drags the handle (small white circle) around…, Floating glassmorphic overlay for configuring Assistant Persona, Commander…, Highlight the selected voice pill; dim the rest. (+1 more)

### Community 59 - "._build_right_panel"
Cohesion: 0.18
Nodes (3): QHBoxLayout, Read api_keys.json config dict. Returns {} on any error., _read_full_config()

### Community 60 - "main.py"
Cohesion: 0.05
Nodes (43): ProactiveEngine 2.0 — context-aware, time-aware, non-repetitive background…, asyncio, configure(), _display_name(), _is_pseudo(), prefetch(), _work(), _query() (+35 more)

### Community 61 - "._play_audio"
Cohesion: 0.25
Nodes (5): _pcm_level(), _pcm_visemes(), Map a block of int16 PCM samples to a 0.0–1.0 loudness level for the HUD…, Slice a PCM block into (level, openness, width) frames, one per 20 ms. Returns…, Stop JARVIS mid-speech: drain queued audio and open mic immediately.

### Community 62 - "MemoryOverlay"
Cohesion: 0.25
Nodes (6): all_entries_for_ui(), Flat list for the memory panel: what ALFRED knows, and when it learned it.…, MemoryOverlay, Everything ALFRED has stored about you, and when it learned it. Memory used to…, Take every item out of the layout and detach it from the widget tree in this…, Size the panel to its content, re-centre it, and repaint what the old size…

### Community 65 - "._launch"
Cohesion: 0.29
Nodes (5): _firefox_profile_dir(), launch_persistent_context already opens a starting tab. Instead of opening a…, Launches the browser with the real user profile. Does nothing if the context is…, _real_profile_dir(), Page

### Community 68 - "weather_report.py"
Cohesion: 0.50
Nodes (4): _log(), weather_action(), urllib_parse, webbrowser

### Community 70 - "_detect_action"
Cohesion: 0.40
Nodes (5): _detect_action(), _normalise(), Resolve a free-text description to an action name, locally. Returns {"action":…, What to tell the model when nothing matched. Names real actions so its retry…, _suggest()

### Community 71 - "._apply_name_update"
Cohesion: 0.20
Nodes (8): apply_ui_accent(), current_palette(), Applies DOSSIER CRT [A-34] (#8e9bff), VECTOR CRT [WAKU] (#a8ff3e), or BATMAN…, A snapshot of the accent-linked colours currently on class C., LIVE full theme change. Replaces the old palette colours with the new ones in…, Live preview — paints the whole interface the new colour (does NOT write to…, Update all name/theme-dependent UI elements and persist to config., retheme_all_widgets()

### Community 72 - "WhisperSTT"
Cohesion: 0.33
Nodes (4): ndarray, Offline transcription using faster-whisper., Transcribe a float32 mono 16 kHz numpy array. Returns transcript string., WhisperSTT

### Community 73 - "daily_brief.py"
Cohesion: 0.18
Nodes (14): daily_brief(), _get_gmail_brief(), _get_greeting(), _get_reminders_brief(), _get_system_vitals(), Daily Brief Action for ALFRED Mark-LIV. Provides the ultimate morning and daily…, Fetch unread emails summary via gmail_manager., Check scheduled reminders in ~/.alfred/reminders or ~/.jarvis/reminders. (+6 more)

### Community 74 - "WakeWordDetector"
Cohesion: 0.17
Nodes (5): Runs the wake model in a dedicated thread. The mic thread calls feed() with raw…, Load the model and spawn the inference thread. Returns True on success. Safe to…, Called from the mic callback (real-time thread). Must stay cheap and never…, WakeWordDetector, Load the detector once (model loads on first start). Idempotent.

### Community 75 - "tech_font"
Cohesion: 0.11
Nodes (11): QPushButton, QVBoxLayout, CapabilitiesOverlay, ConfirmBanner, PluginManagerOverlay, PluginSettingsOverlay, Floating glassmorphic overlay displaying a categorized directory of everything…, Floating overlay — lists discovered plugins with per-plugin ON/OFF toggles. (+3 more)

### Community 76 - "datetime"
Cohesion: 0.41
Nodes (11): _base_dir(), _get_os(), Path, reminder(), _sanitise(), _schedule_linux(), _schedule_mac(), _schedule_windows() (+3 more)

### Community 77 - "get_input_device"
Cohesion: 0.15
Nodes (13): list_devices(), Device names for 'input' or 'output'. Falls back to a synchronous query if the…, get_input_device(), get_output_device(), _patch_config(), Read-modify-write one or more keys in api_keys.json. Every setter in this file…, Microphone device name, or '' for the system default., Speaker device name, or '' for the system default. (+5 more)

### Community 78 - "_trim_to_limit"
Cohesion: 0.24
Nodes (7): _all_entries(), _trim_to_limit(), Performance Benchmark: memory_manager._trim_to_limit Tests execution time and…, Measures execution time for 50,000 mock records. Under the old O(N^2)…, Preserves all items when memory is already below limit., Handles empty memory structure gracefully., TestMemoryTrimBenchmark

### Community 79 - "_template.py"
Cohesion: 0.50
Nodes (3): Drop-in ALFRED plugin template. Copy this file, rename it (no leading…, parameters: dict of the args Gemini extracted, matching PLUGIN['parameters'].…, run()

### Community 80 - "_get_base_dir"
Cohesion: 0.67
Nodes (3): _get_api_key(), _get_base_dir(), Path

### Community 81 - "LogWidget"
Cohesion: 0.25
Nodes (3): QTextEdit, LogWidget, Cancel any in-flight typing animation, drain the queue, and clear the display.

### Community 82 - "_tlog"
Cohesion: 0.14
Nodes (10): _clean_transcript(), _is_repeat_chunk(), _deliver_news(), main(), runner(), Format terminal log report without emojis using red bracketed tags, and…, Send a captured frame immediately after its tool response. The frame is already…, Two-phase briefing optimized for speed: Phase 1 — instant greeting (no tools) →… (+2 more)

### Community 85 - ".__init__"
Cohesion: 0.29
Nodes (6): index(), _ensure_certs(), _local_ip(), Return the best LAN-facing IPv4 address, no internet required., Make sure config/certs holds a TLS key pair, generating a self-signed one the…, _read()

### Community 86 - "get_plugin_config"
Cohesion: 0.50
Nodes (4): get_plugin_config(), get_plugin_setting(), All stored values for a namespace (empty dict if none set yet)., A single value from a namespace, or `default` if unset.

### Community 87 - "._build_jarvis_icon"
Cohesion: 0.22
Nodes (4): Render an ALFRED tactical icon at 4× resolution and downsample for crisp…, Create a Windows .lnk shortcut WITHOUT launching PowerShell or cmd. Tries…, Resolve the user's REAL desktop directory instead of assuming ~/Desktop, which…, Create a desktop shortcut on Windows / macOS / Linux. Never opens a terminal,…

### Community 89 - "json"
Cohesion: 0.25
Nodes (5): Speech-to-Text engines for MARK XL. Whisper – offline transcription via faster-…, Streaming transcription using Vosk., Feed raw int16 LE PCM bytes. Returns (text, is_final)., VoskSTT, json

### Community 93 - "._build_config"
Cohesion: 0.15
Nodes (12): LiveConnectConfig, _describe_limits(), _describe_tools(), _load_system_prompt(), One line per capability, straight from the live tool declarations. Derived…, The other half of self-knowledge: what is out of reach, and why. Derived from…, Fill {tokens} in the prompt template. A plain replace rather than str.format:…, _render_prompt() (+4 more)

### Community 94 - "Daily Brief Protocol"
Cohesion: 0.50
Nodes (3): Daily Brief Protocol, Purpose, Rules

### Community 95 - "Email Handling Rules"
Cohesion: 0.50
Nodes (3): Email Handling Rules, Purpose, Rules

### Community 96 - "Executive Assistant Persona & Behavioral Standards"
Cohesion: 0.50
Nodes (3): Core Operational Rules, Executive Assistant Persona & Behavioral Standards, Persona & Demeanor

### Community 98 - "/email-triage Workflow"
Cohesion: 0.50
Nodes (3): /email-triage Workflow, Objective, Steps

### Community 99 - "get_plugin_enabled"
Cohesion: 0.11
Nodes (17): _call_run(), discover_plugins(), _load_error(), _opt_upper(), PluginRecord, PluginRegistry, Exception, Path (+9 more)

### Community 101 - "intel_notes.py"
Cohesion: 0.31
Nodes (8): _auto_detect_type(), _config_dir(), intel_notes(), _load_notes(), Path, actions/intel_notes.py — Dedicated Intel & Notes Terminal Action. Provides a…, Action handler called by Gemini / action_loader., _save_notes()

### Community 103 - "_VolumeSliderPopup"
Cohesion: 0.33
Nodes (3): QFrame, Sleek tactical cyber popup for adjusting master background music volume.…, _VolumeSliderPopup

### Community 104 - ".request_reconnect"
Cohesion: 0.33
Nodes (3): Thread-safe: ask the run loop to tear down and rebuild the Live session. Called…, Voice picker applied. The voice is baked into the session at connect time, so a…, Microphone or speaker changed. Both streams are opened inside the session…

### Community 107 - "calendar_sync.py"
Cohesion: 0.47
Nodes (5): _load_events(), Calendar Sync Plugin for ALFRED Mark-LIV. Tracks agenda, meetings,…, Execute calendar action., run(), _save_events()

### Community 109 - "focus_protocol.py"
Cohesion: 0.47
Nodes (5): Focus Protocol Plugin for ALFRED Mark-LIV. Manages deep work intervals,…, Execute focus protocol actions., _read_state(), run(), _write_state()

### Community 110 - "._decrypt"
Cohesion: 0.40
Nodes (4): command(), ws_ep(), _decrypt_cbc(), Decrypt base64(IV[16] ‖ ciphertext) with AES-256-CBC + PKCS7.

### Community 111 - "._save_session_summary"
Cohesion: 0.40
Nodes (4): _do_shutdown(), Summarise the current session in 1-2 sentences and save to long_term.json., Append a 1-2 sentence session summary to long_term.json['sessions']., save_session_summary()

### Community 112 - "._listen_audio"
Cohesion: 0.50
Nodes (3): callback(), _open_mic(), True while the speakers may still be finishing our last sentence.

### Community 115 - "Steps"
Cohesion: 0.50
Nodes (3): /daily-brief Workflow, Objective, Steps

## Knowledge Gaps
- **34 isolated node(s):** `C`, `Purpose`, `Rules`, `Purpose`, `Rules` (+29 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 808 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **24 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `JarvisUI` connect `JarvisUI` to `.clear_chat`, `._apply_name_update`, `.__init__`, `ui.py`, `._apply_ptt_shortcut`, `_tlog`, `._wake_state`, `.__init__`, `JarvisLive`, `setter`, `main.py`?**
  _High betweenness centrality (0.066) - this node is a cross-community bridge._
- **Why does `MainWindow` connect `MainWindow` to `.clear_chat`, `._apply_name_update`, `.__init__`, `tech_font`, `_HudOverlay`, `ui.py`, `qcol`, `get_input_device`, `save_app_icon`, `.resizeEvent`, `mono_font`, `._wake_state`, `._build_jarvis_icon`, `setter`, `._build_right_panel`, `._apply_ptt_shortcut`?**
  _High betweenness centrality (0.066) - this node is a cross-community bridge._
- **Why does `JarvisLive` connect `JarvisLive` to `EchoGuard`, `JarvisUI`, `.__init__`, `background_monitor.py`, `avatar_mesh.py`, `system_monitor.py`, `.run`, `_SysMetrics`, `load_api_keys`, `DashboardServer`, `PushToTalk`, `main.py`, `._play_audio`, `WakeWordDetector`, `_tlog`, `._build_config`, `.request_reconnect`, `._save_session_summary`, `._listen_audio`?**
  _High betweenness centrality (0.054) - this node is a cross-community bridge._
- **Are the 8 inferred relationships involving `JarvisLive` (e.g. with `ProactiveEngine` and `SystemMonitor`) actually correct?**
  _`JarvisLive` has 8 INFERRED edges - model-reasoned connections that need verification._
- **What connects `C`, `Purpose`, `Rules` to the rest of the system?**
  _34 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `game_updater.py` be split into smaller, more focused modules?**
  _Cohesion score 0.06190476190476191 - nodes in this community are weakly interconnected._
- **Should `computer_settings.py` be split into smaller, more focused modules?**
  _Cohesion score 0.04081632653061224 - nodes in this community are weakly interconnected._