# Graph Report - Alfred-Mark-III  (2026-09-26)

## Corpus Check
- 94 files · ~182,909 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 16 file(s) not represented in the graph (top: .ico 7, (none) 3, .bak 2)

## Summary
- 2350 nodes · 4603 edges · 125 communities (94 shown, 31 thin omitted)
- Extraction: 96% EXTRACTED · 4% INFERRED · 0% AMBIGUOUS · INFERRED: 181 edges (avg confidence: 0.87)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `e53b55f4`
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
- protocol_engine.py
- qcol
- KokoroTTSEngine
- CentralizedCache
- web_search.py
- mono_font
- gmail_manager.py
- ClipboardManager
- JarvisLive
- _BrowserSession
- computer_control.py
- dev_agent.py
- ui.py
- memory_manager.py
- llm_client.py
- EchoGuard
- ALFRED — MARK III (Wayne Protocol Edition)
- JarvisUI
- config_manager.py
- PluginSettingsOverlay
- tech_font
- plugin_loader.py
- audio_devices.py
- crypto-js.min.js
- screen_processor.py
- desktop.py
- _tlog
- is_heavenly_restricted
- action_loader.py
- load_api_keys
- PushToTalk
- GraphManager
- ._build_app
- TestBackgroundWorkerPool
- doc_rag.py
- TelemetryHUD
- browser_control.py
- MemoryOverlay
- background_monitor.py
- computer_settings
- main.py
- find_element
- TestProtocolEngine
- system_monitor.py
- get_input_device
- daily_brief.py
- .run
- ._wake_state
- cache.py
- _SessionRegistry
- clipboard_manager.py
- stt.py
- NotesTerminalWidget
- create_protocol
- pathlib
- confirm.py
- datetime
- DashboardServer
- VisemeStream
- _SysMetrics
- ._apply_name_update
- .broadcast
- ._build_config
- WakeWordDetector
- setter
- _gemini_grounding
- installer.py
- json
- .__init__
- sys
- unduck_media_apps
- LogWidget
- ._apply_ptt_shortcut
- .test_error_isolation_in_concurrent_tasks
- server.py
- _ensure_network_access
- TestAudioDucker
- .__init__
- ._launch
- SystemMonitor
- _detect_action
- CapabilitiesOverlay
- ClipboardPanel
- ._toggle_sentry_mode
- _RootShim
- .clear_chat
- _unduck_linux
- Daily Brief Protocol
- Email Handling Rules
- Executive Assistant Persona & Behavioral Standards
- /email-triage Workflow
- _template.py
- _get_base_dir
- Graphify + Antigravity Project Workflow & Setup Guide
- /deep-work Workflow
- _get_macos_wifi_interface
- type_text
- rules/graphify.md
- workflows/graphify.md
- audio_ws
- .add_intel_note
- .glance
- ._listen_audio
- weather_report.py
- .hide_confirm
- .hide_quiz
- .push_visemes
- .show_camera_frame
- screen_find.py
- .show_quiz
- .show_review

## God Nodes (most connected - your core abstractions)
1. `MainWindow` - 92 edges
2. `JarvisLive` - 60 edges
3. `JarvisUI` - 45 edges
4. `tech_font()` - 35 edges
5. `mono_font()` - 35 edges
6. `_BrowserSession` - 32 edges
7. `is_heavenly_restricted()` - 26 edges
8. `TronScoreBackgroundPlayer` - 26 edges
9. `qcol()` - 25 edges
10. `computer_control()` - 24 edges

## Surprising Connections (you probably didn't know these)
- `3. Dedicated Intel & Notes Terminal (`intel_notes`)` --references--> `intel_notes()`  [INFERRED]
  .agents/rules/file_exploration.md → actions/intel_notes.py
- `Steps` --references--> `computer_control()`  [INFERRED]
  .agents/workflows/deep_work.md → actions/computer_control.py
- `2. Security, Privacy & Defensive Architecture` --references--> `computer_control()`  [INFERRED]
  readme.md → actions/computer_control.py
- `1. File Opening (`open`)` --references--> `file_controller()`  [INFERRED]
  .agents/rules/file_exploration.md → actions/file_controller.py
- `2. Folder Exploration (`explore`)` --references--> `file_controller()`  [INFERRED]
  .agents/rules/file_exploration.md → actions/file_controller.py

## Import Cycles
- None detected.

## Communities (125 total, 31 thin omitted)

### Community 0 - "game_updater.py"
Cohesion: 0.06
Nodes (79): browser_control(), _build_google_flights_url(), flight_finder(), _format_spoken(), _format_text_report(), _get_base_dir(), _parse_date(), _parse_flights_with_gemini() (+71 more)

