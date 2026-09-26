# Graph Report - Mark-LIV  (2026-09-26)

## Corpus Check
- 85 files · ~170,519 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 8 file(s) not represented in the graph (top: (none) 3, .ico 2, .obj 2)

## Summary
- 1993 nodes · 3936 edges · 109 communities (89 shown, 20 thin omitted)
- Extraction: 96% EXTRACTED · 4% INFERRED · 0% AMBIGUOUS · INFERRED: 164 edges (avg confidence: 0.86)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `07e28d20`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- game_updater.py
- background_monitor.py
- computer_settings.py
- TronScoreBackgroundPlayer
- file_controller.py
- tts.py
- pathlib
- MainWindow
- TacticalAudioPlayerWidget
- gemini.py
- cache.py
- llm_client.py
- code_helper.py
- _HudOverlay
- memory_manager.py
- _BrowserSession
- computer_control.py
- dev_agent.py
- file_processor.py
- mono_font
- EchoGuard
- JarvisUI
- 🦇 ALFRED — MARK II (Wayne Protocol Edition)
- ProactiveEngine
- JarvisLive
- audio_devices.py
- crypto-js.min.js
- config_manager.py
- ._apply_ptt_shortcut
- send_message.py
- confirm.py
- server.py
- heal_execution_error
- HudCanvas
- computer_settings
- daily_brief.py
- VisemeStream
- system_monitor.py
- ActionRegistry
- test_traceback_benchmark.py
- CentralizedCache
- FileDropZone
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
- is_heavenly_restricted
- PushToTalk
- open_app.py
- setter
- datetime
- CustomizeOverlay
- ._build_right_panel
- sys
- ._play_audio
- MemoryOverlay
- Graphify + Antigravity Project Workflow & Setup Guide
- _get_macos_wifi_interface
- ._listen_audio
- _ensure_network_access
- rules/graphify.md
- _SessionRegistry
- workflows/graphify.md
- _detect_action
- ._apply_name_update
- ._decrypt
- WakeWordDetector
- tech_font
- ui.py
- _template.py
- _get_base_dir
- LogWidget
- _tlog
- get_push_to_talk_enabled
- _RootShim
- .__init__
- browser_control.py
- ._build_jarvis_icon
- _VolumeSliderPopup
- stt.py
- main.py
- Daily Brief Protocol
- Email Handling Rules
- Executive Assistant Persona & Behavioral Standards
- .clear_chat
- /email-triage Workflow
- plugin_loader.py
- .__init__
- json
- ._launch
- .request_reconnect
- .__init__
- SubjectDossierCard
- weather_report.py

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
- `Steps` --references--> `computer_control()`  [INFERRED]
  .agents/workflows/deep_work.md → actions/computer_control.py
- `🛡️ 2. Security, Privacy & Defensive Architecture` --references--> `computer_control()`  [INFERRED]
  readme.md → actions/computer_control.py
- `Steps` --references--> `daily_brief()`  [INFERRED]
  .agents/workflows/daily_brief.md → actions/daily_brief.py
- `1. File Opening (`open`)` --references--> `file_controller()`  [INFERRED]
  .agents/rules/file_exploration.md → actions/file_controller.py

## Import Cycles
- None detected.

## Communities (109 total, 20 thin omitted)

### Community 0 - "game_updater.py"
Cohesion: 0.06
Nodes (77): _build_google_flights_url(), flight_finder(), _format_spoken(), _format_text_report(), _get_base_dir(), _parse_date(), _parse_flights_with_gemini(), Path (+69 more)

### Community 1 - "background_monitor.py"
Cohesion: 0.23
Nodes (13): add_monitor(), check_all(), _is_blocked(), list_monitors(), _load(), BackgroundMonitor — user-configured topic watching. Checks DDG news once per…, Run all pending topic checks (once per day per topic). Returns a list of…, remove_monitor() (+5 more)

### Community 3 - "TronScoreBackgroundPlayer"
Cohesion: 0.11
Nodes (7): QObject, _base_dir(), Path, Background music audio engine. Plays background score continuously on loop…, Set base normal volume (0.0 to 1.0). Speech ducking scales to 50% of base., Duck to 50% of base volume when speaking, restore to base volume when…, TronScoreBackgroundPlayer

