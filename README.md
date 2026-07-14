# SyncLingo — real-time voice translation for games & voice chat

**SyncLingo** is a **real-time voice translator for Windows 10/11**, built for **online games and Discord**. Hear other players in **your** language with an **in-game subtitle overlay**, and let them hear **you** in **theirs** — with a focus on **low latency**. Run speech recognition **locally with Whisper on your GPU**, or bring your own cloud API keys.

👉 **Website:** https://synclingo.app · **Download:** https://synclingo.app/download/ · **Pricing:** https://synclingo.app/#pricing

> This repository hosts the **release builds and the auto-updater feed** for SyncLingo. It does not contain source code.

## Download

Get the latest Windows installer from the [**Releases**](https://github.com/maksam07/synclingo-releases/releases/latest) page, or from the [download page](https://synclingo.app/download/) on the site.

Windows may show a SmartScreen prompt on first run (the app isn't code-signed yet) — click **More info → Run anyway**.

## What it does

- **Two-way translation** — understand other players *and* be understood. Their speech becomes subtitles in your language; your voice reaches them in theirs.
- **In-game subtitle overlay** — read translations on top of the game, no alt-tabbing.
- **Works with any game or app** — captures system audio (loopback), so it works with any title, Discord, or voice app.
- **Low latency** — tuned for speed over perfect accuracy, with streaming recognition where the provider supports it.
- **Local & private option** — run speech recognition on your own GPU with local **Whisper** (NVIDIA/AMD/Intel), no STT cloud and no per-use bill.
- **Your providers, your keys** — swap STT/translation/TTS between Deepgram, AssemblyAI, OpenAI, ElevenLabs, DeepL, Google, or local Whisper & Windows voices. Keys are stored locally.
- **Lightweight** — a small native Windows app (Tauri, system WebView), not a heavy Electron build.

## How it works

- **Incoming — understand others:** SyncLingo captures game/Discord audio, transcribes and translates it, and shows subtitles (and optional spoken audio) in your language.
- **Outgoing — be understood:** you speak into your mic; listeners hear your voice in their language, routed through a free **VB-Cable** virtual microphone.

## Pricing

A license unlocks the app: **$5 / 3 months**, **$9 / 6 months**, **$15 / 12 months**. You also pay for any cloud STT/MT/TTS you use with your own API keys — or run a **local Whisper + Windows TTS + free Google translate** setup for near-zero cost beyond the license. See [pricing](https://synclingo.app/#pricing).

## Links

- 🌐 Website — https://synclingo.app
- ⬇️ Download — https://synclingo.app/download/
- 💳 Pricing — https://synclingo.app/#pricing
- 📖 Guide: *How to translate game voice chat in real time* — https://synclingo.app/blog/translate-voice-chat-in-games/