### Community 1 - "code_helper.py"
Cohesion: 0.08
Nodes (48): _build(), _clean_code(), code_helper(), _detect_intent(), _edit_action(), _explain_action(), _fix_code(), _get_gemini() (+40 more)

### Community 2 - "MainWindow"
Cohesion: 0.05
Nodes (12): QMainWindow, MainWindow, Read api_keys.json config dict. Returns {} on any error., Slot — display camera preview overlay (main thread)., Floating overlay panel shown when the ⚙ header button is toggled., Slot — runs on Qt main thread. Updates and shows the content panel., Slot — Qt main thread. Lays a document review into the content panel., Slot — Qt main thread. Puts a fresh quiz on the board. (+4 more)

### Community 3 - "file_processor.py"
Cohesion: 0.08
Nodes (45): _detect_type(), file_processor(), _file_size_str(), _gemini_client(), _output_path(), _process_archive(), _process_audio(), _process_code() (+37 more)

### Community 4 - "file_controller.py"
Cohesion: 0.07
Nodes (63): copy_file(), create_file(), create_folder(), delete_file(), explore_folder(), file_controller(), find_files(), _format_size() (+55 more)

### Community 5 - "TronScoreBackgroundPlayer"
Cohesion: 0.05
Nodes (16): QFrame, QObject, _base_dir(), Path, Background music audio engine. Plays background score continuously on loop…, Set base normal volume (0.0 to 1.0). Speech ducking scales to 50% of base., Sleek tactical cyber popup for adjusting master background music volume.…, Bottom-Left Cyber Tactical Audio Player Widget. Styled matching the HUD /… (+8 more)

### Community 6 - "CustomizeOverlay"
Cohesion: 0.05
Nodes (14): QDragEnterEvent, QDropEvent, QPointF, QRectF, CustomizeOverlay, _lbl(), CyberGraphicLineButton, FileDropZone (+6 more)

### Community 8 - "protocol_engine.py"
Cohesion: 0.17
Nodes (22): execute_protocol(), _execute_tool(), get_action_registry(), interpolate_variables(), _is_failure(), list_protocols(), load_protocols(), match_trigger() (+14 more)

### Community 9 - "qcol"
Cohesion: 0.08
Nodes (19): QColor, QPainter, QPixmap, HudCanvas, qcol(), Thread-safe entry point for the audio threads. Stores the louder of the…, Pre-render the static grid-dot background into a transparent pixmap so…, True only when this canvas can actually be seen by the user. (+11 more)

### Community 10 - "KokoroTTSEngine"
Cohesion: 0.06
Nodes (22): _compress_silence(), create_tts_player(), EdgeTTSEngine, ElevenLabsTTSEngine, _import_kokoro_pipeline(), KokoroTTSEngine, _synth(), _play_audio_bytes() (+14 more)

### Community 11 - "CentralizedCache"
Cohesion: 0.06
Nodes (22): CentralizedCache, _canonicalize(), decorator(), wrapper(), Any, Stores value in cache with TTL. Fails open gracefully if storage fails., Deletes a key from cache. Fails open gracefully., Invalidates all keys starting with prefix. Useful for mutation hooks. (+14 more)

### Community 12 - "web_search.py"
Cohesion: 0.10
Nodes (36): _compare(), _fetch_item(), _ddg_news(), _ddg_search(), _format_ddg(), _format_news(), _gemini_available(), _gemini_headlines() (+28 more)

### Community 13 - "mono_font"
Cohesion: 0.06
Nodes (19): QFont, BiometricFingerprintWidget, _CameraPreview, CRTReconWidget, _EqualizerBarsWidget, _fl(), MetricBar, mono_font() (+11 more)

### Community 14 - "gmail_manager.py"
Cohesion: 0.12
Nodes (21): _clean_header_str(), _extract_body_snippet(), fetch_unread_emails(), gmail_manager(), _load_gmail_creds(), Any, Gmail Manager Action for ALFRED Mark-LIV. Provides full Gmail connectivity: -…, Send an email using Gmail SMTP SSL. (+13 more)

### Community 15 - "ClipboardManager"
Cohesion: 0.10
Nodes (17): ClipboardManager, cosine_similarity(), _get_active_window_info(), Any, Compute cosine similarity between two float vectors., Thread-safe persistent clipboard manager with semantic indexing., Lazily initialize local fastembed model., Compute 384-dimensional vector embedding for text. (+9 more)