### Community 4 - "file_controller.py"
Cohesion: 0.07
Nodes (62): copy_file(), create_file(), create_folder(), delete_file(), explore_folder(), file_controller(), find_files(), _format_size() (+54 more)

### Community 5 - "tts.py"
Cohesion: 0.07
Nodes (26): asyncio, _compress_silence(), create_tts_player(), EdgeTTSEngine, ElevenLabsTTSEngine, _import_kokoro_pipeline(), KokoroTTSEngine, _synth() (+18 more)

### Community 6 - "pathlib"
Cohesion: 0.05
Nodes (51): _blend(), _c(), HoloAvatar, _add_cowl_ears(), _add_cranium(), _add_neck(), _boundary_loop(), build_head() (+43 more)

### Community 7 - "MainWindow"
Cohesion: 0.07
Nodes (6): QMainWindow, MainWindow, Slot — display camera preview overlay (main thread)., Slot — runs on Qt main thread. Updates and shows the content panel., Slot — Qt main thread. Lays a document review into the content panel., Slot — Qt main thread. Puts a fresh quiz on the board.

### Community 8 - "TacticalAudioPlayerWidget"
Cohesion: 0.17
Nodes (4): _EqualizerBarsWidget, Mini animated cyber audio wave visualizer., Bottom-Left Cyber Tactical Audio Player Widget. Styled matching the HUD /…, TacticalAudioPlayerWidget

### Community 9 - "gemini.py"
Cohesion: 0.08
Nodes (41): _ask_gemini_for_desktop_action(), _build_sandbox(), clean_desktop(), desktop_control(), _execute_generated_code(), _get_api_key(), _get_base_dir(), get_current_wallpaper() (+33 more)

### Community 10 - "cache.py"
Cohesion: 0.16
Nodes (12): Permanently saves daily briefing preferences into long-term memory., update_daily_briefing(), get_cache(), core/cache.py — Centralized Caching Layer for ALFRED Mark-II. Provides high-…, Returns the centralized cache client singleton., functools, hashlib, patch (+4 more)

### Community 11 - "llm_client.py"
Cohesion: 0.09
Nodes (32): _auto_detect_type(), _config_dir(), intel_notes(), _load_notes(), Path, actions/intel_notes.py — Dedicated Intel & Notes Terminal Action. Provides a…, Action handler called by Gemini / action_loader., _save_notes() (+24 more)

### Community 12 - "code_helper.py"
Cohesion: 0.18
Nodes (25): _build(), _clean_code(), code_helper(), _detect_intent(), _edit_action(), _explain_action(), _fix_code(), _get_gemini() (+17 more)

### Community 13 - "_HudOverlay"
Cohesion: 0.14
Nodes (5): ConfirmBanner, _HudOverlay, Base for the floating panels placed by hand over the HUD. They are children of…, The gate in front of an action that cannot be taken back. The old confirmation…, Place a floating overlay in the middle of the HUD and show it.

### Community 14 - "memory_manager.py"
Cohesion: 0.11
Nodes (28): Update Daily Briefing Preferences Action for ALFRED Mark-LIV. Permanently…, _do_shutdown(), Summarise the current session in 1-2 sentences and save to long_term.json., _all_entries(), all_entries_for_ui(), _empty_memory(), _entry_value(), forget() (+20 more)

### Community 16 - "computer_control.py"
Cohesion: 0.18
Nodes (27): _base_dir(), _clear_field(), _click(), _clipboard_get(), _clipboard_paste(), computer_control(), _drag(), _focus_window() (+19 more)

### Community 17 - "dev_agent.py"
Cohesion: 0.16
Nodes (21): _build_project(), _classify_error(), _fix_files(), _get_model(), _has_error(), _install_dependencies(), _is_rate_limit(), _llm_repair() (+13 more)

### Community 18 - "file_processor.py"
Cohesion: 0.07
Nodes (46): _detect_type(), file_processor(), _file_size_str(), _gemini_client(), _output_path(), _process_archive(), _process_audio(), _process_code() (+38 more)

