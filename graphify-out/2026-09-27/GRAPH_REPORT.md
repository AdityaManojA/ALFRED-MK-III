# Graph Report - Alfred-Mark-III  (2026-09-27)

## Corpus Check
- 94 files · ~184,415 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 16 file(s) not represented in the graph (top: .ico 7, (none) 3, .bak 2)

## Summary
- 2363 nodes · 4635 edges · 129 communities (103 shown, 26 thin omitted)
- Extraction: 96% EXTRACTED · 4% INFERRED · 0% AMBIGUOUS · INFERRED: 186 edges (avg confidence: 0.87)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `bf4c2dde`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- game_updater.py
- file_controller.py
- clipboard_manager.py
- file_processor.py
- web_search.py
- code_helper.py
- ui_overlay.py
- doc_rag.py
- system_monitor.py
- JarvisUI
- protocol_engine.py
- computer_settings.py
- MainWindow
- dev_agent.py
- sys
- CentralizedCache
- tts.py
- EchoGuard
- desktop.py
- memory_manager.py
- qcol
- JarvisLive
- config_manager.py
- ALFRED — MARK III (Wayne Protocol Edition)
- pathlib
- plugin_loader.py
- _tlog
- computer_control.py
- .run_local
- load_api_keys
- RemoteKeyOverlay
- TronScoreBackgroundPlayer
- _BrowserSession
- .__init__
- time
- .run
- audio_devices.py
- GraphManager
- gmail_manager.py
- get_input_device
- crypto-js.min.js
- screen_find.py
- action_loader.py
- mono_font
- find_element
- VisemeStream
- screen_processor.py
- ui.py
- TacticalAudioPlayerWidget
- get_push_to_talk_enabled
- server.py
- CustomizeOverlay
- computer_settings
- echo.py
- setter
- main.py
- ._build_app
- .__init__
- HueWheel
- browser_control.py
- _SessionRegistry
- TestBackgroundWorkerPool
- ScreenCapturePayload
- numpy
- NotesTerminalWidget
- save_app_icon
- confirm.py
- DashboardServer
- _SysMetrics
- ._build_right_panel
- tech_font
- ._apply_name_update
- WakeWordDetector
- get_active_window_info
- .broadcast
- SetupOverlay
- intel_notes.py
- PushToTalk
- _ensure_network_access
- LogWidget
- TestScreenProcessorWindowContext
- ._build_jarvis_icon
- MemoryOverlay
- ._apply_ptt_shortcut
- TestAudioDucker
- .test_error_isolation_in_concurrent_tasks
- ._launch
- get_plugin_enabled
- datetime
- is_heavenly_restricted
- ._toggle_sentry_mode
- SubjectDossierCard
- _detect_action
- test_screen_processor.py
- weather_report.py
- wake_word.py
- calendar_sync.py
- .clear_chat
- format_window_context
- Daily Brief Protocol
- Email Handling Rules
- Executive Assistant Persona & Behavioral Standards
- /deep-work Workflow
- /email-triage Workflow
- _template.py
- focus_protocol.py
- _get_base_dir
- _unduck_linux
- Graphify + Antigravity Project Workflow & Setup Guide
- _get_macos_wifi_interface
- ._listen_audio
- _base_dir
- rules/graphify.md
- workflows/graphify.md
- chromadb
- chromadb_config
- fastembed
- sentence_transformers
- get_plugin_config
- watchdog_events
- watchdog_observers
- _make_uploads_dir

## God Nodes (most connected - your core abstractions)
1. `MainWindow` - 93 edges
2. `JarvisLive` - 64 edges
3. `JarvisUI` - 45 edges
4. `mono_font()` - 36 edges
5. `tech_font()` - 35 edges
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
- `Steps` --references--> `daily_brief()`  [INFERRED]
  .agents/workflows/daily_brief.md → actions/daily_brief.py
- `1. File Opening (`open`)` --references--> `file_controller()`  [INFERRED]
  .agents/rules/file_exploration.md → actions/file_controller.py

## Import Cycles
- None detected.

## Communities (129 total, 26 thin omitted)

### Community 0 - "game_updater.py"
Cohesion: 0.06
Nodes (78): _build_google_flights_url(), flight_finder(), _format_spoken(), _format_text_report(), _get_base_dir(), _parse_date(), _parse_flights_with_gemini(), Path (+70 more)

### Community 1 - "file_controller.py"
Cohesion: 0.07
Nodes (63): copy_file(), create_file(), create_folder(), delete_file(), explore_folder(), file_controller(), find_files(), _format_size() (+55 more)

### Community 2 - "clipboard_manager.py"
Cohesion: 0.05
Nodes (40): add_clipboard_item(), classify_content_type(), clipboard_manager_action(), ClipboardManager, cosine_similarity(), _get_active_window_info(), get_recent_clipboards(), is_sensitive_content() (+32 more)

