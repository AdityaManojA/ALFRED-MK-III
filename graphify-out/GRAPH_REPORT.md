# Graph Report - Alfred-Mark-III  (2026-09-26)

## Corpus Check
- 84 files · ~173,930 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 13 file(s) not represented in the graph (top: .ico 7, (none) 3, .obj 2)

## Summary
- 2097 nodes · 4099 edges · 116 communities (95 shown, 21 thin omitted)
- Extraction: 96% EXTRACTED · 4% INFERRED · 0% AMBIGUOUS · INFERRED: 169 edges (avg confidence: 0.87)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `80c7b595`
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
- pathlib
- memory_manager.py
- get_llm_settings
- EchoGuard
- 🦇 ALFRED — MARK II (Wayne Protocol Edition)
- JarvisUI
- config_manager.py
- PluginSettingsOverlay
- tech_font
- action_loader.py
- audio_devices.py
- crypto-js.min.js
- screen_processor.py
- send_message.py
- _tlog
- is_heavenly_restricted
- capture_screen
- audio_ducker.py
- intel_notes.py
- get_plugin_enabled
- ._build_app
- TestBackgroundWorkerPool
- load_api_keys
- daily_brief
- desktop.py
- MemoryOverlay
- background_monitor.py
- computer_settings
- main.py
- PushToTalk
- FileDropZone
- system_monitor.py
- _HudOverlay
- test_cache.py
- .run
- setter
- ._build_config
- get_push_to_talk_enabled
- ui.py
- numpy
- NotesTerminalWidget
- ._build_jarvis_icon
- save_app_icon
- TacticalAudioPlayerWidget
- undo.py
- DashboardServer
- viseme.py
- _SysMetrics
- ._apply_name_update
- .broadcast
- ._wake_state
- WakeWordDetector
- setup.py
- VisemeStream
- get_active_window_info
- _trim_to_limit
- _DropCanvas
- ScreenCapturePayload
- unduck_media_apps
- LogWidget
- ._apply_ptt_shortcut
- .test_error_isolation_in_concurrent_tasks
- .__init__
- _ensure_network_access
- TestAudioDucker
- .__init__
- _news
- .__init__
- _detect_action
- .request_reconnect
- WireframePoseWidget
- _gemini_headlines
- _RootShim
- .clear_chat
- ._decrypt
- Daily Brief Protocol
- Email Handling Rules
- Executive Assistant Persona & Behavioral Standards
- /email-triage Workflow
- _template.py
- _get_base_dir
- Graphify + Antigravity Project Workflow & Setup Guide
- WhisperSTT
- _get_macos_wifi_interface
- type_text
- rules/graphify.md
- workflows/graphify.md
- format_window_context
- ._listen_audio
- pil
- get_plugin_config

## God Nodes (most connected - your core abstractions)
1. `MainWindow` - 91 edges
2. `JarvisLive` - 60 edges
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

## Communities (116 total, 21 thin omitted)

### Community 0 - "game_updater.py"
Cohesion: 0.05
Nodes (84): browser_control(), _log(), _build_google_flights_url(), flight_finder(), _format_spoken(), _format_text_report(), _get_base_dir(), _parse_date() (+76 more)

### Community 1 - "code_helper.py"
Cohesion: 0.07
Nodes (49): _build(), _clean_code(), code_helper(), _detect_intent(), _edit_action(), _explain_action(), _fix_code(), _get_gemini() (+41 more)

### Community 2 - "MainWindow"
Cohesion: 0.05
Nodes (7): QMainWindow, MainWindow, Slot — display camera preview overlay (main thread)., Slot — runs on Qt main thread. Updates and shows the content panel., Slot — Qt main thread. Lays a document review into the content panel., Slot — Qt main thread. Puts a fresh quiz on the board., Returns True if auto-start is currently registered on this OS.

### Community 3 - "file_processor.py"
Cohesion: 0.08
Nodes (45): _detect_type(), file_processor(), _file_size_str(), _gemini_client(), _output_path(), _process_archive(), _process_audio(), _process_code() (+37 more)

### Community 4 - "file_controller.py"
Cohesion: 0.09
Nodes (53): copy_file(), create_file(), create_folder(), delete_file(), explore_folder(), file_controller(), find_files(), _format_size() (+45 more)