### Community 16 - "JarvisLive"
Cohesion: 0.10
Nodes (10): JarvisLive, Chord pressed or released — may arrive on the hotkey thread., Called from the detector thread when 'Hey Jarvis' is heard., Auto-sleep after the configured silence window (wake-word mode only)., Enable/disable wake word from the settings UI. Returns a status token:…, Manual sleep/wake button in the UI., Download openwakeword + the model (runs in a UI worker thread)., Called from Qt main thread when user presses Remote Control. (+2 more)

### Community 18 - "computer_control.py"
Cohesion: 0.18
Nodes (26): _base_dir(), _clear_field(), _click(), _clipboard_get(), _clipboard_paste(), computer_control(), _drag(), _focus_window() (+18 more)

### Community 19 - "dev_agent.py"
Cohesion: 0.07
Nodes (47): apply_heal_patch(), _build_project(), _classify_error(), dev_agent(), _diagnose_trace(), _extract_culprit_script(), _fix_files(), _get_model() (+39 more)

### Community 20 - "ui.py"
Cohesion: 0.15
Nodes (13): core_avatar, get_brief_enabled(), get_wake_word_enabled(), Whether local wake-word gating is on (assistant sleeps until 'Hey Jarvis')., save_brief_enabled(), psutil, pyqt6_qtcore, pyqt6_qtgui (+5 more)

### Community 21 - "memory_manager.py"
Cohesion: 0.09
Nodes (33): Build a context snapshot for Gemini. Rotates through three focus areas so…, Update Daily Briefing Preferences Action for ALFRED Mark-LIV. Permanently…, Permanently saves daily briefing preferences into long-term memory., update_daily_briefing(), _do_shutdown(), Summarise the current session in 1-2 sentences and save to long_term.json., all_entries_for_ui(), _empty_memory() (+25 more)

### Community 22 - "llm_client.py"
Cohesion: 0.13
Nodes (23): call_llm(), call_llm_stream(), _do_stream(), call_llm_text(), check_model_available(), ensure_ollama_running(), get_base_dir(), get_llm_provider() (+15 more)

### Community 23 - "EchoGuard"
Cohesion: 0.08
Nodes (14): band_energies(), EchoGuard, ndarray, Classifies microphone blocks while the assistant is speaking. Usage:…, True once the estimate rests on enough real echo to be trusted., Residual left by this room's own echo. Higher = harder to separate., False when the acoustics are too poor to judge on content alone. Speakers…, The residual a block must clear right now to count as a voice. (+6 more)

### Community 24 - "ALFRED — MARK III (Wayne Protocol Edition)"
Cohesion: 0.06
Nodes (33): 10. Local Hybrid Visual Grounding (RapidOCR + ONNX + Gemini Fallback), 11. Process-Level Audio Ducking & Background Concurrency, 13. Bug Fixes & Stability Updates, 14. System Architecture & File Structure, 15. Quick Start & Installation, 16. Configuration Reference (`config/api_keys.json`), 17. Knowledge Graph (`graphify`), 18. Author & Credits (+25 more)

### Community 25 - "JarvisUI"
Cohesion: 0.09
Nodes (8): JarvisUI, Update application and window icon in realtime., Thread-safe: raise the irreversible-action gate. Called from action handlers…, Thread-safe: feed a 0.0–1.0 live audio level to the HUD waveform. Called from…, Thread-safe: wipe the on-screen conversation chat feed., Thread-safe: clear the dedicated Notes Terminal., Thread-safe: display content in the panel below the HUD., Thread-safe: show the API key setup overlay (e.g. after an auth error).

### Community 26 - "config_manager.py"
Cohesion: 0.14
Nodes (21): ensure_config_dir(), get_base_dir(), get_gemini_key(), is_configured(), Path, Read-modify-write one key without disturbing the rest of the config., Merge `values` into a namespace's stored config (read-modify-write, like every…, Persist assistant name and user name to config. (+13 more)

### Community 27 - "PluginSettingsOverlay"
Cohesion: 0.14
Nodes (8): save_plugin_enabled(), QHBoxLayout, QPushButton, QVBoxLayout, PluginManagerOverlay, PluginSettingsOverlay, Floating overlay — lists discovered plugins with per-plugin ON/OFF toggles., Floating overlay — renders per-plugin settings forms. Fully generic: it…

### Community 28 - "tech_font"
Cohesion: 0.12
Nodes (10): _DropCanvas, _file_category(), _fmt_size(), Floating overlay — QR code for instant phone pairing + manual key fallback., Call from any thread when a phone successfully connects., RemoteKeyOverlay, _lbl(), SetupOverlay (+2 more)