### Community 3 - "file_processor.py"
Cohesion: 0.08
Nodes (45): _detect_type(), file_processor(), _file_size_str(), _gemini_client(), _output_path(), _process_archive(), _process_audio(), _process_code() (+37 more)

### Community 4 - "web_search.py"
Cohesion: 0.07
Nodes (43): _get_live_weather(), Fetch live weather conditions without opening an external browser., _compare(), _fetch_item(), _ddg_news(), _ddg_search(), _format_ddg(), _format_news() (+35 more)

### Community 5 - "code_helper.py"
Cohesion: 0.07
Nodes (49): _build(), _clean_code(), code_helper(), _detect_intent(), _edit_action(), _explain_action(), _fix_code(), _get_gemini() (+41 more)

### Community 6 - "ui_overlay.py"
Cohesion: 0.10
Nodes (15): pyqt6_qtcore, pyqt6_qtgui, pyqt6_qtwidgets, main(), QWidget, ui_overlay.py — Minimalist Floating HUD Widget for Telemetry Display A…, Set up the update timer., Set up system tray icon for control. (+7 more)

### Community 7 - "doc_rag.py"
Cohesion: 0.08
Nodes (40): _ChangeHandler, _chunk_text(), crawl_and_index(), _delete_file_chunks(), _detokenize_tokens(), _extract_text_from_file(), _get_chroma_collection(), _get_embedding_model() (+32 more)

### Community 8 - "system_monitor.py"
Cohesion: 0.07
Nodes (38): _get_cpu_temp(), _get_gpu_usage(), get_system_status(), _is_private_or_loopback(), is_protected_process(), _nvml_gpu(), Any, actions/system_monitor.py — System Metric Checks, Process Tree Watchdog &… (+30 more)

### Community 9 - "JarvisUI"
Cohesion: 0.05
Nodes (17): main(), JarvisUI, Update application and window icon in realtime., Thread-safe: raise the irreversible-action gate. Called from action handlers…, Thread-safe: take the gate down., Thread-safe: feed a 0.0–1.0 live audio level to the HUD waveform. Called from…, Ask the avatar to look somewhere for a moment (see HoloAvatar.glance)., Thread-safe: post a schedule of (level, openness, width) mouth frames for… (+9 more)

### Community 10 - "protocol_engine.py"
Cohesion: 0.07
Nodes (39): create_protocol(), _do_save(), execute_protocol(), _execute_tool(), get_action_registry(), get_protocols_file(), interpolate_variables(), _is_failure() (+31 more)

### Community 12 - "MainWindow"
Cohesion: 0.05
Nodes (11): QMainWindow, MainWindow, _fl(), Slot — display camera preview overlay (main thread)., Collapsible panel below the HUD — shows search results, news, briefings. Hidden…, Slot — runs on Qt main thread. Updates and shows the content panel., Slot — Qt main thread. Lays a document review into the content panel., Slot — Qt main thread. Puts a fresh quiz on the board. (+3 more)

### Community 13 - "dev_agent.py"
Cohesion: 0.09
Nodes (39): apply_heal_patch(), _build_project(), _classify_error(), dev_agent(), _diagnose_trace(), _extract_culprit_script(), _fix_files(), _get_model() (+31 more)

### Community 14 - "sys"
Cohesion: 0.10
Nodes (21): _available(), install_for_config(), _pip(), MARK XL — Dependency auto-installer. Called automatically on first launch and…, Return True if the module can be imported (no actual import)., Install all missing packages required by *config*. Blocking — always call from…, get_base_dir(), Path (+13 more)

### Community 15 - "CentralizedCache"
Cohesion: 0.06
Nodes (22): CentralizedCache, _canonicalize(), decorator(), wrapper(), Any, Stores value in cache with TTL. Fails open gracefully if storage fails., Deletes a key from cache. Fails open gracefully., Invalidates all keys starting with prefix. Useful for mutation hooks. (+14 more)

### Community 16 - "tts.py"
Cohesion: 0.07
Nodes (25): _compress_silence(), create_tts_player(), EdgeTTSEngine, ElevenLabsTTSEngine, _import_kokoro_pipeline(), KokoroTTSEngine, _synth(), _play_audio_bytes() (+17 more)

### Community 17 - "EchoGuard"
Cohesion: 0.08
Nodes (14): band_energies(), EchoGuard, ndarray, Classifies microphone blocks while the assistant is speaking. Usage:…, True once the estimate rests on enough real echo to be trusted., Residual left by this room's own echo. Higher = harder to separate., False when the acoustics are too poor to judge on content alone. Speakers…, The residual a block must clear right now to count as a voice. (+6 more)

### Community 18 - "desktop.py"
Cohesion: 0.12
Nodes (36): _ask_gemini_for_desktop_action(), _build_sandbox(), clean_desktop(), desktop_control(), _execute_generated_code(), _get_api_key(), _get_base_dir(), get_current_wallpaper() (+28 more)