### Community 5 - "TronScoreBackgroundPlayer"
Cohesion: 0.11
Nodes (7): QObject, _base_dir(), Path, Background music audio engine. Plays background score continuously on loop…, Set base normal volume (0.0 to 1.0). Speech ducking scales to 50% of base., Duck to 50% of base volume when speaking, restore to base volume when…, TronScoreBackgroundPlayer

### Community 6 - "CustomizeOverlay"
Cohesion: 0.10
Nodes (9): QPointF, QRectF, CustomizeOverlay, _lbl(), HueWheel, Circular colour picker. The user drags the handle (small white circle) around…, Floating glassmorphic overlay for configuring Assistant Persona, Commander…, Highlight the selected voice pill; dim the rest. (+1 more)

### Community 8 - "avatar_mesh.py"
Cohesion: 0.14
Nodes (22): _add_cowl_ears(), _add_cranium(), _add_neck(), _boundary_loop(), build_head(), _check_landmarks(), get_head_mesh(), _load_obj() (+14 more)

### Community 9 - "qcol"
Cohesion: 0.08
Nodes (19): QPixmap, HudCanvas, QColor, QPainter, qcol(), Thread-safe entry point for the audio threads. Stores the louder of the…, Pre-render the static grid-dot background into a transparent pixmap so…, True only when this canvas can actually be seen by the user. (+11 more)

### Community 10 - "tts.py"
Cohesion: 0.07
Nodes (25): _compress_silence(), create_tts_player(), EdgeTTSEngine, ElevenLabsTTSEngine, _import_kokoro_pipeline(), KokoroTTSEngine, _synth(), _play_audio_bytes() (+17 more)

### Community 11 - "CentralizedCache"
Cohesion: 0.06
Nodes (22): CentralizedCache, _canonicalize(), decorator(), wrapper(), Any, Stores value in cache with TTL. Fails open gracefully if storage fails., Deletes a key from cache. Fails open gracefully., Invalidates all keys starting with prefix. Useful for mutation hooks. (+14 more)

### Community 12 - "web_search.py"
Cohesion: 0.13
Nodes (27): _compare(), _fetch_item(), _ddg_news(), _ddg_search(), _format_ddg(), _gemini_available(), _gemini_search(), _get_base_dir() (+19 more)

### Community 13 - "mono_font"
Cohesion: 0.09
Nodes (15): QFont, QHBoxLayout, QWidget, BiometricFingerprintWidget, _CameraPreview, CRTReconWidget, _fl(), MetricBar (+7 more)

### Community 14 - "datetime"
Cohesion: 0.06
Nodes (47): _get_gmail_brief(), Fetch unread emails summary via gmail_manager., _clean_header_str(), _extract_body_snippet(), fetch_unread_emails(), gmail_manager(), _load_gmail_creds(), Any (+39 more)

### Community 15 - "HoloAvatar"
Cohesion: 0.11
Nodes (19): _blend(), _c(), HoloAvatar, QColor, QPainter, _rate(), `col` at alpha `a` pre-mixed onto `bg`, returned fully **opaque**. Qt's raster…, Animated holographic head. One instance per HUD canvas. Lifecycle: av =… (+11 more)

### Community 16 - "JarvisLive"
Cohesion: 0.09
Nodes (11): JarvisLive, Chord pressed or released — may arrive on the hotkey thread., Called from the detector thread when 'Hey Jarvis' is heard., Auto-sleep after the configured silence window (wake-word mode only)., Enable/disable wake word from the settings UI. Returns a status token:…, Manual sleep/wake button in the UI., Download openwakeword + the model (runs in a UI worker thread)., Called from Qt main thread when user presses Remote Control. (+3 more)

### Community 17 - "_BrowserSession"
Cohesion: 0.05
Nodes (19): _BrowserSession, _detect_default_browser(), _find_exe_windows(), _find_opera_windows(), _firefox_profile_dir(), _normalize_url(), _open_native(), Bare words like "instagram" → "https://instagram.com" Domains like… (+11 more)

### Community 18 - "computer_control.py"
Cohesion: 0.14
Nodes (30): _base_dir(), _clear_field(), _click(), _clipboard_get(), _clipboard_paste(), computer_control(), _drag(), _focus_window() (+22 more)

### Community 19 - "dev_agent.py"
Cohesion: 0.12
Nodes (27): _build_project(), _classify_error(), _extract_culprit_script(), _fix_files(), _get_model(), _has_error(), _install_dependencies(), _is_rate_limit() (+19 more)