### Community 29 - "plugin_loader.py"
Cohesion: 0.10
Nodes (22): _call_run(), discover_plugins(), _load_error(), _opt_upper(), PluginRecord, PluginRegistry, Exception, Path (+14 more)

### Community 30 - "audio_devices.py"
Cohesion: 0.12
Nodes (18): configure(), _display_name(), _is_pseudo(), prefetch(), _work(), _query(), _collect(), core/audio_devices.py — pick which microphone and which speakers ALFRED uses.… (+10 more)

### Community 32 - "screen_processor.py"
Cohesion: 0.05
Nodes (48): _base_dir(), _capture_camera(), capture_screen(), _capture_screen(), _compress(), _cv2_backend(), _detect_camera_index(), format_visual_payload() (+40 more)

### Community 33 - "desktop.py"
Cohesion: 0.12
Nodes (36): _ask_gemini_for_desktop_action(), _build_sandbox(), clean_desktop(), desktop_control(), _execute_generated_code(), _get_api_key(), _get_base_dir(), get_current_wallpaper() (+28 more)

### Community 34 - "_tlog"
Cohesion: 0.10
Nodes (16): _clean_transcript(), _is_repeat_chunk(), broadcast_progress(), _run_tool_bounded(), _deliver_news(), main(), runner(), Queue a background task and return task metadata immediately. (+8 more)

### Community 35 - "is_heavenly_restricted"
Cohesion: 0.17
Nodes (12): _normalize(), open_app(), check_action_params(), check_path_access(), is_heavenly_restricted(), Any, core/path_guard.py — Centralized Path Security and Drive Access Control.…, Validate whether a given path is allowed to be accessed. Returns: (True, "") if… (+4 more)

### Community 36 - "action_loader.py"
Cohesion: 0.12
Nodes (15): ActionRecord, ActionRegistry, _call_handler(), discover_actions(), _is_heavenly_restricted_params(), _opt_upper(), Path, Action discovery, validation, and dispatch — the built-in twin of… (+7 more)

### Community 37 - "load_api_keys"
Cohesion: 0.10
Nodes (18): The optional knobs, kept apart so one bad field can be dropped wholesale. Every…, get_app_icon(), get_assistant_name(), get_hud_style(), get_media_resolution(), get_proactive_audio_enabled(), get_push_to_talk_enabled(), get_thinking_enabled() (+10 more)

### Community 38 - "PushToTalk"
Cohesion: 0.15
Nodes (7): chord_label(), PushToTalk, Begin watching. Returns the scope actually achieved., Feed a press/release from a Qt shortcut (non-Windows, or no hook)., Human-readable name of the chord, for the UI and the logs., Calls `on_change(held: bool)` whenever the chord is pressed or released. Start…, global' once a system-wide hook is running, else 'window'.

### Community 39 - "GraphManager"
Cohesion: 0.11
Nodes (14): GraphManager, Any, Path, Save the graph data to the JSON file atomically., Add an entity node to the graph. Returns True if successful., Add a relationship (edge) between two nodes. Returns True if successful., Apply exponential decay to all temporary nodes. Returns the number of nodes…, Query the knowledge graph for a concept and return connected subgraph up to… (+6 more)

### Community 40 - "._build_app"
Cohesion: 0.20
Nodes (8): _auth(), command(), list_files(), revoke_devices(), _safe_filename(), upload_file(), wake_ep(), ws_ep()

### Community 41 - "TestBackgroundWorkerPool"
Cohesion: 0.14
Nodes (6): Verify that calling interrupt() sets halt event, immediately stops active…, Verify that _safe_background_announce waits until ALFRED finishes speaking…, Verify queue_background_task is registered in TOOL_DECLARATIONS., Verify that queue_background_task returns immediately (sub-millisecond), and…, Dispatch a mock task and verify voice PTT interaction continues with sub-second…, TestBackgroundWorkerPool

### Community 42 - "doc_rag.py"
Cohesion: 0.07
Nodes (43): _ChangeHandler, _chunk_text(), crawl_and_index(), _delete_file_chunks(), _detokenize_tokens(), _extract_text_from_file(), _get_chroma_collection(), _get_embedding_model() (+35 more)

### Community 43 - "TelemetryHUD"
Cohesion: 0.13
Nodes (11): main(), QWidget, Set up the update timer., Set up system tray icon for control., Handle mouse press for dragging., Handle mouse move for dragging., Update all telemetry displays., Main entry point for the HUD widget. (+3 more)