### Community 19 - "memory_manager.py"
Cohesion: 0.08
Nodes (34): Update Daily Briefing Preferences Action for ALFRED Mark-LIV. Permanently…, Permanently saves daily briefing preferences into long-term memory., update_daily_briefing(), _do_shutdown(), Summarise the current session in 1-2 sentences and save to long_term.json., _all_entries(), all_entries_for_ui(), _empty_memory() (+26 more)

### Community 20 - "qcol"
Cohesion: 0.08
Nodes (19): QColor, QPainter, QPixmap, HudCanvas, qcol(), Thread-safe entry point for the audio threads. Stores the louder of the…, Pre-render the static grid-dot background into a transparent pixmap so…, True only when this canvas can actually be seen by the user. (+11 more)

### Community 21 - "JarvisLive"
Cohesion: 0.07
Nodes (16): LiveConnectConfig, JarvisLive, Chord pressed or released — may arrive on the hotkey thread., The optional knobs, kept apart so one bad field can be dropped wholesale. Every…, Load the detector once (model loads on first start). Idempotent., Called from the detector thread when 'Hey Jarvis' is heard., Auto-sleep after the configured silence window (wake-word mode only)., Enable/disable wake word from the settings UI. Returns a status token:… (+8 more)

### Community 22 - "config_manager.py"
Cohesion: 0.12
Nodes (22): ensure_config_dir(), get_base_dir(), get_brief_enabled(), Path, Persist the chosen Live voice. Unknown names collapse to the default so a bad…, Read-modify-write one key without disturbing the rest of the config., Merge `values` into a namespace's stored config (read-modify-write, like every…, Persist assistant name and user name to config. (+14 more)

### Community 23 - "ALFRED — MARK III (Wayne Protocol Edition)"
Cohesion: 0.06
Nodes (33): 10. Local Hybrid Visual Grounding (RapidOCR + ONNX + Gemini Fallback), 11. Process-Level Audio Ducking & Background Concurrency, 13. Bug Fixes & Stability Updates, 14. System Architecture & File Structure, 15. Quick Start & Installation, 16. Configuration Reference (`config/api_keys.json`), 17. Knowledge Graph (`graphify`), 18. Author & Credits (+25 more)

### Community 24 - "pathlib"
Cohesion: 0.09
Nodes (29): daily_brief(), _get_gmail_brief(), _get_greeting(), _get_reminders_brief(), _get_system_vitals(), Daily Brief Action for ALFRED Mark-LIV. Provides the ultimate morning and daily…, Fetch unread emails summary via gmail_manager., Check scheduled reminders in ~/.alfred/reminders or ~/.jarvis/reminders. (+21 more)

### Community 25 - "plugin_loader.py"
Cohesion: 0.19
Nodes (13): discover_plugins(), _load_error(), _opt_upper(), PluginRecord, Exception, Path, Plugin discovery, validation, collision detection, and dispatch. Discovery runs…, Returns a PluginRecord; .valid=False + .error set on any problem. Never raises. (+5 more)

### Community 26 - "_tlog"
Cohesion: 0.08
Nodes (18): FunctionResponse, _clean_transcript(), _is_repeat_chunk(), broadcast_progress(), _run_tool_bounded(), _deliver_news(), runner(), Queue a background task and return task metadata immediately. (+10 more)

### Community 27 - "computer_control.py"
Cohesion: 0.17
Nodes (27): _base_dir(), _clear_field(), _click(), _clipboard_get(), _clipboard_paste(), computer_control(), _drag(), _focus_window() (+19 more)

### Community 28 - ".run_local"
Cohesion: 0.12
Nodes (21): call_llm(), call_llm_stream(), _do_stream(), call_llm_text(), check_model_available(), ensure_ollama_running(), get_llm_provider(), get_llm_settings() (+13 more)

### Community 29 - "load_api_keys"
Cohesion: 0.11
Nodes (18): get_app_icon(), get_assistant_name(), get_gemini_key(), get_llm_provider(), get_media_resolution(), get_proactive_audio_enabled(), get_thinking_enabled(), get_turn_tuning() (+10 more)

### Community 30 - "RemoteKeyOverlay"
Cohesion: 0.27
Nodes (4): Floating overlay — QR code for instant phone pairing + manual key fallback., Call from any thread when a phone successfully connects., RemoteKeyOverlay, _lbl()

### Community 31 - "TronScoreBackgroundPlayer"
Cohesion: 0.11
Nodes (7): QObject, _base_dir(), Path, Background music audio engine. Plays background score continuously on loop…, Set base normal volume (0.0 to 1.0). Speech ducking scales to 50% of base., Duck to 50% of base volume when speaking, restore to base volume when…, TronScoreBackgroundPlayer