### Community 19 - "mono_font"
Cohesion: 0.06
Nodes (18): QFont, QWidget, BiometricFingerprintWidget, _CameraPreview, ClipboardPanel, CRTReconWidget, MetricBar, mono_font() (+10 more)

### Community 20 - "EchoGuard"
Cohesion: 0.08
Nodes (14): band_energies(), EchoGuard, ndarray, Classifies microphone blocks while the assistant is speaking. Usage:…, True once the estimate rests on enough real echo to be trusted., Residual left by this room's own echo. Higher = harder to separate., False when the acoustics are too poor to judge on content alone. Speakers…, The residual a block must clear right now to count as a voice. (+6 more)

### Community 21 - "JarvisUI"
Cohesion: 0.05
Nodes (17): JarvisUI, Thread-safe: raise the irreversible-action gate. Called from action handlers…, Thread-safe: take the gate down., Thread-safe: feed a 0.0–1.0 live audio level to the HUD waveform. Called from…, Ask the avatar to look somewhere for a moment (see HoloAvatar.glance)., Thread-safe: post a schedule of (level, openness, width) mouth frames for…, Thread-safe: wipe the on-screen conversation chat feed., Thread-safe: post special note, research link, or structured data to the… (+9 more)

### Community 22 - "🦇 ALFRED — MARK II (Wayne Protocol Edition)"
Cohesion: 0.08
Nodes (24): ⚡ 10. Quick Start & Installation, 🔧 11. Configuration Reference (`config/api_keys.json`), 📊 12. Knowledge Graph (`graphify`), 👤 13. Author & Credits, 🖥️ 1. 100% Local & Air-Gapped Offline Execution, 1. Prerequisites, 2. Setup & Execution, 🎙️ 3. Real-Time Multimodal Intelligence & Dual Audio Engine (+16 more)

### Community 23 - "ProactiveEngine"
Cohesion: 0.29
Nodes (3): ProactiveEngine, Decides when ALFRED should speak unprompted and builds a context-rich prompt.…, Build a context snapshot for Gemini. Rotates through three focus areas so…

### Community 24 - "JarvisLive"
Cohesion: 0.10
Nodes (10): JarvisLive, Called from the detector thread when 'Hey Jarvis' is heard., Auto-sleep after the configured silence window (wake-word mode only)., Enable/disable wake word from the settings UI. Returns a status token:…, Manual sleep/wake button in the UI., Download openwakeword + the model (runs in a UI worker thread)., Called from Qt main thread when user presses Remote Control., Called when user clicks the CLEAR button in desktop GUI. (+2 more)

### Community 25 - "audio_devices.py"
Cohesion: 0.11
Nodes (21): configure(), _display_name(), _is_pseudo(), list_devices(), prefetch(), _work(), _query(), _collect() (+13 more)

### Community 27 - "config_manager.py"
Cohesion: 0.12
Nodes (24): ensure_config_dir(), get_base_dir(), get_brief_enabled(), get_gemini_key(), is_configured(), Path, Read-modify-write one key without disturbing the rest of the config., Merge `values` into a namespace's stored config (read-modify-write, like every… (+16 more)

### Community 28 - "._apply_ptt_shortcut"
Cohesion: 0.40
Nodes (3): _press(), Bind the chord inside the window when no global hook is available. On macOS and…, Report a windowed press/release to whoever owns the microphone.

### Community 29 - "send_message.py"
Cohesion: 0.23
Nodes (20): _base_dir(), _clear_and_paste(), _desktop_send(), _get_os(), _open_app(), _open_browser_url(), _paste_text(), Path (+12 more)

### Community 30 - "confirm.py"
Cohesion: 0.19
Nodes (13): bind(), _log(), _Pending, pending_title(), core/confirm.py — a confirmation the model cannot forge. THE PROBLEM WITH THE…, Called by the UI when the user presses CONFIRM or CANCEL. Runs the stored…, when nothing is waiting. Lets an action avoid stacking two banners., Wire this module to the HUD. Called once from main.py at startup. (+5 more)

