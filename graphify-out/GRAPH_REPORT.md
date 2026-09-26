# Graph Report - Alfred-Mark-III  (2026-09-26)

## Corpus Check
- 80 files · ~170,859 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 13 file(s) not represented in the graph (top: .ico 7, (none) 3, .obj 2)

## Summary
- 2027 nodes · 3978 edges · 111 communities (77 shown, 34 thin omitted)
- Extraction: 96% EXTRACTED · 4% INFERRED · 0% AMBIGUOUS · INFERRED: 165 edges (avg confidence: 0.86)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `a21f9732`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- game_updater.py
- code_helper.py
- MainWindow
- file_processor.py
- file_controller.py
- TronScoreBackgroundPlayer
- CustomizeOverlay
- computer_settings.py
- avatar_mesh.py
- qcol
- tts.py
- CentralizedCache
- web_search.py
- mono_font
- datetime
- HoloAvatar
- JarvisLive
- _BrowserSession
- computer_control.py
- dev_agent.py
- main.py
- memory_manager.py
- llm_client.py
- EchoGuard
- 🦇 ALFRED — MARK II (Wayne Protocol Edition)
- JarvisUI
- config_manager.py
- tech_font
- RemoteKeyOverlay
- ActionRegistry
- audio_devices.py
- crypto-js.min.js
- screen_processor.py
- send_message.py
- _tlog
- PushToTalk
- .__init__
- json
- intel_notes.py
- get_plugin_enabled
- ._build_app
- ._execute_tool
- load_api_keys
- VoskSTT
- desktop.py
- MemoryOverlay
- background_monitor.py
- computer_settings
- server.py
- ClipboardPanel
- get_plugin_config
- SystemMonitor
- get_input_device
- .add_intel_note
- .run
- setter
- .hide_confirm
- .prompt_reconfig
- ui.py
- WhisperSTT
- NotesTerminalWidget
- ProactiveEngine
- save_app_icon
- .set_app_icon
- undo.py
- DashboardServer
- ._build_config
- _SysMetrics
- ._apply_name_update
- confirm.py
- .set_audio_level
- WakeWordDetector
- get_push_to_talk_enabled
- .show_review
- PluginManagerOverlay
- ._wake_state
- ._play_audio
- LogWidget
- ._apply_ptt_shortcut
- .__init__
- _ensure_network_access
- .request_reconnect
- .__init__
- SetupOverlay
- SubjectDossierCard
- _detect_action
- _RootShim
- .clear_chat
- Daily Brief Protocol
- Email Handling Rules
- Executive Assistant Persona & Behavioral Standards
- /email-triage Workflow
- _template.py
- _get_base_dir
- Graphify + Antigravity Project Workflow & Setup Guide
- .glance
- _get_macos_wifi_interface
- type_text
- rules/graphify.md
- workflows/graphify.md
- .clear_intel_notes
- .hide_quiz
- .show_content
- .show_quiz
- .start_camera_stream
- pil

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
- `Steps` --references--> `daily_brief()`  [INFERRED]
  .agents/workflows/daily_brief.md → actions/daily_brief.py
- `1. File Opening (`open`)` --references--> `file_controller()`  [INFERRED]
  .agents/rules/file_exploration.md → actions/file_controller.py
- `2. Folder Exploration (`explore`)` --references--> `file_controller()`  [INFERRED]
  .agents/rules/file_exploration.md → actions/file_controller.py
- `Step 1: Target Identification` --references--> `file_controller()`  [INFERRED]
  .agents/workflows/file_explorer.md → actions/file_controller.py

## Import Cycles
- None detected.

## Communities (111 total, 34 thin omitted)

### Community 0 - "game_updater.py"
Cohesion: 0.06
Nodes (82): _build_google_flights_url(), flight_finder(), _format_spoken(), _format_text_report(), _get_base_dir(), _parse_date(), _parse_flights_with_gemini(), Path (+74 more)

### Community 1 - "code_helper.py"
Cohesion: 0.07
Nodes (51): _build(), _clean_code(), code_helper(), _detect_intent(), _edit_action(), _explain_action(), _fix_code(), _get_gemini() (+43 more)

### Community 2 - "MainWindow"
Cohesion: 0.05
Nodes (10): QMainWindow, MainWindow, Read api_keys.json config dict. Returns {} on any error., Slot — display camera preview overlay (main thread)., Slot — runs on Qt main thread. Updates and shows the content panel., Slot — Qt main thread. Lays a document review into the content panel., Slot — Qt main thread. Puts a fresh quiz on the board., Returns True if auto-start is currently registered on this OS. (+2 more)