### Community 33 - ".__init__"
Cohesion: 0.09
Nodes (7): get_hud_style(), Which centrepiece the HUD draws: the animated head, or the reactor core. Taste,…, QDragEnterEvent, QDropEvent, CyberGraphicLineButton, FileDropZone, Tactical button rendered strictly with vector graphic lines, sharp 2px border…

### Community 34 - "time"
Cohesion: 0.31
Nodes (6): asyncio, Performance Benchmark: memory_manager._trim_to_limit Tests execution time and…, tests/test_cache.py — Comprehensive Test Suite for CentralizedCache. Tests: -…, time, unittest, unittest_mock

### Community 35 - ".run"
Cohesion: 0.12
Nodes (12): BaseException, _get_api_key(), _is_reconnect_signal(), _keep_context_of(), Background task: voice alerts when metrics exceed thresholds., Check user-configured topics once per day; speak alerts when new headlines…, Background task: periodically checks if the user has been silent long enough,…, Forward phone mic PCM chunks from dashboard queue into the Gemini Live session. (+4 more)

### Community 36 - "audio_devices.py"
Cohesion: 0.12
Nodes (20): configure(), _display_name(), _is_pseudo(), list_devices(), prefetch(), _work(), _query(), _collect() (+12 more)

### Community 37 - "GraphManager"
Cohesion: 0.11
Nodes (14): GraphManager, Any, Path, Save the graph data to the JSON file atomically., Add an entity node to the graph. Returns True if successful., Add a relationship (edge) between two nodes. Returns True if successful., Apply exponential decay to all temporary nodes. Returns the number of nodes…, Query the knowledge graph for a concept and return connected subgraph up to… (+6 more)

### Community 38 - "gmail_manager.py"
Cohesion: 0.10
Nodes (24): _clean_header_str(), _extract_body_snippet(), fetch_unread_emails(), gmail_manager(), _load_gmail_creds(), Any, Gmail Manager Action for ALFRED Mark-LIV. Provides full Gmail connectivity: -…, Send an email using Gmail SMTP SSL. (+16 more)

### Community 39 - "get_input_device"
Cohesion: 0.18
Nodes (11): get_input_device(), get_output_device(), _patch_config(), Read-modify-write one or more keys in api_keys.json. Every setter in this file…, Microphone device name, or '' for the system default., Speaker device name, or '' for the system default., save_input_device(), save_output_device() (+3 more)

### Community 41 - "screen_find.py"
Cohesion: 0.15
Nodes (18): _calculate_similarity(), _get_frame_key(), get_onnx_session(), get_rapid_ocr(), _ocr_grounding(), Any, ndarray, actions/screen_find.py — Local Hybrid Element Grounding for ALFRED. Performs… (+10 more)

