# Awesome Whisper Apps

A curated collection of applications, tools, and resources built with [OpenAI Whisper](https://github.com/openai/whisper) - a robust automatic speech recognition (ASR) system trained on 680,000 hours of multilingual and multitask supervised data.

## Table of Contents

- [Quick Start Guide](#quick-start-guide)
- [Popular Picks](#popular-picks)
- [Getting Started](#getting-started)
- [By Use Case](#by-use-case)
- [By Platform](#by-platform)
- [For Developers](#for-developers)
- [Resources](#resources)

## Quick Start Guide

**Looking for something specific?**

- **Voice typing on Linux?** → [Linux System Integration](#linux-system-integration) or try [nerd-dictation](#nerd-dictation)
- **Voice typing on Mac?** → [macOS Apps](#macos) or try [SuperWhisper](#superwhisper)
- **Voice typing on Windows?** → [Windows Apps](#windows) or try [WinWhisper](#winwhisper)
- **Cross-platform desktop app?** → Try [Buzz](#buzz) or [whisper-writer](#whisper-writer)
- **Generate video subtitles?** → [Subtitles & Captioning](#srt--subtitles--captioning)
- **Real-time transcription?** → [Real-Time & Streaming](#real-time--streaming)
- **Meeting transcription?** → [Meeting & Productivity](#meeting--productivity)
- **Cloud/SaaS solution?** → [SaaS Platforms](#saas-platforms)
- **Self-hosted web interface?** → [Web UI](#web-ui)
- **Mobile app?** → [Android](#android) or [iOS](#ios)
- **Developer integration?** → [Libraries & APIs](#libraries--apis) or [Model Variants](#model-variants)

## Popular Picks

Top projects by community engagement and activity:

### Desktop Applications
| Project | Platform | Stars | Description |
|---------|----------|-------|-------------|
| [Buzz](#buzz) | Cross-platform | ![GitHub stars](https://img.shields.io/github/stars/chidiwilliams/buzz?style=flat-square) | Feature-rich desktop transcription app |
| [whisper-writer](#whisper-writer) | Cross-platform | ![GitHub stars](https://img.shields.io/github/stars/savbell/whisper-writer?style=flat-square) | Voice-to-text for system-wide input |
| [SuperWhisper](#superwhisper) | macOS | N/A | Premium Mac app for voice-to-text |
| [WinWhisper](#winwhisper) | Windows | ![GitHub stars](https://img.shields.io/github/stars/GewoonJaap/WinWhisper?style=flat-square) | System-wide hotkey support for Windows |

### Model Variants & Performance
| Project | Stars | Description |
|---------|-------|-------------|
| [whisper.cpp](#whispercpp) | ![GitHub stars](https://img.shields.io/github/stars/ggerganov/whisper.cpp?style=flat-square) | High-performance C/C++ implementation |
| [faster-whisper](#faster-whisper) | ![GitHub stars](https://img.shields.io/github/stars/SYSTRAN/faster-whisper?style=flat-square) | Faster implementation using CTranslate2 |
| [WhisperX](#whisperx) | ![GitHub stars](https://img.shields.io/github/stars/m-bain/whisperX?style=flat-square) | Word-level timestamps + speaker diarization |
| [insanely-fast-whisper](#insanely-fast-whisper) | ![GitHub stars](https://img.shields.io/github/stars/Vaibhavs10/insanely-fast-whisper?style=flat-square) | Speed-optimized implementation |

### Developer Tools
| Project | Stars | Description |
|---------|-------|-------------|
| [WhisperLive](#whisperlive) | ![GitHub stars](https://img.shields.io/github/stars/collabora/WhisperLive?style=flat-square) | Real-time transcription server |
| [whisper_streaming](#whisper_streaming) | ![GitHub stars](https://img.shields.io/github/stars/ufal/whisper_streaming?style=flat-square) | Long-form streaming transcription |
| [Whisper-WebUI](#whisper-webui) | ![GitHub stars](https://img.shields.io/github/stars/jhj0517/Whisper-WebUI?style=flat-square) | Self-hosted web interface |

## Getting Started

### Official Whisper & Models

**Official Repository:** [openai/whisper](https://github.com/openai/whisper) ![GitHub stars](https://img.shields.io/github/stars/openai/whisper?style=flat-square)

**Hugging Face Collection:** [Whisper Model Release](https://huggingface.co/collections/openai/whisper-release)

**Official Paper:** [Robust Speech Recognition via Large-Scale Weak Supervision](https://arxiv.org/abs/2212.04356)

### Official Model Sizes

Choose based on your accuracy/speed requirements:

| Model | Parameters | English-only | Multilingual | Relative Speed | Use Case |
|-------|------------|--------------|--------------|----------------|----------|
| [tiny](https://huggingface.co/openai/whisper-tiny) | 39M | ✓ | ✓ | Fastest | Minimal resource usage, real-time apps |
| [base](https://huggingface.co/openai/whisper-base) | 74M | ✓ | ✓ | Very Fast | Resource-constrained environments |
| [small](https://huggingface.co/openai/whisper-small) | 244M | ✓ | ✓ | Fast | Good balance for most use cases |
| [medium](https://huggingface.co/openai/whisper-medium) | 769M | ✓ | ✓ | Moderate | Better accuracy, moderate speed |
| [large](https://huggingface.co/openai/whisper-large) | 1550M | - | ✓ | Slower | Best accuracy, research use |

---

## By Use Case

### Voice Typing & Dictation

**Cross-Platform:**
- [Buzz](#buzz) - Feature-rich desktop app
- [whisper-writer](#whisper-writer) - System-wide voice-to-text
- [whisper-dictation](#whisper-dictation) - Dictation application

**Linux:**
- [nerd-dictation](#nerd-dictation) - Hackable offline speech-to-text
- [BlahST](#blahst) - Linux speech-to-text integration
- [whisper-to-input](#whisper-to-input) - Convert transcription to keyboard input
- [voice-typing-linux](#voice-typing-linux) - Voice typing integration

**macOS:**
- [SuperWhisper](#superwhisper) - Premium Mac voice-to-text app
- [OpenSuperWhisper](#opensuperwhisper) - Open-source Mac app
- [WhisperKit](#whisperkit) - Native macOS implementation

**Windows:**
- [WinWhisper](#winwhisper) - System-wide hotkey support
- [Whisper Typing for Windows](#whisper-typing-for-windows) - Desktop voice typing

**Mobile:**
- [whisperIME](#whisperime) (Android) - Input method editor
- [Whisperboard](#whisperboard) (iOS) - Keyboard with Whisper

### SaaS Platforms & Cloud Services

- [Whisper Transcribe](https://www.whispertranscribe.com/) - Online transcription platform
- [WhisperAI](https://whisperai.com) - Cloud-based transcription service
- [Whisper Typing](https://whispertyping.com/) - Online typing and transcription
- [Wisprflow](https://wisprflow.ai/) - Workflow automation with transcription
- [CleverType](https://www.clevertype.co/) - Smart typing assistant
- [SpeechPulse](https://speechpulse.com/) - Cross-platform speech-to-text
- [Blabby.ai](https://www.blabby.ai/) - Browser-based transcription

### Subtitles & Captioning

Generate subtitles and captions for videos:

- **[auto-subs](https://github.com/tmoroney/auto-subs)** ![GitHub stars](https://img.shields.io/github/stars/tmoroney/auto-subs?style=flat-square) - Automatic subtitle generation
- **[TeroSubtitler](https://github.com/URUWorks/TeroSubtitler)** ![GitHub stars](https://img.shields.io/github/stars/URUWorks/TeroSubtitler?style=flat-square) - Professional subtitle editor
- **[whisper-youtube](https://github.com/ArthurFDLR/whisper-youtube)** ![GitHub stars](https://img.shields.io/github/stars/ArthurFDLR/whisper-youtube?style=flat-square) - YouTube subtitle generation
- **[yt-whisper](https://github.com/m1guelpf/yt-whisper)** ![GitHub stars](https://img.shields.io/github/stars/m1guelpf/yt-whisper?style=flat-square) - YouTube transcription tool
- **[whisper-subs](https://github.com/GhostNaN/whisper-subs)** ![GitHub stars](https://img.shields.io/github/stars/GhostNaN/whisper-subs?style=flat-square) - CLI for adding subtitles to videos
- **[whisply](https://github.com/tsmdt/whisply)** ![GitHub stars](https://img.shields.io/github/stars/tsmdt/whisply?style=flat-square) - Automatic subtitle generation (Linux)
- **[template-tiktok](https://github.com/remotion-dev/template-tiktok)** ![GitHub stars](https://img.shields.io/github/stars/remotion-dev/template-tiktok?style=flat-square) - TikTok-style captioning with Remotion

### Meeting & Productivity

Tools for transcribing meetings and generating notes:

- **[meeting-minutes](https://github.com/Zackriya-Solutions/meeting-minutes)** ![GitHub stars](https://img.shields.io/github/stars/Zackriya-Solutions/meeting-minutes?style=flat-square) - Generate meeting minutes
- **[ScribeWizard](https://github.com/Bklieger/ScribeWizard)** ![GitHub stars](https://img.shields.io/github/stars/Bklieger/ScribeWizard?style=flat-square) - AI-powered note-taking

### Web Interfaces

**Self-Hosted:**
- **[Whisper-WebUI](https://github.com/jhj0517/Whisper-WebUI)** ![GitHub stars](https://img.shields.io/github/stars/jhj0517/Whisper-WebUI?style=flat-square) - Web interface for transcription
- **[NeuroSandboxWebUI](https://github.com/Dartvauder/NeuroSandboxWebUI)** ![GitHub stars](https://img.shields.io/github/stars/Dartvauder/NeuroSandboxWebUI?style=flat-square) - Comprehensive web UI for AI models

---

## By Platform

### Cross-Platform Desktop Applications

Applications that work on Linux, macOS, and Windows:

| Project | Stars | Description |
|---------|-------|-------------|
| [Buzz](https://github.com/chidiwilliams/buzz) | ![GitHub stars](https://img.shields.io/github/stars/chidiwilliams/buzz?style=flat-square) | Feature-rich transcription app |
| [whisper-writer](https://github.com/savbell/whisper-writer) | ![GitHub stars](https://img.shields.io/github/stars/savbell/whisper-writer?style=flat-square) | Voice-to-text application |
| [faster-whisper-GUI](https://github.com/CheshireCC/faster-whisper-GUI) | ![GitHub stars](https://img.shields.io/github/stars/CheshireCC/faster-whisper-GUI?style=flat-square) | GUI for faster-whisper |
| [SoftWhisper](https://github.com/NullMagic2/SoftWhisper) | ![GitHub stars](https://img.shields.io/github/stars/NullMagic2/SoftWhisper?style=flat-square) | User-friendly GUI |
| [speech-assistant](https://github.com/Mohamad-Hussein/speech-assistant) | ![GitHub stars](https://img.shields.io/github/stars/Mohamad-Hussein/speech-assistant?style=flat-square) | Speech assistant GUI |
| [whisper-dictation](https://github.com/foges/whisper-dictation) | ![GitHub stars](https://img.shields.io/github/stars/foges/whisper-dictation?style=flat-square) | Dictation application |
| [whisper-realtime-gui](https://github.com/phongthanhbuiit/whisper-realtime-gui) | ![GitHub stars](https://img.shields.io/github/stars/phongthanhbuiit/whisper-realtime-gui?style=flat-square) | Real-time transcription GUI |
| [whisper-ui](https://github.com/schnoddelbotz/whisper-ui) | ![GitHub stars](https://img.shields.io/github/stars/schnoddelbotz/whisper-ui?style=flat-square) | Cross-platform desktop UI |
| [whisper_dictation](https://github.com/themanyone/whisper_dictation) | ![GitHub stars](https://img.shields.io/github/stars/themanyone/whisper_dictation?style=flat-square) | Voice dictation tool |
| [WhisperGUI](https://github.com/ADT109119/WhisperGUI) | ![GitHub stars](https://img.shields.io/github/stars/ADT109119/WhisperGUI?style=flat-square) | Simple GUI |

### Linux

#### Desktop Applications
- **[froshine](https://github.com/AdrianScott/froshine)** ![GitHub stars](https://img.shields.io/github/stars/AdrianScott/froshine?style=flat-square) - Linux desktop app
- **[speak-to-ai](https://github.com/AshBuk/speak-to-ai)** ![GitHub stars](https://img.shields.io/github/stars/AshBuk/speak-to-ai?style=flat-square) - Voice interaction app
- **[Whisper-Notepad-For-Linux](https://github.com/danielrosehill/Whisper-Notepad-For-Linux)** ![GitHub stars](https://img.shields.io/github/stars/danielrosehill/Whisper-Notepad-For-Linux?style=flat-square) - Notepad-style transcription
- **[WhisperNow](https://github.com/shinglyu/WhisperNow)** ![GitHub stars](https://img.shields.io/github/stars/shinglyu/WhisperNow?style=flat-square) - Desktop application

#### CLI Tools
- **[whisper.cpp-cli](https://github.com/charliermarsh/whisper.cpp-cli)** ![GitHub stars](https://img.shields.io/github/stars/charliermarsh/whisper.cpp-cli?style=flat-square) - CLI for whisper.cpp
- **[blurt](https://github.com/QuantiusBenignus/blurt)** ![GitHub stars](https://img.shields.io/github/stars/QuantiusBenignus/blurt?style=flat-square) - Command-line transcription tool

#### System Integration
- **[nerd-dictation](https://github.com/ideasman42/nerd-dictation)** ![GitHub stars](https://img.shields.io/github/stars/ideasman42/nerd-dictation?style=flat-square) - Hackable offline STT (VOSK-API)
- **[BlahST](https://github.com/QuantiusBenignus/BlahST)** ![GitHub stars](https://img.shields.io/github/stars/QuantiusBenignus/BlahST?style=flat-square) - Speech-to-text integration
- **[Linux-Dictation-Project](https://github.com/wheeler01/Linux-Dictation-Project)** ![GitHub stars](https://img.shields.io/github/stars/wheeler01/Linux-Dictation-Project?style=flat-square) - Dictation system
- **[linux-stt-input](https://github.com/fengwk/linux-stt-input)** ![GitHub stars](https://img.shields.io/github/stars/fengwk/linux-stt-input?style=flat-square) - STT input method
- **[linux-voice-to-text-ai](https://github.com/trebormc/linux-voice-to-text-ai)** ![GitHub stars](https://img.shields.io/github/stars/trebormc/linux-voice-to-text-ai?style=flat-square) - Voice-to-text AI
- **[LinuxWhisper](https://github.com/vitali87/LinuxWhisper)** ![GitHub stars](https://img.shields.io/github/stars/vitali87/LinuxWhisper?style=flat-square) - Linux implementation
- **[voice-typing-linux](https://github.com/GitJuhb/voice-typing-linux)** ![GitHub stars](https://img.shields.io/github/stars/GitJuhb/voice-typing-linux?style=flat-square) - Voice typing integration
- **[Whisper-Dictation](https://github.com/LumenYoung/Whisper-Dictation)** ![GitHub stars](https://img.shields.io/github/stars/LumenYoung/Whisper-Dictation?style=flat-square) - Dictation system
- **[whisper-flow-linux](https://github.com/sapountzis/whisper-flow-linux)** ![GitHub stars](https://img.shields.io/github/stars/sapountzis/whisper-flow-linux?style=flat-square) - Workflow integration
- **[whisper-hotkey-linux](https://github.com/atkvishnu/whisper-hotkey-linux)** ![GitHub stars](https://img.shields.io/github/stars/atkvishnu/whisper-hotkey-linux?style=flat-square) - Hotkey-based integration
- **[whispertrigger](https://github.com/RetroTrigger/whispertrigger)** ![GitHub stars](https://img.shields.io/github/stars/RetroTrigger/whispertrigger?style=flat-square) - System integration
- **[whisprd](https://github.com/AgenticToaster/whisprd)** ![GitHub stars](https://img.shields.io/github/stars/AgenticToaster/whisprd?style=flat-square) - Whisper daemon
- **[whisper-to-input](https://github.com/j3soon/whisper-to-input)** ![GitHub stars](https://img.shields.io/github/stars/j3soon/whisper-to-input?style=flat-square) - Transcription to keyboard input
- **[whispy](https://github.com/daaku/whispy)** ![GitHub stars](https://img.shields.io/github/stars/daaku/whispy?style=flat-square) - Integration tool
- **[dicti](https://github.com/tksimson/dicti)** ![GitHub stars](https://img.shields.io/github/stars/tksimson/dicti?style=flat-square) - Dictation tool
- **[sonori](https://github.com/0xPD33/sonori)** ![GitHub stars](https://img.shields.io/github/stars/0xPD33/sonori?style=flat-square) - Voice input system
- **[hushnote](https://github.com/peteonrails/hushnote)** ![GitHub stars](https://img.shields.io/github/stars/peteonrails/hushnote?style=flat-square) - Private note-taking
- **[Local-Voice](https://github.com/shashank2122/Local-Voice)** ![GitHub stars](https://img.shields.io/github/stars/shashank2122/Local-Voice?style=flat-square) - Local voice processing
- **[s2t](https://github.com/franchesoni/s2t)** ![GitHub stars](https://img.shields.io/github/stars/franchesoni/s2t?style=flat-square) - Speech-to-text
- **[Whisper-Notepad-Simple](https://github.com/danielrosehill/Whisper-Notepad-Simple)** ![GitHub stars](https://img.shields.io/github/stars/danielrosehill/Whisper-Notepad-Simple?style=flat-square) - Simple notepad app
- **[Linux-AI-Assistant-scripts](https://github.com/samoylenkodmitry/Linux-AI-Assistant-scripts)** ![GitHub stars](https://img.shields.io/github/stars/samoylenkodmitry/Linux-AI-Assistant-scripts?style=flat-square) - AI assistant scripts

### macOS

#### Desktop Applications
- **[SuperWhisper](https://superwhisper.com/)** - Premium Mac voice-to-text app
- **[OpenSuperWhisper](https://github.com/Starmel/OpenSuperWhisper)** ![GitHub stars](https://img.shields.io/github/stars/Starmel/OpenSuperWhisper?style=flat-square) - Open-source Mac app
- **[WhisperKit](https://github.com/argmaxinc/WhisperKit)** ![GitHub stars](https://img.shields.io/github/stars/argmaxinc/WhisperKit?style=flat-square) - Native macOS implementation
- **[Careless Whisper](https://carelesswhisper.app/)** - Lightweight transcription app

#### System Integration
- **[ollama-voice-mac](https://github.com/apeatling/ollama-voice-mac)** ![GitHub stars](https://img.shields.io/github/stars/apeatling/ollama-voice-mac?style=flat-square) - Voice interface for Ollama
- **[whisperanywhere-js](https://github.com/unclecode/whisperanywhere-js)** ![GitHub stars](https://img.shields.io/github/stars/unclecode/whisperanywhere-js?style=flat-square) - System-wide transcription

---

### Windows

#### Desktop Applications
- **[AI Transcription](https://apps.microsoft.com/detail/9p7f1j2svk3g)** - Microsoft Store app
- **[Whisper Typing for Windows](https://whispertyping.com/download)** - Desktop voice typing

#### System Integration
- **[WinWhisper](https://github.com/GewoonJaap/WinWhisper)** ![GitHub stars](https://img.shields.io/github/stars/GewoonJaap/WinWhisper?style=flat-square) - System-wide hotkey support

---

### Android

- **[whisperIME](https://github.com/woheller69/whisperIME)** ![GitHub stars](https://img.shields.io/github/stars/woheller69/whisperIME?style=flat-square) - Input method editor
- **[WhisperInput](https://github.com/alex-vt/WhisperInput)** ![GitHub stars](https://img.shields.io/github/stars/alex-vt/WhisperInput?style=flat-square) - Input app
- **[WhisperKitAndroid](https://github.com/argmaxinc/WhisperKitAndroid)** ![GitHub stars](https://img.shields.io/github/stars/argmaxinc/WhisperKitAndroid?style=flat-square) - WhisperKit for Android
- **[RTranslator](https://github.com/niedev/RTranslator)** ![GitHub stars](https://img.shields.io/github/stars/niedev/RTranslator?style=flat-square) - Real-time translation app
- **[Dictate](https://github.com/DevEmperor/Dictate)** ![GitHub stars](https://img.shields.io/github/stars/DevEmperor/Dictate?style=flat-square) - Voice dictation app
- **[whisper_android](https://github.com/vilassn/whisper_android)** ![GitHub stars](https://img.shields.io/github/stars/vilassn/whisper_android?style=flat-square) - Android integration

---

### iOS

- **[Whisperboard](https://github.com/Saik0s/Whisperboard)** ![GitHub stars](https://img.shields.io/github/stars/Saik0s/Whisperboard?style=flat-square) - iOS keyboard with Whisper integration

---

### Embedded / Raspberry Pi

- **[Local-Voice](https://github.com/shashank2122/Local-Voice)** ![GitHub stars](https://img.shields.io/github/stars/shashank2122/Local-Voice?style=flat-square) - Local voice processing for embedded systems

---

## For Developers

### Model Variants & Performance Optimizations

Enhanced and optimized versions of Whisper:

| Project | Stars | Key Feature |
|---------|-------|-------------|
| [whisper.cpp](https://github.com/ggerganov/whisper.cpp) | ![GitHub stars](https://img.shields.io/github/stars/ggerganov/whisper.cpp?style=flat-square) | High-performance C/C++ implementation |
| [faster-whisper](https://github.com/SYSTRAN/faster-whisper) | ![GitHub stars](https://img.shields.io/github/stars/SYSTRAN/faster-whisper?style=flat-square) | 4x faster using CTranslate2 |
| [insanely-fast-whisper](https://github.com/Vaibhavs10/insanely-fast-whisper) | ![GitHub stars](https://img.shields.io/github/stars/Vaibhavs10/insanely-fast-whisper?style=flat-square) | Speed-optimized implementation |
| [WhisperX](https://github.com/m-bain/whisperX) | ![GitHub stars](https://img.shields.io/github/stars/m-bain/whisperX?style=flat-square) | Word-level timestamps + diarization |
| [distil-whisper](https://github.com/huggingface/distil-whisper) | ![GitHub stars](https://img.shields.io/github/stars/huggingface/distil-whisper?style=flat-square) | Distilled models from HuggingFace |
| [CrisperWhisper](https://github.com/nyrahealth/CrisperWhisper) | ![GitHub stars](https://img.shields.io/github/stars/nyrahealth/CrisperWhisper?style=flat-square) | Enhanced accuracy variant |
| [whisper.net](https://github.com/sandrohanea/whisper.net) | ![GitHub stars](https://img.shields.io/github/stars/sandrohanea/whisper.net?style=flat-square) | .NET implementation |
| [whisper-turbo](https://github.com/FL33TW00D/whisper-turbo) | ![GitHub stars](https://img.shields.io/github/stars/FL33TW00D/whisper-turbo?style=flat-square) | High-performance implementation |

### Real-Time & Streaming

For live transcription and streaming audio:

- **[WhisperLive](https://github.com/collabora/WhisperLive)** ![GitHub stars](https://img.shields.io/github/stars/collabora/WhisperLive?style=flat-square) - Real-time transcription server
- **[whisper_streaming](https://github.com/ufal/whisper_streaming)** ![GitHub stars](https://img.shields.io/github/stars/ufal/whisper_streaming?style=flat-square) - Long-form streaming transcription
- **[whisper_real_time](https://github.com/davabase/whisper_real_time)** ![GitHub stars](https://img.shields.io/github/stars/davabase/whisper_real_time?style=flat-square) - Real-time implementation
- **[whisper-flow](https://github.com/dimastatz/whisper-flow)** ![GitHub stars](https://img.shields.io/github/stars/dimastatz/whisper-flow?style=flat-square) - Real-time flow

### Diarization & Advanced Features

Speaker diarization and word-level timestamps:

- **[whisper-diarization](https://github.com/MahmoudAshraf97/whisper-diarization)** ![GitHub stars](https://img.shields.io/github/stars/MahmoudAshraf97/whisper-diarization?style=flat-square) - Speaker diarization
- **[whisper-timestamped](https://github.com/linto-ai/whisper-timestamped)** ![GitHub stars](https://img.shields.io/github/stars/linto-ai/whisper-timestamped?style=flat-square) - Word-level timestamps
- **[pyannote-whisper](https://github.com/yinruiqing/pyannote-whisper)** ![GitHub stars](https://img.shields.io/github/stars/yinruiqing/pyannote-whisper?style=flat-square) - Pyannote integration
- **[cog-whisper-diarization](https://github.com/thomasmol/cog-whisper-diarization)** ![GitHub stars](https://img.shields.io/github/stars/thomasmol/cog-whisper-diarization?style=flat-square) - Cog-wrapped diarization
- **[WhisperTimeSync](https://github.com/EtienneAb3d/WhisperTimeSync)** ![GitHub stars](https://img.shields.io/github/stars/EtienneAb3d/WhisperTimeSync?style=flat-square) - Time sync & diarization

### Fine-Tuning

Tools for customizing Whisper models:

- **[Whisper-Finetune](https://github.com/yeyupiaoling/Whisper-Finetune)** ![GitHub stars](https://img.shields.io/github/stars/yeyupiaoling/Whisper-Finetune?style=flat-square) - Fine-tuning utilities
- **[whisper-finetuning](https://github.com/jumon/whisper-finetuning)** ![GitHub stars](https://img.shields.io/github/stars/jumon/whisper-finetuning?style=flat-square) - Fine-tuning framework

### Deployment & Containers

- **[cog-whisper](https://github.com/replicate/cog-whisper)** ![GitHub stars](https://img.shields.io/github/stars/replicate/cog-whisper?style=flat-square) - Cog container for deployment

### IDE & Editor Integrations

**VS Code Extensions:**
- [Whisper Assistant](https://marketplace.visualstudio.com/items?itemName=MartinOpenSky.whisper-assistant) - Voice-to-text integration
- [Yap - Cursor Extension](https://marketplace.visualstudio.com/items?itemName=rishabhsai.yap-cursor-extension) - Voice input for VS Code/Cursor
- [WhisperX Assistant](https://marketplace.visualstudio.com/items?itemName=mwhesse.whisperx-assistant) - WhisperX integration

**Other Editors:**
- **[whisper-obsidian-plugin](https://github.com/nikdanilov/whisper-obsidian-plugin)** ![GitHub stars](https://img.shields.io/github/stars/nikdanilov/whisper-obsidian-plugin?style=flat-square) - Obsidian integration

### Game Development

- **[whisper.unity](https://github.com/Macoron/whisper.unity)** ![GitHub stars](https://img.shields.io/github/stars/Macoron/whisper.unity?style=flat-square) - Unity game engine integration

### Pipelines & Workflows

- **[WhisperChain](https://github.com/chrischoy/WhisperChain)** ![GitHub stars](https://img.shields.io/github/stars/chrischoy/WhisperChain?style=flat-square) - Pipeline framework for Whisper workflows
- **[whisper-playground](https://github.com/saharmor/whisper-playground)** ![GitHub stars](https://img.shields.io/github/stars/saharmor/whisper-playground?style=flat-square) - Interactive playground for experimentation

---

## Resources

### Official Documentation
- [OpenAI Whisper Repository](https://github.com/openai/whisper)
- [OpenAI Whisper Paper](https://arxiv.org/abs/2212.04356)
- [Hugging Face Whisper Collection](https://huggingface.co/collections/openai/whisper-release)

### Community Awesome Lists
- [awesome-openai-whisper (ancs21)](https://github.com/ancs21/awesome-openai-whisper)
- [awesome-whisper (saharmor)](https://github.com/saharmor/awesome-whisper)
- [awesome-whisper (oenu)](https://github.com/oenu/awesome-whisper)