### Community 3 - "file_processor.py"
Cohesion: 0.08
Nodes (45): _detect_type(), file_processor(), _file_size_str(), _gemini_client(), _output_path(), _process_archive(), _process_audio(), _process_code() (+37 more)

### Community 4 - "file_controller.py"
Cohesion: 0.09
Nodes (53): copy_file(), create_file(), create_folder(), delete_file(), explore_folder(), file_controller(), find_files(), _format_size() (+45 more)

### Community 5 - "TronScoreBackgroundPlayer"
Cohesion: 0.05
Nodes (16): QFrame, QObject, _base_dir(), Path, Background music audio engine. Plays background score continuously on loop…, Set base normal volume (0.0 to 1.0). Speech ducking scales to 50% of base., Sleek tactical cyber popup for adjusting master background music volume.…, Bottom-Left Cyber Tactical Audio Player Widget. Styled matching the HUD /… (+8 more)

### Community 6 - "CustomizeOverlay"
Cohesion: 0.07
Nodes (11): QPointF, QRectF, CustomizeOverlay, _lbl(), CyberGraphicLineButton, HueWheel, Tactical button rendered strictly with vector graphic lines, sharp 2px border…, Circular colour picker. The user drags the handle (small white circle) around… (+3 more)

### Community 8 - "avatar_mesh.py"
Cohesion: 0.07
Nodes (34): collections, _add_cowl_ears(), _add_cranium(), _add_neck(), _boundary_loop(), build_head(), _check_landmarks(), get_head_mesh() (+26 more)

### Community 9 - "qcol"
Cohesion: 0.08
Nodes (19): QPixmap, HudCanvas, QColor, QPainter, qcol(), Thread-safe entry point for the audio threads. Stores the louder of the…, Pre-render the static grid-dot background into a transparent pixmap so…, True only when this canvas can actually be seen by the user. (+11 more)

### Community 10 - "tts.py"
Cohesion: 0.07
Nodes (26): asyncio, _compress_silence(), create_tts_player(), EdgeTTSEngine, ElevenLabsTTSEngine, _import_kokoro_pipeline(), KokoroTTSEngine, _synth() (+18 more)

### Community 11 - "CentralizedCache"
Cohesion: 0.06
Nodes (22): CentralizedCache, _canonicalize(), decorator(), wrapper(), Any, Stores value in cache with TTL. Fails open gracefully if storage fails., Deletes a key from cache. Fails open gracefully., Invalidates all keys starting with prefix. Useful for mutation hooks. (+14 more)

### Community 12 - "web_search.py"
Cohesion: 0.11
Nodes (35): _compare(), _ddg_news(), _ddg_search(), _format_ddg(), _format_news(), _gemini_available(), _gemini_search(), _get_base_dir() (+27 more)

### Community 13 - "mono_font"
Cohesion: 0.07
Nodes (16): QFont, QWidget, BiometricFingerprintWidget, _CameraPreview, CRTReconWidget, _fl(), MetricBar, mono_font() (+8 more)

### Community 14 - "datetime"
Cohesion: 0.06
Nodes (45): _clean_header_str(), _extract_body_snippet(), fetch_unread_emails(), gmail_manager(), _load_gmail_creds(), Any, Gmail Manager Action for ALFRED Mark-LIV. Provides full Gmail connectivity: -…, Send an email using Gmail SMTP SSL. (+37 more)

### Community 15 - "HoloAvatar"
Cohesion: 0.11
Nodes (19): _blend(), _c(), HoloAvatar, QColor, QPainter, _rate(), `col` at alpha `a` pre-mixed onto `bg`, returned fully **opaque**. Qt's raster…, Animated holographic head. One instance per HUD canvas. Lifecycle: av =… (+11 more)

### Community 16 - "JarvisLive"
Cohesion: 0.09
Nodes (12): JarvisLive, Load the detector once (model loads on first start). Idempotent., Called from the detector thread when 'Hey Jarvis' is heard., Auto-sleep after the configured silence window (wake-word mode only)., Enable/disable wake word from the settings UI. Returns a status token:…, Manual sleep/wake button in the UI., Download openwakeword + the model (runs in a UI worker thread)., Called from Qt main thread when user presses Remote Control. (+4 more)