### Community 31 - "server.py"
Cohesion: 0.12
Nodes (13): base64, _derive_key(), _make_uploads_dir(), Path, dashboard/server.py — ALFRED Local HTTP Dashboard Plain HTTP on port 8000 (no…, Return (and create) the cross-platform uploads folder., SHA-256(sessionKey‖salt) → 32-byte AES-256 key (microseconds, no PBKDF2 needed)., fastapi (+5 more)

### Community 32 - "heal_execution_error"
Cohesion: 0.19
Nodes (12): apply_heal_patch(), dev_agent(), _diagnose_trace(), _extract_culprit_script(), heal_execution_error(), _heuristic_repair(), Isolates the target script path from explicit argument or stack trace., Parses stderr and stack traces to isolate error category, line number, and… (+4 more)

### Community 33 - "HudCanvas"
Cohesion: 0.09
Nodes (15): HudCanvas, QPainter, Thread-safe entry point for the audio threads. Stores the louder of the…, True only when this canvas can actually be seen by the user., Draw the Avengers: Endgame Stark Arc Reactor at (cx, cy) with outer radius r., Draw subtle background CRT coordinate grid with + crosshairs (Screenshot 2)., 3D Rotating Vector Wireframe Globe (Matching Screenshot 2: WAKU CRT Globe).…, Futuristic Oscilloscope Waveforms spanning across the globe (Screenshot 1 & 2… (+7 more)

### Community 34 - "computer_settings"
Cohesion: 0.12
Nodes (16): brightness_get(), brightness_set(), computer_settings(), dark_mode(), paste(), press_key(), Current brightness 0-100, or None where it cannot be read., Set brightness to an absolute percentage. Only used to restore a value captured… (+8 more)

### Community 35 - "daily_brief.py"
Cohesion: 0.12
Nodes (21): daily_brief(), _get_gmail_brief(), _get_greeting(), _get_live_weather(), _get_reminders_brief(), _get_system_vitals(), Daily Brief Action for ALFRED Mark-LIV. Provides the ultimate morning and daily…, Fetch unread emails summary via gmail_manager. (+13 more)

### Community 36 - "VisemeStream"
Cohesion: 0.13
Nodes (12): collections, coverage(), Text → mouth shape, fused with the audio the avatar is actually speaking. Why…, Reduce any character to a bare Latin letter, or "" if it has none. This is what…, Fraction of the letters in `text` we can reduce to a Latin sound., Split a line of speech into (viseme, duration-weight) pairs. Returns [] for…, Fuses the transcript's shape sequence onto the audio's timing. Thread note:…, Blend audio frames [(level, openness, width)] with the text queue. (+4 more)

### Community 37 - "system_monitor.py"
Cohesion: 0.20
Nodes (10): _get_cpu_temp(), _get_gpu_usage(), get_system_status(), _nvml_gpu(), System Monitor — background metric checks with voice alert support. Zero…, Snapshot of current system metrics for the system_status tool., Stateful monitor — cooldown state persists across session reconnections. Call…, GPU utilisation via NVML — zero subprocess on all platforms. (+2 more)

### Community 38 - "ActionRegistry"
Cohesion: 0.16
Nodes (9): ActionRecord, ActionRegistry, discover_actions(), _opt_upper(), Path, Returns an ActionRecord; .valid=False + .error set on any problem. Never raises., Scans actions_dir for *.py files (skips files starting with '_'). A file is…, How this action's result should re-enter the conversation, if it said. (+1 more)

### Community 39 - "test_traceback_benchmark.py"
Cohesion: 0.33
Nodes (5): _parse_traceback(), Performance Benchmark: dev_agent._parse_traceback Tests O(1) hash map lookups…, Measures lookup time across 50,000 mock project files and 500 stack frames., TestTracebackBenchmark, unittest

### Community 40 - "CentralizedCache"
Cohesion: 0.06
Nodes (22): CentralizedCache, _canonicalize(), decorator(), wrapper(), Any, Stores value in cache with TTL. Fails open gracefully if storage fails., Deletes a key from cache. Fails open gracefully., Invalidates all keys starting with prefix. Useful for mutation hooks. (+14 more)

### Community 41 - "FileDropZone"
Cohesion: 0.07
Nodes (9): QDragEnterEvent, QDropEvent, QPointF, QRectF, CyberGraphicLineButton, FileDropZone, HueWheel, Tactical button rendered strictly with vector graphic lines, sharp 2px border… (+1 more)

### Community 42 - "web_search.py"
Cohesion: 0.11
Nodes (33): _compare(), _ddg_news(), _ddg_search(), _format_ddg(), _format_news(), _gemini_available(), _gemini_search(), _get_base_dir() (+25 more)

### Community 43 - "RemoteKeyOverlay"
Cohesion: 0.27
Nodes (4): Floating overlay — QR code for instant phone pairing + manual key fallback., Call from any thread when a phone successfully connects., RemoteKeyOverlay, _lbl()

### Community 44 - "qcol"
Cohesion: 0.17
Nodes (7): QPixmap, _DropCanvas, _file_category(), _fmt_size(), QColor, qcol(), Pre-render the static grid-dot background into a transparent pixmap so…

### Community 45 - ".run"
Cohesion: 0.20
Nodes (8): BaseException, _get_api_key(), _is_reconnect_signal(), _keep_context_of(), Background task: voice alerts when metrics exceed thresholds., Forward phone mic PCM chunks from dashboard queue into the Gemini Live session., True if `exc` is a _ReconnectSignal, or a(n) (Base)ExceptionGroup that wraps…, Read `keep_context` off a reconnect signal, unwrapping the group the TaskGroup…

### Community 46 - "._build_app"
Cohesion: 0.20
Nodes (11): _auth(), auto_login(), clear_chat_ep(), device_login_ep(), list_files(), login(), phone_audio_ws(), revoke_devices() (+3 more)

### Community 47 - "save_app_icon"
Cohesion: 0.40
Nodes (5): Update App Icon Action for ALFRED Mark-LIV. Switches the application window,…, Updates the main application icon and taskbar badge in realtime., update_app_icon(), Save the chosen app icon setting to config., save_app_icon()

### Community 48 - "_SysMetrics"
Cohesion: 0.21
Nodes (4): Thread-safe speech channel for plugins: lets a plugin ask JARVIS to say…, _nvml_gpu_windows(), Return NVIDIA GPU utilisation % using nvml.dll directly — zero subprocess., _SysMetrics

### Community 49 - "load_api_keys"
Cohesion: 0.14
Nodes (14): The optional knobs, kept apart so one bad field can be dropped wholesale. Every…, get_app_icon(), get_hud_style(), get_media_resolution(), get_thinking_enabled(), get_turn_tuning(), get_wake_word_enabled(), load_api_keys() (+6 more)

### Community 51 - "screen_processor.py"
Cohesion: 0.16
Nodes (19): _base_dir(), _capture_camera(), _capture_screen(), _compress(), _cv2_backend(), _detect_camera_index(), _get_camera_index(), _get_os() (+11 more)

### Community 52 - "DashboardServer"
Cohesion: 0.23
Nodes (3): DashboardServer, URL for manual browser entry. When HTTPS active, points to alias port (also…, Second HTTPS server on PORT+1 sharing the same app and in-memory state. Chrome…

### Community 53 - "is_heavenly_restricted"
Cohesion: 0.13
Nodes (20): _call_handler(), _is_heavenly_restricted_params(), Action discovery, validation, and dispatch — the built-in twin of…, Invoke the handler passing only the context kwargs it actually declares (or all…, check_action_params(), check_path_access(), get_allowed_c_roots(), is_heavenly_restricted() (+12 more)

### Community 54 - "PushToTalk"
Cohesion: 0.18
Nodes (5): PushToTalk, Begin watching. Returns the scope actually achieved., Feed a press/release from a Qt shortcut (non-Windows, or no hook)., Calls `on_change(held: bool)` whenever the chord is pressed or released. Start…, global' once a system-wide hook is running, else 'window'.

### Community 55 - "open_app.py"
Cohesion: 0.18
Nodes (7): _normalize(), open_app(), /deep-work Workflow, Objective, Steps, 🛡️ 2. Security, Privacy & Defensive Architecture, shutil

### Community 56 - "setter"
Cohesion: 0.10
Nodes (3): setter, _work(), Combined state for the two wake-word buttons. Readiness is a cheap,…

### Community 57 - "datetime"
Cohesion: 0.06
Nodes (43): _clean_header_str(), _extract_body_snippet(), gmail_manager(), _load_gmail_creds(), Any, Gmail Manager Action for ALFRED Mark-LIV. Provides full Gmail connectivity: -…, Send an email using Gmail SMTP SSL., Action entry point for Gmail interaction. (+35 more)

### Community 58 - "CustomizeOverlay"
Cohesion: 0.14
Nodes (10): CustomizeOverlay, _lbl(), format_icon_display_name(), get_available_app_icons(), Floating glassmorphic overlay for configuring Assistant Persona, Commander…, Highlight the selected voice pill; dim the rest., Updates the selected colour; hex box + wheel stay in sync, theme is live-…, Format an icon file name into an authentic, sleek tactical insignia title. (+2 more)

### Community 59 - "._build_right_panel"
Cohesion: 0.18
Nodes (3): QHBoxLayout, Read api_keys.json config dict. Returns {} on any error., _read_full_config()

### Community 60 - "sys"
Cohesion: 0.09
Nodes (29): qt_sequence(), Push-to-talk — hold a key, speak, release. Why this exists ---------------…, The same chord as a QKeySequence string., _available(), install_for_config(), _pip(), MARK XL — Dependency auto-installer. Called automatically on first launch and…, Return True if the module can be imported (no actual import). (+21 more)

### Community 61 - "._play_audio"
Cohesion: 0.25
Nodes (5): _pcm_level(), _pcm_visemes(), Map a block of int16 PCM samples to a 0.0–1.0 loudness level for the HUD…, Slice a PCM block into (level, openness, width) frames, one per 20 ms. Returns…, Stop JARVIS mid-speech: drain queued audio and open mic immediately.

### Community 62 - "MemoryOverlay"
Cohesion: 0.33
Nodes (4): MemoryOverlay, Everything ALFRED has stored about you, and when it learned it. Memory used to…, Take every item out of the layout and detach it from the widget tree in this…, Size the panel to its content, re-centre it, and repaint what the old size…

### Community 65 - "._listen_audio"
Cohesion: 0.50
Nodes (3): callback(), _open_mic(), True while the speakers may still be finishing our last sentence.

### Community 68 - "_SessionRegistry"
Cohesion: 0.15
Nodes (5): _detect_default_browser(), Manages all active browser sessions., Is there an active automation session for this browser (or any)?, Returns the last natively-opened URL once (consumed to avoid repeats)., _SessionRegistry

### Community 70 - "_detect_action"
Cohesion: 0.40
Nodes (5): _detect_action(), _normalise(), Resolve a free-text description to an action name, locally. Returns {"action":…, What to tell the model when nothing matched. Names real actions so its retry…, _suggest()

### Community 71 - "._apply_name_update"
Cohesion: 0.20
Nodes (8): apply_ui_accent(), current_palette(), Applies DOSSIER CRT [A-34] (#8e9bff), VECTOR CRT [WAKU] (#a8ff3e), or BATMAN…, A snapshot of the accent-linked colours currently on class C., LIVE full theme change. Replaces the old palette colours with the new ones in…, Live preview — paints the whole interface the new colour (does NOT write to…, Update all name/theme-dependent UI elements and persist to config., retheme_all_widgets()

### Community 73 - "._decrypt"
Cohesion: 0.40
Nodes (4): command(), ws_ep(), _decrypt_cbc(), Decrypt base64(IV[16] ‖ ciphertext) with AES-256-CBC + PKCS7.

### Community 74 - "WakeWordDetector"
Cohesion: 0.17
Nodes (5): Runs the wake model in a dedicated thread. The mic thread calls feed() with raw…, Load the model and spawn the inference thread. Returns True on success. Safe to…, Called from the mic callback (real-time thread). Must stay cheap and never…, WakeWordDetector, Load the detector once (model loads on first start). Idempotent.

### Community 75 - "tech_font"
Cohesion: 0.12
Nodes (9): QPushButton, QVBoxLayout, CapabilitiesOverlay, PluginManagerOverlay, PluginSettingsOverlay, Floating glassmorphic overlay displaying a categorized directory of everything…, Floating overlay — lists discovered plugins with per-plugin ON/OFF toggles., Floating overlay — renders per-plugin settings forms. Fully generic: it… (+1 more)

### Community 77 - "ui.py"
Cohesion: 0.18
Nodes (13): get_input_device(), get_output_device(), _patch_config(), Read-modify-write one or more keys in api_keys.json. Every setter in this file…, Microphone device name, or '' for the system default., Speaker device name, or '' for the system default., save_input_device(), save_output_device() (+5 more)

### Community 79 - "_template.py"
Cohesion: 0.50
Nodes (3): Drop-in ALFRED plugin template. Copy this file, rename it (no leading…, parameters: dict of the args Gemini extracted, matching PLUGIN['parameters'].…, run()

### Community 80 - "_get_base_dir"
Cohesion: 0.67
Nodes (3): _get_api_key(), _get_base_dir(), Path

### Community 81 - "LogWidget"
Cohesion: 0.29
Nodes (3): QTextEdit, LogWidget, Cancel any in-flight typing animation, drain the queue, and clear the display.

### Community 82 - "_tlog"
Cohesion: 0.11
Nodes (13): _clean_transcript(), _is_repeat_chunk(), _deliver_news(), main(), runner(), Format terminal log report without emojis using red bracketed tags, and…, Send a captured frame immediately after its tool response. The frame is already…, Two-phase briefing optimized for speed: Phase 1 — instant greeting (no tools) →… (+5 more)

### Community 83 - "get_push_to_talk_enabled"
Cohesion: 0.33
Nodes (5): chord_label(), Human-readable name of the chord, for the UI and the logs., get_push_to_talk_enabled(), Hold-a-key-to-speak. When on, the mic is closed unless the chord is held., Repaint the push-to-talk row from the saved setting.

### Community 85 - ".__init__"
Cohesion: 0.29
Nodes (6): index(), _ensure_certs(), _local_ip(), Return the best LAN-facing IPv4 address, no internet required., Make sure config/certs holds a TLS key pair, generating a self-signed one the…, _read()

### Community 86 - "browser_control.py"
Cohesion: 0.24
Nodes (11): browser_control(), _find_exe_windows(), _find_opera_windows(), _log(), _normalize_url(), _open_native(), Bare words like "instagram" → "https://instagram.com" Domains like…, Opens the user's REAL browser normally — with their own profile, logged-in… (+3 more)

### Community 87 - "._build_jarvis_icon"
Cohesion: 0.22
Nodes (4): Render an ALFRED tactical icon at 4× resolution and downsample for crisp…, Create a Windows .lnk shortcut WITHOUT launching PowerShell or cmd. Tries…, Resolve the user's REAL desktop directory instead of assuming ~/Desktop, which…, Create a desktop shortcut on Windows / macOS / Linux. Never opens a terminal,…

### Community 88 - "_VolumeSliderPopup"
Cohesion: 0.33
Nodes (3): QFrame, Sleek tactical cyber popup for adjusting master background music volume.…, _VolumeSliderPopup

### Community 89 - "stt.py"
Cohesion: 0.15
Nodes (8): ndarray, Speech-to-Text engines for MARK XL. Whisper – offline transcription via faster-…, Offline transcription using faster-whisper., Transcribe a float32 mono 16 kHz numpy array. Returns transcript string., Streaming transcription using Vosk., Feed raw int16 LE PCM bytes. Returns (text, is_final)., VoskSTT, WhisperSTT

### Community 93 - "main.py"
Cohesion: 0.11
Nodes (19): ProactiveEngine 2.0 — context-aware, time-aware, non-repetitive background…, Telling the user's voice apart from our own coming back through the speakers.…, google, google_genai, LiveConnectConfig, _describe_limits(), _describe_tools(), _load_system_prompt() (+11 more)

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

### Community 99 - "plugin_loader.py"
Cohesion: 0.10
Nodes (23): _call_run(), discover_plugins(), _load_error(), _opt_upper(), PluginRecord, PluginRegistry, Exception, Path (+15 more)

### Community 107 - ".__init__"
Cohesion: 0.11
Nodes (5): _fl(), Floating overlay panel shown when the ⚙ header button is toggled., Returns True if auto-start is currently registered on this OS., Swap the centrepiece. Both objects stay in memory, so the change is instant and…, Update application and window icon in realtime.

### Community 108 - "json"
Cohesion: 0.20
Nodes (6): json, Performance Benchmark: memory_manager._trim_to_limit Tests execution time and…, Measures execution time for 50,000 mock records. Under the old O(N^2)…, Preserves all items when memory is already below limit., Handles empty memory structure gracefully., TestMemoryTrimBenchmark

### Community 110 - "._launch"
Cohesion: 0.29
Nodes (5): _firefox_profile_dir(), launch_persistent_context already opens a starting tab. Instead of opening a…, Launches the browser with the real user profile. Does nothing if the context is…, _real_profile_dir(), Page

### Community 111 - ".request_reconnect"
Cohesion: 0.33
Nodes (3): Thread-safe: ask the run loop to tear down and rebuild the Live session. Called…, Voice picker applied. The voice is baked into the session at connect time, so a…, Microphone or speaker changed. Both streams are opened inside the session…

### Community 112 - ".__init__"
Cohesion: 0.17
Nodes (7): _Popen, Exception, Raised inside the session TaskGroup to force a clean, voluntary reconnect (e.g.…, Session-scoped task: when a voluntary reconnect is requested, raise a signal…, Turn hold-to-talk on or off. Returns the scope actually achieved., _ReconnectSignal, _OrigPopen

### Community 114 - "weather_report.py"
Cohesion: 0.50
Nodes (4): _log(), weather_action(), urllib_parse, webbrowser

## Knowledge Gaps
- **34 isolated node(s):** `C`, `Purpose`, `Rules`, `Purpose`, `Rules` (+29 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 793 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **20 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `MainWindow` connect `MainWindow` to `.clear_chat`, `._apply_name_update`, `config_manager.py`, `.__init__`, `tech_font`, `ui.py`, `_HudOverlay`, `qcol`, `mono_font`, `get_push_to_talk_enabled`, `._build_jarvis_icon`, `setter`, `CustomizeOverlay`, `._build_right_panel`, `._apply_ptt_shortcut`?**
  _High betweenness centrality (0.083) - this node is a cross-community bridge._
- **Why does `JarvisUI` connect `JarvisUI` to `.clear_chat`, `._apply_name_update`, `.__init__`, `ui.py`, `.__init__`, `_tlog`, `mono_font`, `JarvisLive`, `setter`, `._apply_ptt_shortcut`, `main.py`?**
  _High betweenness centrality (0.065) - this node is a cross-community bridge._
- **Why does `JarvisLive` connect `JarvisLive` to `background_monitor.py`, `memory_manager.py`, `EchoGuard`, `JarvisUI`, `ProactiveEngine`, `VisemeStream`, `system_monitor.py`, `.run`, `_SysMetrics`, `load_api_keys`, `DashboardServer`, `PushToTalk`, `._play_audio`, `._listen_audio`, `WakeWordDetector`, `_tlog`, `main.py`, `.request_reconnect`, `.__init__`?**
  _High betweenness centrality (0.052) - this node is a cross-community bridge._
- **Are the 8 inferred relationships involving `JarvisLive` (e.g. with `ProactiveEngine` and `SystemMonitor`) actually correct?**
  _`JarvisLive` has 8 INFERRED edges - model-reasoned connections that need verification._
- **What connects `C`, `Purpose`, `Rules` to the rest of the system?**
  _34 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `game_updater.py` be split into smaller, more focused modules?**
  _Cohesion score 0.06310958118187034 - nodes in this community are weakly interconnected._
- **Should `computer_settings.py` be split into smaller, more focused modules?**
  _Cohesion score 0.04081632653061224 - nodes in this community are weakly interconnected._