### Community 20 - "pathlib"
Cohesion: 0.09
Nodes (26): Daily Brief Action for ALFRED Mark-LIV. Provides the ultimate morning and daily…, concurrent_futures, core/cache.py — Centralized Caching Layer for ALFRED Mark-II. Provides high-…, Push-to-talk — hold a key, speak, release. Why this exists ---------------…, _available(), install_for_config(), _pip(), MARK XL — Dependency auto-installer. Called automatically on first launch and… (+18 more)

### Community 21 - "memory_manager.py"
Cohesion: 0.12
Nodes (26): Update Daily Briefing Preferences Action for ALFRED Mark-LIV. Permanently…, all_entries_for_ui(), _empty_memory(), _entry_value(), forget(), get_base_dir(), load_memory(), pop_last_session() (+18 more)

### Community 22 - "get_llm_settings"
Cohesion: 0.13
Nodes (20): call_llm(), call_llm_stream(), _do_stream(), call_llm_text(), check_model_available(), ensure_ollama_running(), get_llm_provider(), get_llm_settings() (+12 more)

### Community 23 - "EchoGuard"
Cohesion: 0.08
Nodes (14): band_energies(), EchoGuard, ndarray, Classifies microphone blocks while the assistant is speaking. Usage:…, True once the estimate rests on enough real echo to be trusted., Residual left by this room's own echo. Higher = harder to separate., False when the acoustics are too poor to judge on content alone. Speakers…, The residual a block must clear right now to count as a voice. (+6 more)

### Community 24 - "🦇 ALFRED — MARK II (Wayne Protocol Edition)"
Cohesion: 0.08
Nodes (25): ⚡ 10. Quick Start & Installation, 🔧 11. Configuration Reference (`config/api_keys.json`), 📊 12. Knowledge Graph (`graphify`), 🛠️ 13. Bug Fixes & System Patches, 👤 14. Author & Credits, 🖥️ 1. 100% Local & Air-Gapped Offline Execution, 1. Prerequisites, 2. Setup & Execution (+17 more)

### Community 25 - "JarvisUI"
Cohesion: 0.05
Nodes (18): JarvisUI, Update application and window icon in realtime., Thread-safe: raise the irreversible-action gate. Called from action handlers…, Thread-safe: take the gate down., Thread-safe: feed a 0.0–1.0 live audio level to the HUD waveform. Called from…, Ask the avatar to look somewhere for a moment (see HoloAvatar.glance)., Thread-safe: post a schedule of (level, openness, width) mouth frames for…, Thread-safe: wipe the on-screen conversation chat feed. (+10 more)

### Community 26 - "config_manager.py"
Cohesion: 0.12
Nodes (23): ensure_config_dir(), get_base_dir(), get_brief_enabled(), get_gemini_key(), is_configured(), Path, Read-modify-write one key without disturbing the rest of the config., Merge `values` into a namespace's stored config (read-modify-write, like every… (+15 more)

### Community 27 - "PluginSettingsOverlay"
Cohesion: 0.17
Nodes (6): QPushButton, QVBoxLayout, PluginManagerOverlay, PluginSettingsOverlay, Floating overlay — lists discovered plugins with per-plugin ON/OFF toggles., Floating overlay — renders per-plugin settings forms. Fully generic: it…

### Community 28 - "tech_font"
Cohesion: 0.12
Nodes (10): _row(), CapabilitiesOverlay, Floating glassmorphic overlay displaying a categorized directory of everything…, Floating overlay — QR code for instant phone pairing + manual key fallback., Call from any thread when a phone successfully connects., RemoteKeyOverlay, _lbl(), SetupOverlay (+2 more)

### Community 29 - "action_loader.py"
Cohesion: 0.11
Nodes (17): ActionRecord, ActionRegistry, _call_handler(), discover_actions(), _is_heavenly_restricted_params(), _opt_upper(), Path, Action discovery, validation, and dispatch — the built-in twin of… (+9 more)

### Community 30 - "audio_devices.py"
Cohesion: 0.12
Nodes (20): configure(), _display_name(), _is_pseudo(), list_devices(), prefetch(), _work(), _query(), _collect() (+12 more)