### Community 17 - "_BrowserSession"
Cohesion: 0.05
Nodes (23): browser_control(), _BrowserSession, _detect_default_browser(), _find_exe_windows(), _find_opera_windows(), _firefox_profile_dir(), _log(), _normalize_url() (+15 more)

### Community 18 - "computer_control.py"
Cohesion: 0.07
Nodes (48): _base_dir(), _clear_field(), _click(), _clipboard_get(), _clipboard_paste(), computer_control(), _drag(), _focus_window() (+40 more)

### Community 19 - "dev_agent.py"
Cohesion: 0.07
Nodes (47): apply_heal_patch(), _build_project(), _classify_error(), dev_agent(), _diagnose_trace(), _extract_culprit_script(), _fix_files(), _get_model() (+39 more)

### Community 20 - "main.py"
Cohesion: 0.09
Nodes (32): System Monitor — background metric checks with voice alert support. Zero…, Action discovery, validation, and dispatch — the built-in twin of…, Push-to-talk — hold a key, speak, release. Why this exists ---------------…, _available(), install_for_config(), _pip(), MARK XL — Dependency auto-installer. Called automatically on first launch and…, Return True if the module can be imported (no actual import). (+24 more)

### Community 21 - "memory_manager.py"
Cohesion: 0.08
Nodes (36): Update Daily Briefing Preferences Action for ALFRED Mark-LIV. Permanently…, Permanently saves daily briefing preferences into long-term memory., update_daily_briefing(), _all_entries(), all_entries_for_ui(), _empty_memory(), _entry_value(), forget() (+28 more)

