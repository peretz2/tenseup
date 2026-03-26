# TenseUp — AI English Teacher

An AI-powered iOS app that helps users master English grammar and pronunciation through real-time conversation practice and intelligent feedback.

<!-- <p align="center">
  <img src="screenshots/screenshot1.png" width="200">
  <img src="screenshots/screenshot2.png" width="200">
  <img src="screenshots/screenshot3.png" width="200">
</p> -->

## Tech Stack

| Layer | Technology |
|-------|-----------|
| **UI** | SwiftUI |
| **Data** | SwiftData |
| **AI Chat** | OpenAI GPT-4 API |
| **Speech-to-Text** | OpenAI Whisper API |
| **Payments** | RevenueCat |
| **Sync** | CloudKit |
| **Architecture** | MVVM |

## Key Features

- **AI Conversation Partner** — Practice English with GPT-4 in real-time dialogue
- **Speech Recognition** — Speak naturally and get transcription via Whisper
- **Grammar Correction** — Instant feedback on tense usage, word order, and common mistakes
- **Pronunciation Practice** — Record and compare your speech
- **Progress Tracking** — Track improvement over time with SwiftData persistence
- **Subscription Tiers** — Free, Premium, and Premium+ via RevenueCat
- **iCloud Sync** — Progress syncs across devices via CloudKit

## Architecture

```
TenseUp/
├── Models/          # SwiftData models
├── Views/           # SwiftUI views
├── ViewModels/      # Business logic (MVVM)
├── Services/        # OpenAI API, Whisper, RevenueCat
└── Utils/           # Helpers and extensions
```

## Monetization

| Tier | Features |
|------|----------|
| **Free** | Limited daily conversations |
| **Premium** | Unlimited conversations, all grammar exercises |
| **Premium+** | Everything + advanced pronunciation analysis |

## Links

- [Support](https://peretz2.github.io/tenseup/support.html)
- [Privacy Policy](https://peretz2.github.io/tenseup/privacy.html)
- [Terms of Use](https://peretz2.github.io/tenseup/terms.html)