### Community 42 - "action_loader.py"
Cohesion: 0.13
Nodes (15): ActionRecord, ActionRegistry, _call_handler(), discover_actions(), _opt_upper(), Path, Action discovery, validation, and dispatch — the built-in twin of…, Invoke the handler passing only the context kwargs it actually declares (or all… (+7 more)

### Community 43 - "mono_font"
Cohesion: 0.07
Nodes (15): QFont, BiometricFingerprintWidget, _CameraPreview, ClipboardPanel, CRTReconWidget, MetricBar, mono_font(), QWidget (+7 more)

### Community 44 - "find_element"
Cohesion: 0.08
Nodes (22): _capture_screen_image(), find_element(), _gemini_grounding(), _get_api_key(), is_icon_query(), _onnx_element_grounding(), Determine if target query is specifically targeting an icon/non-text element., Capture current screen into a PIL Image. (+14 more)

### Community 45 - "VisemeStream"
Cohesion: 0.13
Nodes (12): collections, coverage(), Text → mouth shape, fused with the audio the avatar is actually speaking. Why…, Reduce any character to a bare Latin letter, or "" if it has none. This is what…, Fraction of the letters in `text` we can reduce to a Latin sound., Split a line of speech into (viseme, duration-weight) pairs. Returns [] for…, Fuses the transcript's shape sequence onto the audio's timing. Thread note:…, Blend audio frames [(level, openness, width)] with the text queue. (+4 more)

### Community 46 - "screen_processor.py"
Cohesion: 0.18
Nodes (17): _capture_camera(), _cv2_backend(), _detect_camera_index(), _get_camera_index(), _get_os(), _load_config(), _probe_camera(), Screen & webcam capture for ALFRED vision with OS window context grounding.… (+9 more)

### Community 47 - "ui.py"
Cohesion: 0.14
Nodes (9): core_avatar, pyqt6_qtmultimedia, QApplication, random, C, _DropCanvas, _file_category(), _fmt_size() (+1 more)

### Community 48 - "TacticalAudioPlayerWidget"
Cohesion: 0.11
Nodes (7): QFrame, _EqualizerBarsWidget, Mini animated cyber audio wave visualizer., Sleek tactical cyber popup for adjusting master background music volume.…, Bottom-Left Cyber Tactical Audio Player Widget. Styled matching the HUD /…, TacticalAudioPlayerWidget, _VolumeSliderPopup

### Community 49 - "get_push_to_talk_enabled"
Cohesion: 0.20
Nodes (6): chord_label(), Human-readable name of the chord, for the UI and the logs., get_push_to_talk_enabled(), Hold-a-key-to-speak. When on, the mic is closed unless the chord is held., Floating overlay panel shown when the ⚙ header button is toggled., Repaint the push-to-talk row from the saved setting.

### Community 50 - "server.py"
Cohesion: 0.10
Nodes (17): base64, index(), _decrypt_cbc(), _ensure_certs(), _local_ip(), dashboard/server.py — ALFRED Local HTTP Dashboard Plain HTTP on port 8000 (no…, Return the best LAN-facing IPv4 address, no internet required., Make sure config/certs holds a TLS key pair, generating a self-signed one the… (+9 more)

### Community 51 - "CustomizeOverlay"
Cohesion: 0.14
Nodes (10): CustomizeOverlay, _lbl(), format_icon_display_name(), get_available_app_icons(), Floating glassmorphic overlay for configuring Assistant Persona, Commander…, Highlight the selected voice pill; dim the rest., Updates the selected colour; hex box + wheel stay in sync, theme is live-…, Format an icon file name into an authentic, sleek tactical insignia title. (+2 more)

### Community 52 - "computer_settings"
Cohesion: 0.12
Nodes (16): brightness_get(), brightness_set(), computer_settings(), dark_mode(), paste(), press_key(), Current brightness 0-100, or None where it cannot be read., Set brightness to an absolute percentage. Only used to restore a value captured… (+8 more)

### Community 53 - "echo.py"
Cohesion: 0.10
Nodes (17): _duck_linux(), duck_media_apps(), _worker(), _duck_windows(), is_ducked(), Execute ducking on Linux via pulsectl., Lower external media application volume (by default to 30%, i.e. ducking by…, Restore ducked media applications to their exact original volume levels. :param… (+9 more)

### Community 54 - "setter"
Cohesion: 0.10
Nodes (3): setter, _work(), Combined state for the two wake-word buttons. Readiness is a cheap,…

### Community 55 - "main.py"
Cohesion: 0.13
Nodes (22): add_monitor(), check_all(), _is_blocked(), list_monitors(), _load(), BackgroundMonitor — user-configured topic watching. Checks DDG news once per…, Run all pending topic checks (once per day per topic). Returns a list of…, remove_monitor() (+14 more)

### Community 56 - "._build_app"
Cohesion: 0.16
Nodes (9): audio_ws(), _auth(), command(), list_files(), revoke_devices(), _safe_filename(), upload_file(), wake_ep() (+1 more)

### Community 57 - ".__init__"
Cohesion: 0.10
Nodes (11): ProactiveEngine, ProactiveEngine 2.0 — context-aware, time-aware, non-repetitive background…, Decides when ALFRED should speak unprompted and builds a context-rich prompt.…, Build a context snapshot for Gemini. Rotates through three focus areas so…, _Popen, Exception, Turn hold-to-talk on or off. Returns the scope actually achieved., Raised inside the session TaskGroup to force a clean, voluntary reconnect (e.g.… (+3 more)

### Community 58 - "HueWheel"
Cohesion: 0.20
Nodes (4): QPointF, QRectF, HueWheel, Circular colour picker. The user drags the handle (small white circle) around…

### Community 59 - "browser_control.py"
Cohesion: 0.24
Nodes (11): browser_control(), _find_exe_windows(), _find_opera_windows(), _log(), _normalize_url(), _open_native(), Bare words like "instagram" → "https://instagram.com" Domains like…, Opens the user's REAL browser normally — with their own profile, logged-in… (+3 more)

### Community 60 - "_SessionRegistry"
Cohesion: 0.15
Nodes (5): _detect_default_browser(), Manages all active browser sessions., Is there an active automation session for this browser (or any)?, Returns the last natively-opened URL once (consumed to avoid repeats)., _SessionRegistry

### Community 61 - "TestBackgroundWorkerPool"
Cohesion: 0.12
Nodes (7): Verify that calling interrupt() sets halt event, immediately stops active…, Verify that _safe_background_announce waits until ALFRED finishes speaking…, Verify DashboardServer tracks background tasks and exposes them via endpoint., Verify queue_background_task is registered in TOOL_DECLARATIONS., Verify that queue_background_task returns immediately (sub-millisecond), and…, Dispatch a mock task and verify voice PTT interaction continues with sub-second…, TestBackgroundWorkerPool

### Community 62 - "ScreenCapturePayload"
Cohesion: 0.25
Nodes (3): Hybrid return payload for screen captures. - Behaves as a 3-tuple `(img_bytes,…, ScreenCapturePayload, tuple

### Community 63 - "numpy"
Cohesion: 0.14
Nodes (9): ndarray, Speech-to-Text engines for MARK XL. Whisper – offline transcription via faster-…, Offline transcription using faster-whisper., Transcribe a float32 mono 16 kHz numpy array. Returns transcript string., Streaming transcription using Vosk., Feed raw int16 LE PCM bytes. Returns (text, is_final)., VoskSTT, WhisperSTT (+1 more)

### Community 65 - "save_app_icon"
Cohesion: 0.40
Nodes (5): Update App Icon Action for ALFRED Mark-LIV. Switches the application window,…, Updates the main application icon and taskbar badge in realtime., update_app_icon(), Save the chosen app icon setting to config., save_app_icon()

### Community 66 - "confirm.py"
Cohesion: 0.21
Nodes (12): bind(), _log(), _Pending, pending_title(), core/confirm.py — a confirmation the model cannot forge. THE PROBLEM WITH THE…, Called by the UI when the user presses CONFIRM or CANCEL. Runs the stored…, when nothing is waiting. Lets an action avoid stacking two banners., Wire this module to the HUD. Called once from main.py at startup. (+4 more)

### Community 67 - "DashboardServer"
Cohesion: 0.21
Nodes (3): DashboardServer, URL for manual browser entry. When HTTPS active, points to alias port (also…, Second HTTPS server on PORT+1 sharing the same app and in-memory state. Chrome…

### Community 68 - "_SysMetrics"
Cohesion: 0.21
Nodes (4): Thread-safe speech channel for plugins: lets a plugin ask JARVIS to say…, _nvml_gpu_windows(), Return NVIDIA GPU utilisation % using nvml.dll directly — zero subprocess., _SysMetrics

### Community 69 - "._build_right_panel"
Cohesion: 0.18
Nodes (3): QHBoxLayout, Read api_keys.json config dict. Returns {} on any error., _read_full_config()

### Community 70 - "tech_font"
Cohesion: 0.13
Nodes (9): QPushButton, QVBoxLayout, CapabilitiesOverlay, PluginManagerOverlay, PluginSettingsOverlay, Floating glassmorphic overlay displaying a categorized directory of everything…, Floating overlay — lists discovered plugins with per-plugin ON/OFF toggles., Floating overlay — renders per-plugin settings forms. Fully generic: it… (+1 more)

### Community 71 - "._apply_name_update"
Cohesion: 0.16
Nodes (10): get_voice(), Return the configured Live voice, falling back to the default if unset or if…, apply_ui_accent(), current_palette(), Applies DOSSIER CRT [A-34] (#8e9bff), VECTOR CRT [WAKU] (#a8ff3e), or BATMAN…, A snapshot of the accent-linked colours currently on class C., LIVE full theme change. Replaces the old palette colours with the new ones in…, Live preview — paints the whole interface the new colour (does NOT write to… (+2 more)

### Community 72 - "WakeWordDetector"
Cohesion: 0.20
Nodes (4): Runs the wake model in a dedicated thread. The mic thread calls feed() with raw…, Load the model and spawn the inference thread. Returns True on success. Safe to…, Called from the mic callback (real-time thread). Must stay cheap and never…, WakeWordDetector

### Community 73 - "get_active_window_info"
Cohesion: 0.20
Nodes (10): get_active_window_context(), get_active_window_info(), _get_linux_window_info(), _get_macos_window_info(), _get_windows_window_info(), Query foreground window handle, title, and process name on Windows., Query active frontmost window on macOS via Quartz or AppleScript fallback., Query active window on Linux via xdotool or wmctrl. (+2 more)

### Community 74 - ".broadcast"
Cohesion: 0.24
Nodes (7): auto_login(), clear_chat_ep(), device_login_ep(), login(), phone_audio_ws(), _derive_key(), SHA-256(sessionKey‖salt) → 32-byte AES-256 key (microseconds, no PBKDF2 needed).

### Community 76 - "intel_notes.py"
Cohesion: 0.31
Nodes (8): _auto_detect_type(), _config_dir(), intel_notes(), _load_notes(), Path, actions/intel_notes.py — Dedicated Intel & Notes Terminal Action. Provides a…, Action handler called by Gemini / action_loader., _save_notes()

### Community 77 - "PushToTalk"
Cohesion: 0.20
Nodes (5): PushToTalk, Begin watching. Returns the scope actually achieved., Feed a press/release from a Qt shortcut (non-Windows, or no hook)., Calls `on_change(held: bool)` whenever the chord is pressed or released. Start…, global' once a system-wide hook is running, else 'window'.

### Community 79 - "LogWidget"
Cohesion: 0.25
Nodes (3): QTextEdit, LogWidget, Cancel any in-flight typing animation, drain the queue, and clear the display.

### Community 80 - "TestScreenProcessorWindowContext"
Cohesion: 0.22
Nodes (5): Verifies system falls back to 'App: Unknown' without raising exceptions., Verification Requirement: Verify [WINDOW_CONTEXT] header contains VS Code and…, Verifies that active window query resolves in < 15ms and adheres to schema., Verifies capture_screen() returns valid compressed image and window context., TestScreenProcessorWindowContext

### Community 81 - "._build_jarvis_icon"
Cohesion: 0.22
Nodes (4): Render an ALFRED tactical icon at 4× resolution and downsample for crisp…, Create a Windows .lnk shortcut WITHOUT launching PowerShell or cmd. Tries…, Resolve the user's REAL desktop directory instead of assuming ~/Desktop, which…, Create a desktop shortcut on Windows / macOS / Linux. Never opens a terminal,…

### Community 82 - "MemoryOverlay"
Cohesion: 0.17
Nodes (8): ConfirmBanner, _HudOverlay, MemoryOverlay, Base for the floating panels placed by hand over the HUD. They are children of…, The gate in front of an action that cannot be taken back. The old confirmation…, Everything ALFRED has stored about you, and when it learned it. Memory used to…, Take every item out of the layout and detach it from the widget tree in this…, Size the panel to its content, re-centre it, and repaint what the old size…

### Community 83 - "._apply_ptt_shortcut"
Cohesion: 0.29
Nodes (5): qt_sequence(), The same chord as a QKeySequence string., _press(), Bind the chord inside the window when no global hook is available. On macOS and…, Report a windowed press/release to whoever owns the microphone.

### Community 84 - "TestAudioDucker"
Cohesion: 0.29
Nodes (4): patch, Verify that duck_media_apps lowers target media processes by 70% (0.3 factor),…, Verify Linux pulsectl ducking fallback logic., TestAudioDucker

### Community 85 - ".test_error_isolation_in_concurrent_tasks"
Cohesion: 0.29
Nodes (5): Verify that an exception in one concurrent task does not break or cancel…, Verify that a batch of tasks run with a concurrency limit of 5 scales sub-…, TestConcurrencyLimiter, execute_task(), safe_run()

### Community 86 - "._launch"
Cohesion: 0.29
Nodes (5): _firefox_profile_dir(), launch_persistent_context already opens a starting tab. Instead of opening a…, Launches the browser with the real user profile. Does nothing if the context is…, _real_profile_dir(), Page

### Community 87 - "get_plugin_enabled"
Cohesion: 0.19
Nodes (7): _call_run(), PluginRegistry, One entry per settings SECTION, for enabled plugins that declare a…, Invoke run() passing only the kwargs it actually declares (or all of them if it…, How this plugin's result should re-enter the conversation, if it said., get_plugin_enabled(), Plugins are enabled by default the moment they're discovered (opt-out model).

### Community 88 - "datetime"
Cohesion: 0.41
Nodes (11): _base_dir(), _get_os(), Path, reminder(), _sanitise(), _schedule_linux(), _schedule_mac(), _schedule_windows() (+3 more)

### Community 89 - "is_heavenly_restricted"
Cohesion: 0.24
Nodes (6): _normalize(), open_app(), _is_heavenly_restricted_params(), is_heavenly_restricted(), Any, Check if any argument references the restricted Personal-Assistant directory.

### Community 90 - "._toggle_sentry_mode"
Cohesion: 0.33
Nodes (3): Toggle continuous visual context (camera stream) monitoring., Thread-safe: start live camera feed in the full HUD area., Thread-safe: stop the live camera feed.

### Community 92 - "_detect_action"
Cohesion: 0.40
Nodes (5): _detect_action(), _normalise(), Resolve a free-text description to an action name, locally. Returns {"action":…, What to tell the model when nothing matched. Names real actions so its retry…, _suggest()

### Community 93 - "test_screen_processor.py"
Cohesion: 0.20
Nodes (9): capture_screen(), _capture_screen(), _compress(), format_visual_payload(), Prepares the visual frame payload dictionary for the Gemini Live API…, Captures primary or specified monitor, queries active OS window context,…, Default entry point used by main.py., Unit and integration tests for screen_processor.py window context grounding.… (+1 more)

### Community 94 - "weather_report.py"
Cohesion: 0.50
Nodes (4): _log(), weather_action(), urllib_parse, webbrowser

### Community 95 - "wake_word.py"
Cohesion: 0.36
Nodes (7): install_and_download(), is_installed(), is_ready(), Local wake-word detection for ALFRED ("Hey Jarvis"). Design goals: • ZERO cost…, True if the openwakeword package is importable (no model check)., True if openwakeword is installed AND its model files are present on disk. This…, One-click setup for the UI button: pip-install openwakeword if missing, then…

### Community 96 - "calendar_sync.py"
Cohesion: 0.47
Nodes (5): _load_events(), Calendar Sync Plugin for ALFRED Mark-LIV. Tracks agenda, meetings,…, Execute calendar action., run(), _save_events()

### Community 98 - "format_window_context"
Cohesion: 0.50
Nodes (3): format_window_context(), Format the standard metadata block: [WINDOW_CONTEXT] App: <Name> | Title:…, Verifies exact string formatting requirements.

### Community 99 - "Daily Brief Protocol"
Cohesion: 0.50
Nodes (3): Daily Brief Protocol, Purpose, Rules

### Community 100 - "Email Handling Rules"
Cohesion: 0.50
Nodes (3): Email Handling Rules, Purpose, Rules

### Community 101 - "Executive Assistant Persona & Behavioral Standards"
Cohesion: 0.50
Nodes (3): Core Operational Rules, Executive Assistant Persona & Behavioral Standards, Persona & Demeanor

### Community 102 - "/deep-work Workflow"
Cohesion: 0.50
Nodes (3): /deep-work Workflow, Objective, Steps

### Community 103 - "/email-triage Workflow"
Cohesion: 0.50
Nodes (3): /email-triage Workflow, Objective, Steps

### Community 104 - "_template.py"
Cohesion: 0.50
Nodes (3): Drop-in ALFRED plugin template. Copy this file, rename it (no leading…, parameters: dict of the args Gemini extracted, matching PLUGIN['parameters'].…, run()

### Community 105 - "focus_protocol.py"
Cohesion: 0.47
Nodes (5): Focus Protocol Plugin for ALFRED Mark-LIV. Manages deep work intervals,…, Execute focus protocol actions., _read_state(), run(), _write_state()

### Community 106 - "_get_base_dir"
Cohesion: 0.67
Nodes (3): _get_api_key(), _get_base_dir(), Path

### Community 107 - "_unduck_linux"
Cohesion: 0.40
Nodes (5): Execute unducking on Windows via pycaw, restoring exact prior volume levels., Execute unducking on Linux via pulsectl., _unduck_linux(), _worker(), _unduck_windows()

### Community 110 - "._listen_audio"
Cohesion: 0.50
Nodes (3): callback(), _open_mic(), True while the speakers may still be finishing our last sentence.

### Community 124 - "get_plugin_config"
Cohesion: 0.50
Nodes (4): get_plugin_config(), get_plugin_setting(), All stored values for a namespace (empty dict if none set yet)., A single value from a namespace, or `default` if unset.

### Community 127 - "_make_uploads_dir"
Cohesion: 0.67
Nodes (3): _make_uploads_dir(), Path, Return (and create) the cross-platform uploads folder.

## Knowledge Gaps
- **41 isolated node(s):** `C`, `Purpose`, `Rules`, `Purpose`, `Rules` (+36 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 970 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **26 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `JarvisLive` connect `JarvisLive` to `time`, `DashboardServer`, `_SysMetrics`, `.run`, `system_monitor.py`, `WakeWordDetector`, `JarvisUI`, `PushToTalk`, `VisemeStream`, `._listen_audio`, `EchoGuard`, `memory_manager.py`, `echo.py`, `main.py`, `.__init__`, `_tlog`, `.run_local`, `TestBackgroundWorkerPool`?**
  _High betweenness centrality (0.051) - this node is a cross-community bridge._
- **Why does `JarvisUI` connect `JarvisUI` to `.__init__`, `.clear_chat`, `._apply_name_update`, `ui.py`, `get_push_to_talk_enabled`, `._apply_ptt_shortcut`, `JarvisLive`, `setter`, `main.py`, `.__init__`, `._toggle_sentry_mode`?**
  _High betweenness centrality (0.049) - this node is a cross-community bridge._
- **Why does `DashboardServer` connect `DashboardServer` to `time`, `.run`, `.broadcast`, `server.py`, `JarvisLive`, `main.py`, `._build_app`, `TestBackgroundWorkerPool`?**
  _High betweenness centrality (0.039) - this node is a cross-community bridge._
- **Are the 9 inferred relationships involving `JarvisLive` (e.g. with `ProactiveEngine` and `SystemMonitor`) actually correct?**
  _`JarvisLive` has 9 INFERRED edges - model-reasoned connections that need verification._
- **What connects `C`, `Purpose`, `Rules` to the rest of the system?**
  _41 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `game_updater.py` be split into smaller, more focused modules?**
  _Cohesion score 0.06190476190476191 - nodes in this community are weakly interconnected._
- **Should `file_controller.py` be split into smaller, more focused modules?**
  _Cohesion score 0.06690140845070422 - nodes in this community are weakly interconnected._