### Community 44 - "browser_control.py"
Cohesion: 0.22
Nodes (11): _detect_default_browser(), _find_exe_windows(), _find_opera_windows(), _log(), _normalize_url(), _open_native(), Bare words like "instagram" → "https://instagram.com" Domains like…, Opens the user's REAL browser normally — with their own profile, logged-in… (+3 more)

### Community 45 - "MemoryOverlay"
Cohesion: 0.15
Nodes (8): ConfirmBanner, _HudOverlay, MemoryOverlay, Base for the floating panels placed by hand over the HUD. They are children of…, The gate in front of an action that cannot be taken back. The old confirmation…, Everything ALFRED has stored about you, and when it learned it. Memory used to…, Take every item out of the layout and detach it from the widget tree in this…, Size the panel to its content, re-centre it, and repaint what the old size…

### Community 46 - "background_monitor.py"
Cohesion: 0.29
Nodes (12): add_monitor(), check_all(), _is_blocked(), list_monitors(), _load(), BackgroundMonitor — user-configured topic watching. Checks DDG news once per…, Run all pending topic checks (once per day per topic). Returns a list of…, remove_monitor() (+4 more)

### Community 47 - "computer_settings"
Cohesion: 0.12
Nodes (16): brightness_get(), brightness_set(), computer_settings(), dark_mode(), press_key(), Current brightness 0-100, or None where it cannot be read., Set brightness to an absolute percentage. Only used to restore a value captured…, Current master volume 0-100, or None if this platform will not say. Undo needs… (+8 more)

### Community 48 - "main.py"
Cohesion: 0.06
Nodes (40): ProactiveEngine 2.0 — context-aware, time-aware, non-repetitive background…, asyncio, _duck_linux(), duck_media_apps(), _worker(), _duck_windows(), is_ducked(), Process-level Audio Ducking for ALFRED. Automatically ducks background media… (+32 more)

### Community 49 - "find_element"
Cohesion: 0.12
Nodes (14): _screen_find(), find_element(), is_icon_query(), Determine if target query is specifically targeting an icon/non-text element., Main entry point for local hybrid UI element grounding. 1. Executes RapidOCR on…, Action handler called by ALFRED action dispatcher., screen_find(), 6. Full Desktop Control & Operating System Automation (+6 more)

### Community 50 - "TestProtocolEngine"
Cohesion: 0.12
Nodes (7): Verify that a tool failure halts subsequent steps immediately., Verify voice trigger word resolution (e.g. 'FCC CLAUDE')., Verify protocol_engine TOOL action handler dispatching., Verification Requirement: Define test_protocol in protocols.yaml that opens…, Verify variable interpolation into strings, lists, and dicts., Verify that if any step is blocked by path restrictions, the engine aborts…, TestProtocolEngine

### Community 51 - "system_monitor.py"
Cohesion: 0.08
Nodes (35): _get_cpu_temp(), _get_gpu_usage(), get_system_status(), _is_private_or_loopback(), is_protected_process(), _nvml_gpu(), Any, actions/system_monitor.py — System Metric Checks, Process Tree Watchdog &… (+27 more)

### Community 52 - "get_input_device"
Cohesion: 0.16
Nodes (13): list_devices(), Device names for 'input' or 'output'. Falls back to a synchronous query if the…, get_input_device(), get_output_device(), _patch_config(), Read-modify-write one or more keys in api_keys.json. Every setter in this file…, Microphone device name, or '' for the system default., Speaker device name, or '' for the system default. (+5 more)

### Community 53 - "daily_brief.py"
Cohesion: 0.13
Nodes (17): daily_brief(), _get_gmail_brief(), _get_greeting(), _get_reminders_brief(), _get_system_vitals(), Daily Brief Action for ALFRED Mark-LIV. Provides the ultimate morning and daily…, Fetch unread emails summary via gmail_manager., Check scheduled reminders in ~/.alfred/reminders or ~/.jarvis/reminders. (+9 more)

### Community 54 - ".run"
Cohesion: 0.14
Nodes (10): BaseException, _get_api_key(), _is_reconnect_signal(), _keep_context_of(), Background task: voice alerts when metrics exceed thresholds., Check user-configured topics once per day; speak alerts when new headlines…, Background task: periodically checks if the user has been silent long enough,…, Forward phone mic PCM chunks from dashboard queue into the Gemini Live session. (+2 more)

### Community 56 - "cache.py"
Cohesion: 0.19
Nodes (10): _get_live_weather(), Fetch live weather conditions without opening an external browser., get_cache(), core/cache.py — Centralized Caching Layer for ALFRED Mark-II. Provides high-…, Returns the centralized cache client singleton., functools, patch, tests/test_cache.py — Comprehensive Test Suite for CentralizedCache. Tests: -… (+2 more)

