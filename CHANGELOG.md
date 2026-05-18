# Candy-Bot Update Changelog

## Version 6.0.0 - Major Release
**Released:** 2026-05-19

### New Features
- **HF Space Image Generation** — All image generation now runs on HuggingFace Spaces (4× A10G GPU, 96GB VRAM) for dramatically faster, higher-quality results
- **Auto-Pause / Auto-Wake** — Space automatically wakes before generation and pauses immediately after — zero idle GPU cost
- **8 Curated NSFW Models** — Xenocock Flux V2, Universal Special Model Pro, Universal Model Ultra, Pony Realism, NSFW Wan 1.4B, NSFW 1.4, NSFW Realism - Real Life, Anime NSFW High Quality
- **Roleplay Sexual Orientation Control** — Select Heterosexual, Homosexual, or Bisexual before starting a session; AI enforces strict boundary constraints
- **Animal Character Type** — Animals can be added to roleplay sessions; they are restricted to third-person actions only and cannot speak
- **Slow-Burn Explicit AI Pacing** — AI responses are 700-1200 words, multi-turn breakdowns enforced; scenes never end in a single turn
- **Finish Roleplay Button** — "Start Roleplay" button transforms to "Finish Roleplay" (dark red) after session begins
- **Saved Chats Library Tab** — Save, name, load, and delete roleplay sessions from a dedicated Saved Chats tab in the Library

### Improvements
- Roleplay saves now persist to a local `RoleplaySaves/` folder inside the application directory
- Image generator model dropdown now shows clean display names with the Space handling all routing
- Error messages updated throughout to reflect cloud-based generation

## Version 5.0.0 - Major Release
**Released:** 2026-04-23

### New Features
- **Multi-Character Roleplay** — Add up to 6 AI characters per session with full per-character profiles
- **Character Library** — Persistent library of up to 12 saved characters; pick and reuse across any session
- **Detailed Character Cards** — Height, Body Type, Hair Color, Eye Color, Personality Archetype, Relationship, and Special Traits per character
- **Save to Library** — Save any active character card to the persistent library with one click
- **Create / Edit in Library** — Build new characters directly in the library without starting a session
- **Full Help & Walkthrough Tab** — Complete step-by-step guide inside Settings covering every app feature
- **Detail Field Persistence** — All character profile details now fully saved and restored in .candyrp files
- **Resizable Windows** — All major windows now support free resizing

### Improvements
- Session save/load now preserves all detailed profile fields
- Multi-character AI prompt engineering with per-character dialogue prefixing
- Tag list expanded and alphabetically sorted (Safe + Mature tiers)
- Intensity scale updated with sharper level descriptions up to level 10

## Version 4.4.1
**Released:** 2026-04-22

### Features
- Desktop Widget with AI-powered chat
- Venice AI integration
- ElevenLabs voice synthesis
- Multi-drive file search
- Role play mode with save/load
- DJ Engine
- Settings panel with API key management, themes, and PIN protection