### Community 32 - "screen_processor.py"
Cohesion: 0.15
Nodes (19): _base_dir(), _capture_camera(), _cv2_backend(), _detect_camera_index(), _get_camera_index(), _get_os(), _load_config(), _probe_camera() (+11 more)

### Community 33 - "send_message.py"
Cohesion: 0.23
Nodes (20): _base_dir(), _clear_and_paste(), _desktop_send(), _get_os(), _open_app(), _open_browser_url(), _paste_text(), Path (+12 more)

### Community 34 - "_tlog"
Cohesion: 0.11
Nodes (15): _clean_transcript(), _is_repeat_chunk(), broadcast_progress(), _run_tool_bounded(), _deliver_news(), main(), runner(), Announce background completion ensuring ALFRED does not talk over active speech. (+7 more)

### Community 35 - "is_heavenly_restricted"
Cohesion: 0.09
Nodes (30): apply_heal_patch(), dev_agent(), _diagnose_trace(), heal_execution_error(), _heuristic_repair(), Parses stderr and stack traces to isolate error category, line number, and…, Attempts fast, deterministic rule-based fixes for standard syntax and import…, r""" Automated diagnostic and self-repair engine for tool and script execution… (+22 more)

### Community 36 - "capture_screen"
Cohesion: 0.12
Nodes (12): capture_screen(), _compress(), format_visual_payload(), Prepares the visual frame payload dictionary for the Gemini Live API…, Captures primary or specified monitor, queries active OS window context,…, Default entry point used by main.py., Verifies system falls back to 'App: Unknown' without raising exceptions., Verification Requirement: Verify [WINDOW_CONTEXT] header contains VS Code and… (+4 more)

### Community 37 - "audio_ducker.py"
Cohesion: 0.12
Nodes (16): _duck_linux(), duck_media_apps(), _worker(), _duck_windows(), is_ducked(), Process-level Audio Ducking for ALFRED. Automatically ducks background media…, Execute unducking on Windows via pycaw, restoring exact prior volume levels., Execute ducking on Linux via pulsectl. (+8 more)

### Community 38 - "intel_notes.py"
Cohesion: 0.31
Nodes (8): _auto_detect_type(), _config_dir(), intel_notes(), _load_notes(), Path, actions/intel_notes.py — Dedicated Intel & Notes Terminal Action. Provides a…, Action handler called by Gemini / action_loader., _save_notes()

### Community 39 - "get_plugin_enabled"
Cohesion: 0.11
Nodes (17): _call_run(), discover_plugins(), _load_error(), _opt_upper(), PluginRecord, PluginRegistry, Exception, Path (+9 more)

### Community 40 - "._build_app"
Cohesion: 0.23
Nodes (7): _auth(), clear_chat_ep(), list_files(), revoke_devices(), _safe_filename(), upload_file(), wake_ep()

### Community 41 - "TestBackgroundWorkerPool"
Cohesion: 0.12
Nodes (7): Verify that calling interrupt() sets halt event, immediately stops active…, Verify that _safe_background_announce waits until ALFRED finishes speaking…, Verify DashboardServer tracks background tasks and exposes them via endpoint., Verify queue_background_task is registered in TOOL_DECLARATIONS., Verify that queue_background_task returns immediately (sub-millisecond), and…, Dispatch a mock task and verify voice PTT interaction continues with sub-second…, TestBackgroundWorkerPool

### Community 42 - "load_api_keys"
Cohesion: 0.10
Nodes (18): The optional knobs, kept apart so one bad field can be dropped wholesale. Every…, get_app_icon(), get_assistant_name(), get_hud_style(), get_media_resolution(), get_thinking_enabled(), get_turn_tuning(), get_user_name() (+10 more)

### Community 43 - "daily_brief"
Cohesion: 0.25
Nodes (8): daily_brief(), _get_greeting(), _get_reminders_brief(), _get_system_vitals(), Check scheduled reminders in ~/.alfred/reminders or ~/.jarvis/reminders., Inspect core CPU, RAM, and Battery vitals., Executes the daily briefing and delivers spoken synthesis., Generate time-contextual executive salutation.

### Community 44 - "desktop.py"
Cohesion: 0.25
Nodes (16): _ask_gemini_for_desktop_action(), _build_sandbox(), clean_desktop(), desktop_control(), _execute_generated_code(), _get_api_key(), _get_base_dir(), get_current_wallpaper() (+8 more)

### Community 45 - "MemoryOverlay"
Cohesion: 0.33
Nodes (4): MemoryOverlay, Everything ALFRED has stored about you, and when it learned it. Memory used to…, Take every item out of the layout and detach it from the widget tree in this…, Size the panel to its content, re-centre it, and repaint what the old size…

### Community 46 - "background_monitor.py"
Cohesion: 0.23
Nodes (13): add_monitor(), check_all(), _is_blocked(), list_monitors(), _load(), BackgroundMonitor — user-configured topic watching. Checks DDG news once per…, Run all pending topic checks (once per day per topic). Returns a list of…, remove_monitor() (+5 more)

### Community 47 - "computer_settings"
Cohesion: 0.12
Nodes (16): brightness_get(), brightness_set(), computer_settings(), dark_mode(), press_key(), Current brightness 0-100, or None where it cannot be read., Set brightness to an absolute percentage. Only used to restore a value captured…, Current master volume 0-100, or None if this platform will not say. Undo needs… (+8 more)

### Community 48 - "main.py"
Cohesion: 0.07
Nodes (29): ProactiveEngine 2.0 — context-aware, time-aware, non-repetitive background…, _capture_screen(), asyncio, base64, get_base_dir(), Path, Local LLM client for MARK XL. Supports two backends — selected via…, _make_uploads_dir() (+21 more)

### Community 49 - "PushToTalk"
Cohesion: 0.20
Nodes (5): PushToTalk, Begin watching. Returns the scope actually achieved., Feed a press/release from a Qt shortcut (non-Windows, or no hook)., Calls `on_change(held: bool)` whenever the chord is pressed or released. Start…, global' once a system-wide hook is running, else 'window'.

### Community 50 - "FileDropZone"
Cohesion: 0.11
Nodes (5): QDragEnterEvent, QDropEvent, CyberGraphicLineButton, FileDropZone, Tactical button rendered strictly with vector graphic lines, sharp 2px border…

### Community 51 - "system_monitor.py"
Cohesion: 0.18
Nodes (11): _get_cpu_temp(), _get_gpu_usage(), get_system_status(), _nvml_gpu(), System Monitor — background metric checks with voice alert support. Zero…, Snapshot of current system metrics for the system_status tool., Stateful monitor — cooldown state persists across session reconnections. Call…, GPU utilisation via NVML — zero subprocess on all platforms. (+3 more)

### Community 52 - "_HudOverlay"
Cohesion: 0.13
Nodes (7): AudioDeviceOverlay, ConfirmBanner, _HudOverlay, Base for the floating panels placed by hand over the HUD. They are children of…, The gate in front of an action that cannot be taken back. The old confirmation…, Choose which microphone ALFRED listens to and which speakers it uses. Both…, Place a floating overlay in the middle of the HUD and show it.

### Community 53 - "test_cache.py"
Cohesion: 0.22
Nodes (10): _get_live_weather(), Fetch live weather conditions without opening an external browser., Permanently saves daily briefing preferences into long-term memory., update_daily_briefing(), get_cache(), Returns the centralized cache client singleton., patch, tests/test_cache.py — Comprehensive Test Suite for CentralizedCache. Tests: -… (+2 more)

### Community 54 - ".run"
Cohesion: 0.12
Nodes (12): BaseException, _get_api_key(), _is_reconnect_signal(), _do_shutdown(), _keep_context_of(), Summarise the current session in 1-2 sentences and save to long_term.json., Background task: voice alerts when metrics exceed thresholds., Check user-configured topics once per day; speak alerts when new headlines… (+4 more)

### Community 56 - "._build_config"
Cohesion: 0.15
Nodes (12): LiveConnectConfig, _describe_limits(), _describe_tools(), _load_system_prompt(), One line per capability, straight from the live tool declarations. Derived…, The other half of self-knowledge: what is out of reach, and why. Derived from…, Fill {tokens} in the prompt template. A plain replace rather than str.format:…, _render_prompt() (+4 more)

### Community 57 - "get_push_to_talk_enabled"
Cohesion: 0.25
Nodes (5): chord_label(), Human-readable name of the chord, for the UI and the logs., get_push_to_talk_enabled(), Hold-a-key-to-speak. When on, the mic is closed unless the chord is held., Repaint the push-to-talk row from the saved setting.

### Community 58 - "ui.py"
Cohesion: 0.15
Nodes (16): Holographic AI head for the HUD centre — the thing that used to be a ring stack…, math, get_input_device(), get_output_device(), _patch_config(), Read-modify-write one or more keys in api_keys.json. Every setter in this file…, Microphone device name, or '' for the system default., Speaker device name, or '' for the system default. (+8 more)

### Community 59 - "numpy"
Cohesion: 0.25
Nodes (5): Speech-to-Text engines for MARK XL. Whisper – offline transcription via faster-…, Streaming transcription using Vosk., Feed raw int16 LE PCM bytes. Returns (text, is_final)., VoskSTT, numpy

### Community 61 - "._build_jarvis_icon"
Cohesion: 0.22
Nodes (4): Render an ALFRED tactical icon at 4× resolution and downsample for crisp…, Create a Windows .lnk shortcut WITHOUT launching PowerShell or cmd. Tries…, Resolve the user's REAL desktop directory instead of assuming ~/Desktop, which…, Create a desktop shortcut on Windows / macOS / Linux. Never opens a terminal,…

### Community 62 - "save_app_icon"
Cohesion: 0.20
Nodes (10): Update App Icon Action for ALFRED Mark-LIV. Switches the application window,…, Updates the main application icon and taskbar badge in realtime., update_app_icon(), Save the chosen app icon setting to config., save_app_icon(), format_icon_display_name(), get_available_app_icons(), Format an icon file name into an authentic, sleek tactical insignia title. (+2 more)

### Community 63 - "TacticalAudioPlayerWidget"
Cohesion: 0.14
Nodes (5): QFrame, Sleek tactical cyber popup for adjusting master background music volume.…, Bottom-Left Cyber Tactical Audio Player Widget. Styled matching the HUD /…, TacticalAudioPlayerWidget, _VolumeSliderPopup

### Community 64 - "undo.py"
Cohesion: 0.10
Nodes (20): bind(), _log(), _Pending, core/confirm.py — a confirmation the model cannot forge. THE PROBLEM WITH THE…, Called by the UI when the user presses CONFIRM or CANCEL. Runs the stored…, Wire this module to the HUD. Called once from main.py at startup., Park an irreversible action behind the on-screen gate. Returns the sentence the…, request() (+12 more)

### Community 66 - "viseme.py"
Cohesion: 0.24
Nodes (9): collections, coverage(), Text → mouth shape, fused with the audio the avatar is actually speaking. Why…, Reduce any character to a bare Latin letter, or "" if it has none. This is what…, Fraction of the letters in `text` we can reduce to a Latin sound., Split a line of speech into (viseme, duration-weight) pairs. Returns [] for…, text_to_visemes(), to_latin() (+1 more)

### Community 67 - "_SysMetrics"
Cohesion: 0.21
Nodes (4): Thread-safe speech channel for plugins: lets a plugin ask JARVIS to say…, _nvml_gpu_windows(), Return NVIDIA GPU utilisation % using nvml.dll directly — zero subprocess., _SysMetrics

### Community 68 - "._apply_name_update"
Cohesion: 0.15
Nodes (10): apply_ui_accent(), current_palette(), Read api_keys.json config dict. Returns {} on any error., Applies DOSSIER CRT [A-34] (#8e9bff), VECTOR CRT [WAKU] (#a8ff3e), or BATMAN…, A snapshot of the accent-linked colours currently on class C., LIVE full theme change. Replaces the old palette colours with the new ones in…, Live preview — paints the whole interface the new colour (does NOT write to…, Update all name/theme-dependent UI elements and persist to config. (+2 more)

### Community 69 - ".broadcast"
Cohesion: 0.32
Nodes (6): auto_login(), device_login_ep(), login(), phone_audio_ws(), _derive_key(), SHA-256(sessionKey‖salt) → 32-byte AES-256 key (microseconds, no PBKDF2 needed).

### Community 71 - "WakeWordDetector"
Cohesion: 0.17
Nodes (5): Runs the wake model in a dedicated thread. The mic thread calls feed() with raw…, Load the model and spawn the inference thread. Returns True on success. Safe to…, Called from the mic callback (real-time thread). Must stay cheap and never…, WakeWordDetector, Load the detector once (model loads on first start). Idempotent.

### Community 72 - "setup.py"
Cohesion: 0.36
Nodes (7): _check_assets(), _check_python(), main(), MARK LIV — one-time setup. Installs the Python dependencies for THIS operating…, Fail immediately and clearly rather than deep inside a pip resolver. A wrong…, The avatar's face is a shipped file; a truncated clone should say so., _run()

### Community 73 - "VisemeStream"
Cohesion: 0.29
Nodes (3): Fuses the transcript's shape sequence onto the audio's timing. Thread note:…, Blend audio frames [(level, openness, width)] with the text queue., VisemeStream

### Community 74 - "get_active_window_info"
Cohesion: 0.20
Nodes (10): get_active_window_context(), get_active_window_info(), _get_linux_window_info(), _get_macos_window_info(), _get_windows_window_info(), Query foreground window handle, title, and process name on Windows., Query active frontmost window on macOS via Quartz or AppleScript fallback., Query active window on Linux via xdotool or wmctrl. (+2 more)

### Community 75 - "_trim_to_limit"
Cohesion: 0.28
Nodes (6): _all_entries(), _trim_to_limit(), Measures execution time for 50,000 mock records. Under the old O(N^2)…, Preserves all items when memory is already below limit., Handles empty memory structure gracefully., TestMemoryTrimBenchmark

### Community 76 - "_DropCanvas"
Cohesion: 0.25
Nodes (3): _DropCanvas, _file_category(), _fmt_size()

### Community 77 - "ScreenCapturePayload"
Cohesion: 0.25
Nodes (3): Hybrid return payload for screen captures. - Behaves as a 3-tuple `(img_bytes,…, ScreenCapturePayload, tuple

### Community 78 - "unduck_media_apps"
Cohesion: 0.24
Nodes (7): Restore ducked media applications to their exact original volume levels. :param…, unduck_media_apps(), _pcm_level(), _pcm_visemes(), Stop JARVIS mid-speech: drain queued audio and open mic immediately., Map a block of int16 PCM samples to a 0.0–1.0 loudness level for the HUD…, Slice a PCM block into (level, openness, width) frames, one per 20 ms. Returns…

### Community 79 - "LogWidget"
Cohesion: 0.25
Nodes (3): QTextEdit, LogWidget, Cancel any in-flight typing animation, drain the queue, and clear the display.

### Community 80 - "._apply_ptt_shortcut"
Cohesion: 0.29
Nodes (5): qt_sequence(), The same chord as a QKeySequence string., _press(), Bind the chord inside the window when no global hook is available. On macOS and…, Report a windowed press/release to whoever owns the microphone.

### Community 81 - ".test_error_isolation_in_concurrent_tasks"
Cohesion: 0.29
Nodes (5): Verify that an exception in one concurrent task does not break or cancel…, Verify that a batch of tasks run with a concurrency limit of 5 scales sub-…, TestConcurrencyLimiter, execute_task(), safe_run()

### Community 82 - ".__init__"
Cohesion: 0.40
Nodes (4): index(), _local_ip(), Return the best LAN-facing IPv4 address, no internet required., _read()

### Community 83 - "_ensure_network_access"
Cohesion: 0.20
Nodes (5): _ensure_certs(), _ensure_network_access(), Cross-platform, best-effort: open port in the OS firewall for LAN access. Runs…, Make sure config/certs holds a TLS key pair, generating a self-signed one the…, Second HTTPS server on PORT+1 sharing the same app and in-memory state. Chrome…

### Community 84 - "TestAudioDucker"
Cohesion: 0.29
Nodes (4): patch, Verify that duck_media_apps lowers target media processes by 70% (0.3 factor),…, Verify Linux pulsectl ducking fallback logic., TestAudioDucker

### Community 85 - ".__init__"
Cohesion: 0.11
Nodes (10): ProactiveEngine, Decides when ALFRED should speak unprompted and builds a context-rich prompt.…, Build a context snapshot for Gemini. Rotates through three focus areas so…, _Popen, Exception, Raised inside the session TaskGroup to force a clean, voluntary reconnect (e.g.…, Session-scoped task: when a voluntary reconnect is requested, raise a signal…, Turn hold-to-talk on or off. Returns the scope actually achieved. (+2 more)

### Community 86 - "_news"
Cohesion: 0.29
Nodes (7): _format_news(), _news(), _ddg_attempt(), DDG first, Gemini as backup, with 15-minute caching to protect quota., Run fn() in a daemon thread; return its result, or None if it overruns., _run_bounded(), _run()

### Community 87 - ".__init__"
Cohesion: 0.11
Nodes (6): ClipboardPanel, _EqualizerBarsWidget, Tactical Dossier Card Widget (Screenshot 1: Exact recreation of SUBJECT A-34…, Mini animated cyber audio wave visualizer., Floating panel shown when text is copied — offers quick Alfred actions., SubjectDossierCard

### Community 88 - "_detect_action"
Cohesion: 0.40
Nodes (5): _detect_action(), _normalise(), Resolve a free-text description to an action name, locally. Returns {"action":…, What to tell the model when nothing matched. Names real actions so its retry…, _suggest()

### Community 89 - ".request_reconnect"
Cohesion: 0.33
Nodes (3): Thread-safe: ask the run loop to tear down and rebuild the Live session. Called…, Voice picker applied. The voice is baked into the session at connect time, so a…, Microphone or speaker changed. Both streams are opened inside the session…

### Community 94 - "._decrypt"
Cohesion: 0.40
Nodes (4): command(), ws_ep(), _decrypt_cbc(), Decrypt base64(IV[16] ‖ ciphertext) with AES-256-CBC + PKCS7.

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

### Community 102 - "WhisperSTT"
Cohesion: 0.33
Nodes (4): ndarray, Offline transcription using faster-whisper., Transcribe a float32 mono 16 kHz numpy array. Returns transcript string., WhisperSTT

### Community 109 - "format_window_context"
Cohesion: 0.50
Nodes (3): format_window_context(), Format the standard metadata block: [WINDOW_CONTEXT] App: <Name> | Title:…, Verifies exact string formatting requirements.

### Community 111 - "._listen_audio"
Cohesion: 0.50
Nodes (3): callback(), _open_mic(), True while the speakers may still be finishing our last sentence.

### Community 123 - "get_plugin_config"
Cohesion: 0.50
Nodes (4): get_plugin_config(), get_plugin_setting(), All stored values for a namespace (empty dict if none set yet)., A single value from a namespace, or `default` if unset.

## Knowledge Gaps
- **35 isolated node(s):** `C`, `Purpose`, `Rules`, `Purpose`, `Rules` (+30 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 839 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **21 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `MainWindow` connect `MainWindow` to `config_manager.py`, `._apply_name_update`, `._wake_state`, `_DropCanvas`, `mono_font`, `._apply_ptt_shortcut`, `_HudOverlay`, `.clear_chat`, `setter`, `.__init__`, `get_push_to_talk_enabled`, `ui.py`, `tech_font`, `._build_jarvis_icon`, `save_app_icon`?**
  _High betweenness centrality (0.067) - this node is a cross-community bridge._
- **Why does `JarvisUI` connect `JarvisUI` to `_tlog`, `._apply_name_update`, `._wake_state`, `main.py`, `JarvisLive`, `._apply_ptt_shortcut`, `.__init__`, `.__init__`, `setter`, `get_push_to_talk_enabled`, `ui.py`, `.clear_chat`?**
  _High betweenness centrality (0.057) - this node is a cross-community bridge._
- **Why does `JarvisLive` connect `JarvisLive` to `EchoGuard`, `JarvisUI`, `_tlog`, `TestBackgroundWorkerPool`, `load_api_keys`, `background_monitor.py`, `main.py`, `PushToTalk`, `system_monitor.py`, `.run`, `._build_config`, `DashboardServer`, `_SysMetrics`, `WakeWordDetector`, `VisemeStream`, `unduck_media_apps`, `.__init__`, `.request_reconnect`, `._listen_audio`?**
  _High betweenness centrality (0.057) - this node is a cross-community bridge._
- **Are the 9 inferred relationships involving `JarvisLive` (e.g. with `ProactiveEngine` and `SystemMonitor`) actually correct?**
  _`JarvisLive` has 9 INFERRED edges - model-reasoned connections that need verification._
- **What connects `C`, `Purpose`, `Rules` to the rest of the system?**
  _35 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `game_updater.py` be split into smaller, more focused modules?**
  _Cohesion score 0.054945054945054944 - nodes in this community are weakly interconnected._
- **Should `code_helper.py` be split into smaller, more focused modules?**
  _Cohesion score 0.07402597402597402 - nodes in this community are weakly interconnected._