### Community 57 - "_SessionRegistry"
Cohesion: 0.16
Nodes (4): Manages all active browser sessions., Is there an active automation session for this browser (or any)?, Returns the last natively-opened URL once (consumed to avoid repeats)., _SessionRegistry

### Community 58 - "clipboard_manager.py"
Cohesion: 0.08
Nodes (24): add_clipboard_item(), classify_content_type(), clipboard_manager_action(), get_recent_clipboards(), is_sensitive_content(), paste_clipboard_item(), actions/clipboard_manager.py — Persistent, Semantically Indexed Clipboard…, Determine category: url, email, json, code, or text. (+16 more)

### Community 59 - "stt.py"
Cohesion: 0.15
Nodes (8): ndarray, Speech-to-Text engines for MARK XL. Whisper – offline transcription via faster-…, Offline transcription using faster-whisper., Transcribe a float32 mono 16 kHz numpy array. Returns transcript string., Streaming transcription using Vosk., Feed raw int16 LE PCM bytes. Returns (text, is_final)., VoskSTT, WhisperSTT

### Community 61 - "create_protocol"
Cohesion: 0.18
Nodes (10): create_protocol(), _do_save(), get_protocols_file(), Path, Create a new workflow playbook and save to config/protocols.yaml. Supports…, Return path to config/protocols.yaml., Save macro definitions back to config/protocols.yaml., save_protocols() (+2 more)

### Community 62 - "pathlib"
Cohesion: 0.18
Nodes (11): Update App Icon Action for ALFRED Mark-LIV. Switches the application window,…, Updates the main application icon and taskbar badge in realtime., update_app_icon(), Save the chosen app icon setting to config., save_app_icon(), pathlib, format_icon_display_name(), get_available_app_icons() (+3 more)

### Community 63 - "confirm.py"
Cohesion: 0.25
Nodes (10): bind(), _log(), _Pending, core/confirm.py — a confirmation the model cannot forge. THE PROBLEM WITH THE…, Called by the UI when the user presses CONFIRM or CANCEL. Runs the stored…, Wire this module to the HUD. Called once from main.py at startup., Park an irreversible action behind the on-screen gate. Returns the sentence the…, request() (+2 more)

### Community 64 - "datetime"
Cohesion: 0.10
Nodes (29): _auto_detect_type(), _config_dir(), intel_notes(), _load_notes(), Path, actions/intel_notes.py — Dedicated Intel & Notes Terminal Action. Provides a…, Action handler called by Gemini / action_loader., _save_notes() (+21 more)

