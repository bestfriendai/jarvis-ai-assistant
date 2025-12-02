# Changelog

All notable changes to Jarvis AI Assistant will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.1.0] - 2025-12-01

### Added
- **Local Whisper Model Support**: On-device speech-to-text transcription using OpenAI's Whisper model for enhanced privacy and offline capability
- **Settings UI**: New settings panel to configure transcription provider (Deepgram, Groq, or Local Whisper)
- **Model Selection**: Choose between different Whisper model sizes (tiny, base, small, medium) based on speed vs accuracy needs

### Fixed
- **WPM (Words Per Minute) Calculation**: Fixed inaccurate WPM tracking and display
- **Nudge Handler**: Resolved issues with nudge notifications not triggering correctly

### Improved
- **DMG Build Process**: Enhanced macOS DMG creation with proper background image and code signing for macOS 15 compatibility
- **Performance**: Optimized transcription pipeline for faster response times

## [1.0.0] - 2025-11-15

### Added
- Initial release of Jarvis AI Assistant
- Voice-activated AI assistant with push-to-talk (Fn key)
- Real-time speech-to-text transcription
- AI-powered text generation and editing
- Context-aware suggestions based on active application
- Native macOS integration with accessibility features
- Support for both Intel and Apple Silicon Macs
