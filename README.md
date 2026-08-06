<div align="center">

<img src="https://storage.googleapis.com/chirag-dahiya-portfolio-assets/juno-landing-page/og-image.png" alt="Juno, the private on-device call co-pilot" width="640" />

<h1>Juno</h1>

<p><strong>A private, on-device meeting co-pilot for macOS and Windows.</strong><br/>
Live transcription, real-time assist, and living notes for your calls. Your meetings stay on your machine.</p>

<p>
  <a href="https://juno.chiragdahiya.com"><strong>juno.chiragdahiya.com</strong></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/chiragd03/juno-meeting-copilot/releases/latest">Download the latest release</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/chiragd03/juno-meeting-copilot/issues/new/choose">Report an issue</a>
</p>

</div>

---

## What Juno does

Juno listens alongside your call and helps you in the moment, without anything leaving your device.

- **Pre-call setup:** paste in context and a goal so answers stay on target
- **Live Assist and Notes:** an answer the moment a question lands, plus a self-updating notes board
- **Fully on-device:** transcription and search run locally; only the text you send to your own model ever leaves
- **Bring your own model:** any provider, your own key, no per-seat pricing
- **Search across every past call:** with citations back to the exact conversation
- **Local MCP server:** let your own AI assistant query your meeting history, read-only and off by default
- **Teams auto-detect:** starts and stops capture on its own

<div align="center">
<img src="https://storage.googleapis.com/chirag-dahiya-portfolio-assets/juno-landing-page/juno-guard.png" alt="" width="150" />
<img src="https://storage.googleapis.com/chirag-dahiya-portfolio-assets/juno-landing-page/juno-magnify.png" alt="" width="150" />
<img src="https://storage.googleapis.com/chirag-dahiya-portfolio-assets/juno-landing-page/juno-phones.png" alt="" width="150" />
</div>

There's a full walkthrough, with videos, on the website: **[juno.chiragdahiya.com](https://juno.chiragdahiya.com)**

## Download

Grab the latest build for your platform from the **[Releases page](https://github.com/chiragd03/juno-meeting-copilot/releases/latest)**:

| Platform | File |
| --- | --- |
| macOS (Apple Silicon) | `Juno_arm64.dmg` |
| macOS (Intel) | `Juno_x86_64.dmg` |
| Windows | `Juno_..._x64-setup.exe` |

macOS note: native system-audio capture needs macOS 14.2 or later; on older versions Juno uses BlackHole. Apple Silicon is the primary, most-exercised path.

## This repository

This is the home for **Juno's releases, issues, and feature requests**. It's where you download builds, tell me what's broken, and suggest what to build next. Every issue and request here gets read.

### Report a bug or request a feature

Open an issue and pick a template: **[New issue](https://github.com/chiragd03/juno-meeting-copilot/issues/new/choose)**

For bugs, please attach a **debug bundle** so it can be diagnosed quickly: in Juno, go to **Settings > Help & feedback > Export debug bundle**. The bundle contains app logs and system info only. It does **not** include your meetings, transcripts, or API keys.

## Privacy

Juno is built around one idea: your calls are yours. Audio and transcript never leave your machine, transcription and search run locally, and the only thing that ever goes out is the text you choose to send to the model you picked, on your own key.

---

<div align="center">
<sub>Built by <a href="https://chiragdahiya.com">Chirag Dahiya</a>.</sub>
</div>