### Community 65 - "DashboardServer"
Cohesion: 0.20
Nodes (3): DashboardServer, URL for manual browser entry. When HTTPS active, points to alias port (also…, Verify DashboardServer tracks background tasks and exposes them via endpoint.

### Community 66 - "VisemeStream"
Cohesion: 0.13
Nodes (12): collections, coverage(), Text → mouth shape, fused with the audio the avatar is actually speaking. Why…, Reduce any character to a bare Latin letter, or "" if it has none. This is what…, Fraction of the letters in `text` we can reduce to a Latin sound., Split a line of speech into (viseme, duration-weight) pairs. Returns [] for…, Fuses the transcript's shape sequence onto the audio's timing. Thread note:…, Blend audio frames [(level, openness, width)] with the text queue. (+4 more)

### Community 67 - "_SysMetrics"
Cohesion: 0.13
Nodes (7): Thread-safe speech channel for plugins: lets a plugin ask JARVIS to say…, Thread-safe: ask the run loop to tear down and rebuild the Live session. Called…, Voice picker applied. The voice is baked into the session at connect time, so a…, Microphone or speaker changed. Both streams are opened inside the session…, _nvml_gpu_windows(), Return NVIDIA GPU utilisation % using nvml.dll directly — zero subprocess., _SysMetrics

### Community 68 - "._apply_name_update"
Cohesion: 0.16
Nodes (10): get_voice(), Return the configured Live voice, falling back to the default if unset or if…, apply_ui_accent(), current_palette(), Applies DOSSIER CRT [A-34] (#8e9bff), VECTOR CRT [WAKU] (#a8ff3e), or BATMAN…, A snapshot of the accent-linked colours currently on class C., LIVE full theme change. Replaces the old palette colours with the new ones in…, Live preview — paints the whole interface the new colour (does NOT write to… (+2 more)

### Community 69 - ".broadcast"
Cohesion: 0.24
Nodes (7): auto_login(), clear_chat_ep(), device_login_ep(), login(), phone_audio_ws(), _derive_key(), SHA-256(sessionKey‖salt) → 32-byte AES-256 key (microseconds, no PBKDF2 needed).

### Community 70 - "._build_config"
Cohesion: 0.22
Nodes (8): LiveConnectConfig, _describe_limits(), _describe_tools(), _load_system_prompt(), One line per capability, straight from the live tool declarations. Derived…, The other half of self-knowledge: what is out of reach, and why. Derived from…, Fill {tokens} in the prompt template. A plain replace rather than str.format:…, _render_prompt()

### Community 71 - "WakeWordDetector"
Cohesion: 0.17
Nodes (5): Runs the wake model in a dedicated thread. The mic thread calls feed() with raw…, Load the model and spawn the inference thread. Returns True on success. Safe to…, Called from the mic callback (real-time thread). Must stay cheap and never…, WakeWordDetector, Load the detector once (model loads on first start). Idempotent.

### Community 73 - "_gemini_grounding"
Cohesion: 0.22
Nodes (9): _capture_screen_image(), _gemini_grounding(), _get_api_key(), _onnx_element_grounding(), Capture current screen into a PIL Image., Run local ONNX element detector (OmniParser-v2 / Florence-2). Returns:…, Fallback visual grounding via Gemini Live / Flash API., Retrieve Gemini API key from api_keys.json or environment. (+1 more)

### Community 74 - "installer.py"
Cohesion: 0.32
Nodes (7): _available(), install_for_config(), _pip(), MARK XL — Dependency auto-installer. Called automatically on first launch and…, Return True if the module can be imported (no actual import)., Install all missing packages required by *config*. Blocking — always call from…, importlib_util

### Community 75 - "json"
Cohesion: 0.21
Nodes (8): json, _all_entries(), _trim_to_limit(), Performance Benchmark: memory_manager._trim_to_limit Tests execution time and…, Measures execution time for 50,000 mock records. Under the old O(N^2)…, Preserves all items when memory is already below limit., Handles empty memory structure gracefully., TestMemoryTrimBenchmark

### Community 76 - ".__init__"
Cohesion: 0.29
Nodes (6): index(), _ensure_certs(), _local_ip(), Return the best LAN-facing IPv4 address, no internet required., Make sure config/certs holds a TLS key pair, generating a self-signed one the…, _read()

### Community 77 - "sys"
Cohesion: 0.38
Nodes (4): main(), remove_emojis_from_headings(), re, sys

### Community 78 - "unduck_media_apps"
Cohesion: 0.24
Nodes (7): Restore ducked media applications to their exact original volume levels. :param…, unduck_media_apps(), _pcm_level(), _pcm_visemes(), Stop JARVIS mid-speech: drain queued audio and open mic immediately., Map a block of int16 PCM samples to a 0.0–1.0 loudness level for the HUD…, Slice a PCM block into (level, openness, width) frames, one per 20 ms. Returns…

### Community 79 - "LogWidget"
Cohesion: 0.25
Nodes (3): QTextEdit, LogWidget, Cancel any in-flight typing animation, drain the queue, and clear the display.

### Community 80 - "._apply_ptt_shortcut"
Cohesion: 0.22
Nodes (5): qt_sequence(), The same chord as a QKeySequence string., _press(), Bind the chord inside the window when no global hook is available. On macOS and…, Report a windowed press/release to whoever owns the microphone.

### Community 81 - ".test_error_isolation_in_concurrent_tasks"
Cohesion: 0.29
Nodes (5): Verify that an exception in one concurrent task does not break or cancel…, Verify that a batch of tasks run with a concurrency limit of 5 scales sub-…, TestConcurrencyLimiter, execute_task(), safe_run()

### Community 82 - "server.py"
Cohesion: 0.12
Nodes (14): base64, _decrypt_cbc(), _make_uploads_dir(), Path, dashboard/server.py — ALFRED Local HTTP Dashboard Plain HTTP on port 8000 (no…, Return (and create) the cross-platform uploads folder., Decrypt base64(IV[16] ‖ ciphertext) with AES-256-CBC + PKCS7., fastapi (+6 more)

### Community 83 - "_ensure_network_access"
Cohesion: 0.25
Nodes (3): _ensure_network_access(), Cross-platform, best-effort: open port in the OS firewall for LAN access. Runs…, Second HTTPS server on PORT+1 sharing the same app and in-memory state. Chrome…

### Community 84 - "TestAudioDucker"
Cohesion: 0.29
Nodes (4): patch, Verify that duck_media_apps lowers target media processes by 70% (0.3 factor),…, Verify Linux pulsectl ducking fallback logic., TestAudioDucker

### Community 85 - ".__init__"
Cohesion: 0.12
Nodes (9): ProactiveEngine, Decides when ALFRED should speak unprompted and builds a context-rich prompt.…, _Popen, Exception, Raised inside the session TaskGroup to force a clean, voluntary reconnect (e.g.…, Session-scoped task: when a voluntary reconnect is requested, raise a signal…, Turn hold-to-talk on or off. Returns the scope actually achieved., _ReconnectSignal (+1 more)

### Community 86 - "._launch"
Cohesion: 0.29
Nodes (5): _firefox_profile_dir(), launch_persistent_context already opens a starting tab. Instead of opening a…, Launches the browser with the real user profile. Does nothing if the context is…, _real_profile_dir(), Page

### Community 88 - "_detect_action"
Cohesion: 0.40
Nodes (5): _detect_action(), _normalise(), Resolve a free-text description to an action name, locally. Returns {"action":…, What to tell the model when nothing matched. Names real actions so its retry…, _suggest()

### Community 91 - "._toggle_sentry_mode"
Cohesion: 0.33
Nodes (3): Toggle continuous visual context (camera stream) monitoring., Thread-safe: start live camera feed in the full HUD area., Thread-safe: stop the live camera feed.

### Community 94 - "_unduck_linux"
Cohesion: 0.40
Nodes (5): Execute unducking on Windows via pycaw, restoring exact prior volume levels., Execute unducking on Linux via pulsectl., _unduck_linux(), _worker(), _unduck_windows()

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

### Community 102 - "/deep-work Workflow"
Cohesion: 0.50
Nodes (3): /deep-work Workflow, Objective, Steps

### Community 111 - "._listen_audio"
Cohesion: 0.50
Nodes (3): callback(), _open_mic(), True while the speakers may still be finishing our last sentence.

### Community 112 - "weather_report.py"
Cohesion: 0.50
Nodes (4): _log(), weather_action(), urllib_parse, webbrowser

### Community 119 - "screen_find.py"
Cohesion: 0.15
Nodes (18): _calculate_similarity(), _get_frame_key(), get_onnx_session(), get_rapid_ocr(), _ocr_grounding(), Any, ndarray, actions/screen_find.py — Local Hybrid Element Grounding for ALFRED. Performs… (+10 more)

## Knowledge Gaps
- **41 isolated node(s):** `C`, `Purpose`, `Rules`, `Purpose`, `Rules` (+36 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 966 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **31 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `JarvisUI` connect `JarvisUI` to `mono_font`, `JarvisLive`, `ui.py`, `_tlog`, `main.py`, `._wake_state`, `._apply_name_update`, `setter`, `._apply_ptt_shortcut`, `.__init__`, `._toggle_sentry_mode`, `.clear_chat`, `.add_intel_note`, `.glance`, `.hide_confirm`, `.hide_quiz`, `.push_visemes`, `.show_camera_frame`, `.show_quiz`, `.show_review`?**
  _High betweenness centrality (0.047) - this node is a cross-community bridge._
- **Why does `JarvisLive` connect `JarvisLive` to `memory_manager.py`, `EchoGuard`, `JarvisUI`, `_tlog`, `load_api_keys`, `PushToTalk`, `TestBackgroundWorkerPool`, `background_monitor.py`, `main.py`, `.run`, `DashboardServer`, `VisemeStream`, `_SysMetrics`, `._build_config`, `WakeWordDetector`, `unduck_media_apps`, `.__init__`, `SystemMonitor`, `._listen_audio`?**
  _High betweenness centrality (0.044) - this node is a cross-community bridge._
- **Why does `ALFRED — MARK III (Wayne Protocol Edition)` connect `ALFRED — MARK III (Wayne Protocol Edition)` to `find_element`, `system_monitor.py`?**
  _High betweenness centrality (0.042) - this node is a cross-community bridge._
- **Are the 9 inferred relationships involving `JarvisLive` (e.g. with `ProactiveEngine` and `SystemMonitor`) actually correct?**
  _`JarvisLive` has 9 INFERRED edges - model-reasoned connections that need verification._
- **What connects `C`, `Purpose`, `Rules` to the rest of the system?**
  _41 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `game_updater.py` be split into smaller, more focused modules?**
  _Cohesion score 0.06101231190150479 - nodes in this community are weakly interconnected._
- **Should `code_helper.py` be split into smaller, more focused modules?**
  _Cohesion score 0.07609427609427609 - nodes in this community are weakly interconnected._