### Community 22 - "llm_client.py"
Cohesion: 0.09
Nodes (26): Hybrid return payload for screen captures. - Behaves as a 3-tuple `(img_bytes,…, ScreenCapturePayload, call_llm(), call_llm_stream(), _do_stream(), call_llm_text(), check_model_available(), ensure_ollama_running() (+18 more)

### Community 23 - "EchoGuard"
Cohesion: 0.08
Nodes (14): band_energies(), EchoGuard, ndarray, Classifies microphone blocks while the assistant is speaking. Usage:…, True once the estimate rests on enough real echo to be trusted., Residual left by this room's own echo. Higher = harder to separate., False when the acoustics are too poor to judge on content alone. Speakers…, The residual a block must clear right now to count as a voice. (+6 more)

### Community 24 - "🦇 ALFRED — MARK II (Wayne Protocol Edition)"
Cohesion: 0.08
Nodes (25): ⚡ 10. Quick Start & Installation, 🔧 11. Configuration Reference (`config/api_keys.json`), 📊 12. Knowledge Graph (`graphify`), 🛠️ 13. Bug Fixes & System Patches, 👤 14. Author & Credits, 🖥️ 1. 100% Local & Air-Gapped Offline Execution, 1. Prerequisites, 2. Setup & Execution (+17 more)

### Community 25 - "JarvisUI"
Cohesion: 0.11
Nodes (7): main(), JarvisUI, Thread-safe: raise the irreversible-action gate. Called from action handlers…, Thread-safe: post a schedule of (level, openness, width) mouth frames for…, Thread-safe: wipe the on-screen conversation chat feed., Thread-safe: show a webcam frame in the small overlay (screen captures)., Thread-safe: stop the live camera feed.

### Community 26 - "config_manager.py"
Cohesion: 0.13
Nodes (22): ensure_config_dir(), get_base_dir(), get_gemini_key(), is_configured(), Path, Read-modify-write one key without disturbing the rest of the config., Merge `values` into a namespace's stored config (read-modify-write, like every…, Persist assistant name and user name to config. (+14 more)

### Community 27 - "tech_font"
Cohesion: 0.14
Nodes (7): QVBoxLayout, CapabilitiesOverlay, _DropCanvas, PluginSettingsOverlay, Floating glassmorphic overlay displaying a categorized directory of everything…, Floating overlay — renders per-plugin settings forms. Fully generic: it…, tech_font()

### Community 28 - "RemoteKeyOverlay"
Cohesion: 0.27
Nodes (4): Floating overlay — QR code for instant phone pairing + manual key fallback., Call from any thread when a phone successfully connects., RemoteKeyOverlay, _lbl()

### Community 29 - "ActionRegistry"
Cohesion: 0.13
Nodes (11): ActionRecord, ActionRegistry, _call_handler(), discover_actions(), _opt_upper(), Path, Invoke the handler passing only the context kwargs it actually declares (or all…, Returns an ActionRecord; .valid=False + .error set on any problem. Never raises. (+3 more)

### Community 30 - "audio_devices.py"
Cohesion: 0.12
Nodes (18): configure(), _display_name(), _is_pseudo(), prefetch(), _work(), _query(), _collect(), core/audio_devices.py — pick which microphone and which speakers ALFRED uses.… (+10 more)

### Community 32 - "screen_processor.py"
Cohesion: 0.06
Nodes (46): _base_dir(), _capture_camera(), capture_screen(), _capture_screen(), _compress(), _cv2_backend(), _detect_camera_index(), format_visual_payload() (+38 more)

### Community 33 - "send_message.py"
Cohesion: 0.23
Nodes (20): _base_dir(), _clear_and_paste(), _desktop_send(), _get_os(), _open_app(), _open_browser_url(), _paste_text(), Path (+12 more)

### Community 34 - "_tlog"
Cohesion: 0.12
Nodes (11): _clean_transcript(), _is_repeat_chunk(), _deliver_news(), runner(), Format terminal log report without emojis using red bracketed tags, and…, Send a captured frame immediately after its tool response. The frame is already…, Two-phase briefing optimized for speed: Phase 1 — instant greeting (no tools) →…, Check user-configured topics once per day; speak alerts when new headlines… (+3 more)

### Community 35 - "PushToTalk"
Cohesion: 0.20
Nodes (5): PushToTalk, Begin watching. Returns the scope actually achieved., Feed a press/release from a Qt shortcut (non-Windows, or no hook)., Calls `on_change(held: bool)` whenever the chord is pressed or released. Start…, global' once a system-wide hook is running, else 'window'.

### Community 36 - ".__init__"
Cohesion: 0.11
Nodes (5): QDragEnterEvent, QDropEvent, _EqualizerBarsWidget, FileDropZone, Mini animated cyber audio wave visualizer.

### Community 37 - "json"
Cohesion: 0.08
Nodes (29): daily_brief(), _get_gmail_brief(), _get_greeting(), _get_live_weather(), _get_reminders_brief(), _get_system_vitals(), Daily Brief Action for ALFRED Mark-LIV. Provides the ultimate morning and daily…, Fetch unread emails summary via gmail_manager. (+21 more)

### Community 38 - "intel_notes.py"
Cohesion: 0.31
Nodes (8): _auto_detect_type(), _config_dir(), intel_notes(), _load_notes(), Path, actions/intel_notes.py — Dedicated Intel & Notes Terminal Action. Provides a…, Action handler called by Gemini / action_loader., _save_notes()

### Community 39 - "get_plugin_enabled"
Cohesion: 0.11
Nodes (17): _call_run(), discover_plugins(), _load_error(), _opt_upper(), PluginRecord, PluginRegistry, Exception, Path (+9 more)

### Community 40 - "._build_app"
Cohesion: 0.17
Nodes (13): _auth(), auto_login(), clear_chat_ep(), command(), device_login_ep(), list_files(), login(), phone_audio_ws() (+5 more)

### Community 41 - "._execute_tool"
Cohesion: 0.29
Nodes (3): FunctionResponse, _do_shutdown(), Summarise the current session in 1-2 sentences and save to long_term.json.

### Community 42 - "load_api_keys"
Cohesion: 0.10
Nodes (19): get_app_icon(), get_assistant_name(), get_hud_style(), get_media_resolution(), get_proactive_audio_enabled(), get_thinking_enabled(), get_turn_tuning(), get_user_name() (+11 more)

### Community 43 - "VoskSTT"
Cohesion: 0.40
Nodes (3): Streaming transcription using Vosk., Feed raw int16 LE PCM bytes. Returns (text, is_final)., VoskSTT

### Community 44 - "desktop.py"
Cohesion: 0.25
Nodes (16): _ask_gemini_for_desktop_action(), _build_sandbox(), clean_desktop(), desktop_control(), _execute_generated_code(), _get_api_key(), _get_base_dir(), get_current_wallpaper() (+8 more)

### Community 45 - "MemoryOverlay"
Cohesion: 0.15
Nodes (8): ConfirmBanner, _HudOverlay, MemoryOverlay, Base for the floating panels placed by hand over the HUD. They are children of…, The gate in front of an action that cannot be taken back. The old confirmation…, Everything ALFRED has stored about you, and when it learned it. Memory used to…, Take every item out of the layout and detach it from the widget tree in this…, Size the panel to its content, re-centre it, and repaint what the old size…

### Community 46 - "background_monitor.py"
Cohesion: 0.33
Nodes (11): add_monitor(), check_all(), _is_blocked(), list_monitors(), _load(), BackgroundMonitor — user-configured topic watching. Checks DDG news once per…, Run all pending topic checks (once per day per topic). Returns a list of…, remove_monitor() (+3 more)

### Community 47 - "computer_settings"
Cohesion: 0.12
Nodes (16): brightness_get(), brightness_set(), computer_settings(), dark_mode(), press_key(), Current brightness 0-100, or None where it cannot be read., Set brightness to an absolute percentage. Only used to restore a value captured…, Current master volume 0-100, or None if this platform will not say. Undo needs… (+8 more)

### Community 48 - "server.py"
Cohesion: 0.11
Nodes (15): _decrypt_cbc(), _derive_key(), _make_uploads_dir(), Path, dashboard/server.py — ALFRED Local HTTP Dashboard Plain HTTP on port 8000 (no…, Return (and create) the cross-platform uploads folder., SHA-256(sessionKey‖salt) → 32-byte AES-256 key (microseconds, no PBKDF2 needed)., Decrypt base64(IV[16] ‖ ciphertext) with AES-256-CBC + PKCS7. (+7 more)

### Community 50 - "get_plugin_config"
Cohesion: 0.50
Nodes (4): get_plugin_config(), get_plugin_setting(), All stored values for a namespace (empty dict if none set yet)., A single value from a namespace, or `default` if unset.

### Community 51 - "SystemMonitor"
Cohesion: 0.21
Nodes (8): _get_cpu_temp(), _get_gpu_usage(), get_system_status(), _nvml_gpu(), Snapshot of current system metrics for the system_status tool., Stateful monitor — cooldown state persists across session reconnections. Call…, GPU utilisation via NVML — zero subprocess on all platforms., SystemMonitor

### Community 52 - "get_input_device"
Cohesion: 0.16
Nodes (13): list_devices(), Device names for 'input' or 'output'. Falls back to a synchronous query if the…, get_input_device(), get_output_device(), _patch_config(), Read-modify-write one or more keys in api_keys.json. Every setter in this file…, Microphone device name, or '' for the system default., Speaker device name, or '' for the system default. (+5 more)

### Community 54 - ".run"
Cohesion: 0.20
Nodes (8): BaseException, _get_api_key(), _is_reconnect_signal(), _keep_context_of(), Background task: voice alerts when metrics exceed thresholds., Forward phone mic PCM chunks from dashboard queue into the Gemini Live session., True if `exc` is a _ReconnectSignal, or a(n) (Base)ExceptionGroup that wraps…, Read `keep_context` off a reconnect signal, unwrapping the group the TaskGroup…

### Community 58 - "ui.py"
Cohesion: 0.17
Nodes (12): Holographic AI head for the HUD centre — the thing that used to be a ring stack…, math, get_brief_enabled(), save_brief_enabled(), pyqt6_qtcore, pyqt6_qtgui, pyqt6_qtmultimedia, pyqt6_qtwidgets (+4 more)

### Community 59 - "WhisperSTT"
Cohesion: 0.33
Nodes (4): ndarray, Offline transcription using faster-whisper., Transcribe a float32 mono 16 kHz numpy array. Returns transcript string., WhisperSTT

### Community 61 - "ProactiveEngine"
Cohesion: 0.22
Nodes (4): ProactiveEngine, ProactiveEngine 2.0 — context-aware, time-aware, non-repetitive background…, Decides when ALFRED should speak unprompted and builds a context-rich prompt.…, Build a context snapshot for Gemini. Rotates through three focus areas so…

### Community 62 - "save_app_icon"
Cohesion: 0.20
Nodes (10): Update App Icon Action for ALFRED Mark-LIV. Switches the application window,…, Updates the main application icon and taskbar badge in realtime., update_app_icon(), Save the chosen app icon setting to config., save_app_icon(), format_icon_display_name(), get_available_app_icons(), Format an icon file name into an authentic, sleek tactical insignia title. (+2 more)

### Community 64 - "undo.py"
Cohesion: 0.18
Nodes (9): clear(), history(), peek(), core/undo.py — one shared undo stack for every action that changes state. WHY…, Forget the stack. Called when the app shuts down so closures holding old file…, Label of the operation that `undo_last()` would reverse, or ''., Most recent first — used by the UI panel and the `undo` tool's list mode., Reverse the most recent reversible operation. The entry is popped *before*… (+1 more)

### Community 65 - "DashboardServer"
Cohesion: 0.23
Nodes (3): DashboardServer, URL for manual browser entry. When HTTPS active, points to alias port (also…, Second HTTPS server on PORT+1 sharing the same app and in-memory state. Chrome…

### Community 66 - "._build_config"
Cohesion: 0.18
Nodes (9): LiveConnectConfig, _describe_limits(), _describe_tools(), _load_system_prompt(), The optional knobs, kept apart so one bad field can be dropped wholesale. Every…, One line per capability, straight from the live tool declarations. Derived…, The other half of self-knowledge: what is out of reach, and why. Derived from…, Fill {tokens} in the prompt template. A plain replace rather than str.format:… (+1 more)

### Community 67 - "_SysMetrics"
Cohesion: 0.21
Nodes (4): Thread-safe speech channel for plugins: lets a plugin ask JARVIS to say…, _nvml_gpu_windows(), Return NVIDIA GPU utilisation % using nvml.dll directly — zero subprocess., _SysMetrics

### Community 68 - "._apply_name_update"
Cohesion: 0.16
Nodes (10): get_voice(), Return the configured Live voice, falling back to the default if unset or if…, apply_ui_accent(), current_palette(), Applies DOSSIER CRT [A-34] (#8e9bff), VECTOR CRT [WAKU] (#a8ff3e), or BATMAN…, A snapshot of the accent-linked colours currently on class C., LIVE full theme change. Replaces the old palette colours with the new ones in…, Live preview — paints the whole interface the new colour (does NOT write to… (+2 more)

### Community 69 - "confirm.py"
Cohesion: 0.25
Nodes (10): bind(), _log(), _Pending, core/confirm.py — a confirmation the model cannot forge. THE PROBLEM WITH THE…, Called by the UI when the user presses CONFIRM or CANCEL. Runs the stored…, Wire this module to the HUD. Called once from main.py at startup., Park an irreversible action behind the on-screen gate. Returns the sentence the…, request() (+2 more)

### Community 71 - "WakeWordDetector"
Cohesion: 0.20
Nodes (4): Runs the wake model in a dedicated thread. The mic thread calls feed() with raw…, Load the model and spawn the inference thread. Returns True on success. Safe to…, Called from the mic callback (real-time thread). Must stay cheap and never…, WakeWordDetector

### Community 72 - "get_push_to_talk_enabled"
Cohesion: 0.29
Nodes (5): chord_label(), Human-readable name of the chord, for the UI and the logs., get_push_to_talk_enabled(), Hold-a-key-to-speak. When on, the mic is closed unless the chord is held., Repaint the push-to-talk row from the saved setting.

### Community 75 - "PluginManagerOverlay"
Cohesion: 0.31
Nodes (4): QHBoxLayout, QPushButton, PluginManagerOverlay, Floating overlay — lists discovered plugins with per-plugin ON/OFF toggles.

### Community 78 - "._play_audio"
Cohesion: 0.22
Nodes (7): callback(), _open_mic(), _pcm_level(), _pcm_visemes(), Map a block of int16 PCM samples to a 0.0–1.0 loudness level for the HUD…, Slice a PCM block into (level, openness, width) frames, one per 20 ms. Returns…, True while the speakers may still be finishing our last sentence.

### Community 79 - "LogWidget"
Cohesion: 0.25
Nodes (3): QTextEdit, LogWidget, Cancel any in-flight typing animation, drain the queue, and clear the display.

### Community 80 - "._apply_ptt_shortcut"
Cohesion: 0.29
Nodes (5): qt_sequence(), The same chord as a QKeySequence string., _press(), Bind the chord inside the window when no global hook is available. On macOS and…, Report a windowed press/release to whoever owns the microphone.

### Community 82 - ".__init__"
Cohesion: 0.29
Nodes (6): index(), _ensure_certs(), _local_ip(), Return the best LAN-facing IPv4 address, no internet required., Make sure config/certs holds a TLS key pair, generating a self-signed one the…, _read()

### Community 84 - ".request_reconnect"
Cohesion: 0.33
Nodes (3): Thread-safe: ask the run loop to tear down and rebuild the Live session. Called…, Voice picker applied. The voice is baked into the session at connect time, so a…, Microphone or speaker changed. Both streams are opened inside the session…

### Community 85 - ".__init__"
Cohesion: 0.17
Nodes (7): _Popen, Exception, Raised inside the session TaskGroup to force a clean, voluntary reconnect (e.g.…, Session-scoped task: when a voluntary reconnect is requested, raise a signal…, Turn hold-to-talk on or off. Returns the scope actually achieved., _ReconnectSignal, _OrigPopen

### Community 88 - "_detect_action"
Cohesion: 0.40
Nodes (5): _detect_action(), _normalise(), Resolve a free-text description to an action name, locally. Returns {"action":…, What to tell the model when nothing matched. Names real actions so its retry…, _suggest()

### Community 95 - "Daily Brief Protocol"
Cohesion: 0.50
Nodes (3): Daily Brief Protocol, Purpose, Rules

### Community 96 - "Email Handling Rules"
Cohesion: 0.50
Nodes (3): Email Handling Rules, Purpose, Rules

### Community 97 - "Executive Assistant Persona & Behavioral Standards"
Cohesion: 0.50
Nodes (3): Core Operational Rules, Executive Assistant Persona & Behavioral Standards, Persona & Demeanor

### Community 98 - "/email-triage Workflow"
Cohesion: 0.50
Nodes (3): /email-triage Workflow, Objective, Steps

### Community 99 - "_template.py"
Cohesion: 0.50
Nodes (3): Drop-in ALFRED plugin template. Copy this file, rename it (no leading…, parameters: dict of the args Gemini extracted, matching PLUGIN['parameters'].…, run()

### Community 100 - "_get_base_dir"
Cohesion: 0.67
Nodes (3): _get_api_key(), _get_base_dir(), Path

## Knowledge Gaps
- **35 isolated node(s):** `C`, `Purpose`, `Rules`, `Purpose`, `Rules` (+30 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 809 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **34 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `JarvisUI` connect `JarvisUI` to `JarvisLive`, `main.py`, `.__init__`, `.add_intel_note`, `setter`, `.hide_confirm`, `.prompt_reconfig`, `ui.py`, `.set_app_icon`, `._apply_name_update`, `.set_audio_level`, `.show_review`, `._wake_state`, `._apply_ptt_shortcut`, `.__init__`, `.clear_chat`, `.glance`, `.clear_intel_notes`, `.hide_quiz`, `.show_content`, `.show_quiz`, `.start_camera_stream`?**
  _High betweenness centrality (0.066) - this node is a cross-community bridge._
- **Why does `MainWindow` connect `MainWindow` to `.__init__`, `._apply_name_update`, `TronScoreBackgroundPlayer`, `get_push_to_talk_enabled`, `PluginManagerOverlay`, `mono_font`, `MemoryOverlay`, `._wake_state`, `._apply_ptt_shortcut`, `SetupOverlay`, `setter`, `ui.py`, `tech_font`, `.clear_chat`, `save_app_icon`?**
  _High betweenness centrality (0.066) - this node is a cross-community bridge._
- **Why does `JarvisLive` connect `JarvisLive` to `DashboardServer`, `._build_config`, `PushToTalk`, `_tlog`, `_SysMetrics`, `WakeWordDetector`, `avatar_mesh.py`, `._execute_tool`, `._play_audio`, `SystemMonitor`, `main.py`, `.__init__`, `.request_reconnect`, `EchoGuard`, `.run`, `JarvisUI`, `ProactiveEngine`?**
  _High betweenness centrality (0.054) - this node is a cross-community bridge._
- **Are the 8 inferred relationships involving `JarvisLive` (e.g. with `ProactiveEngine` and `SystemMonitor`) actually correct?**
  _`JarvisLive` has 8 INFERRED edges - model-reasoned connections that need verification._
- **What connects `C`, `Purpose`, `Rules` to the rest of the system?**
  _35 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `game_updater.py` be split into smaller, more focused modules?**
  _Cohesion score 0.056679151061173536 - nodes in this community are weakly interconnected._
- **Should `code_helper.py` be split into smaller, more focused modules?**
  _Cohesion score 0.07017543859649122 - nodes in this community are weakly interconnected._