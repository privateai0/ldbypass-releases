# LDBypass

**Invisible AI overlay for macOS proctored exams**

[![Discord](https://img.shields.io/badge/Discord-Join-5865F2?logo=discord&logoColor=white)](https://discord.gg/saMaxDk5)

LDBypass renders ChatGPT and Claude in a private overlay window on macOS. The overlay is invisible to screen capture, screen recordings, screen sharing, and window enumeration — operating at the macOS window server level below all proctoring software. Compatible with LockDown Browser, Proctorio, ProctorU, Honorlock, ExamSoft, Safe Exam Browser, and Respondus Monitor.

🌐 **[ldbypass.com](https://ldbypass.com)** · 💬 **[Discord](https://discord.gg/saMaxDk5)** · 📦 **[Download Latest](https://github.com/privateai0/ldbypass-releases/releases/latest)**

---

## Quick Start

1. **Download** — grab LDBypass-universal.zip from [Releases](https://github.com/privateai0/ldbypass-releases/releases/latest)
2. **Unzip & open** — double-click the .zip, then open LDBypass.app
3. **Allow in System Settings** — macOS blocks unsigned apps by default. Go to **System Settings → Privacy & Security → Open Anyway**
4. **Press ⌃⌘L** — the invisible AI overlay appears. That is it.

> **Free 1-hour trial** — no credit card required. Create an account inside the app.

## Features

- **Invisible overlay** — excluded from CGWindowList, screen capture APIs, and all screen recording
- **AI providers** — ChatGPT, Claude, or local AI via Ollama
- **Keyboard-driven** — toggle with ⌃⌘L, quit with ⌃⌘Q, switch AI with ⌃⌘ 1/2/3
- **Adjustable transparency** — ⌃⌘↑ more opaque, ⌃⌘↓ more transparent
- **Session persistence** — conversations survive app restarts
- **In-app auth** — sign up with email or Discord directly in the app
- **In-app purchases** — buy time without leaving the app
- **Universal binary** — native on Apple Silicon (M1–M4) and Intel

## Compatibility

| Proctoring Software | Status | Notes |
|---|---|---|
| Respondus LockDown Browser | ✅ Undetectable | Window excluded from enumeration |
| Proctorio | ✅ Undetectable | Invisible to Chrome extension APIs |
| ProctorU / Meazure Learning | ✅ Undetectable | Not visible in screen share |
| Honorlock | ✅ Undetectable | Excluded from screen capture |
| ExamSoft / Examplify | ✅ Undetectable | Below application-level monitoring |
| Safe Exam Browser (SEB) | ✅ Undetectable | Independent of SEB kiosk mode |
| Respondus Monitor | ✅ Undetectable | Not captured by webcam recording |

> Compatibility verified April 2026. [Full compatibility guide →](https://ldbypass.com/guides/ai-overlay-lockdown-browser)

## System Requirements

| Requirement | Minimum |
|---|---|
| macOS | 12 Monterey or later |
| Processor | Apple Silicon (M1/M2/M3/M4) or Intel |
| RAM | ~100 MB |
| Disk | ~5 MB |
| Network | Required for AI providers and license validation |

## Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| ⌃⌘L | Show / hide overlay |
| ⌃⌘Q | Quit LDBypass |
| ⌃⌘1 | Switch to ChatGPT |
| ⌃⌘2 | Switch to Claude |
| ⌃⌘3 | Switch to local AI (Ollama) |
| ⌃⌘↑ | Increase opacity |
| ⌃⌘↓ | Decrease opacity |
| Esc | Release keyboard back to exam |

## Pricing

| Plan | Price | Duration |
|---|---|---|
| Day Pass | \ | 24 hours |
| Week Pass | \9 | 7 days |
| Month Pass | \9 | 30 days |

All plans include a **free 1-hour trial** on signup. No credit card required. Time is wall-clock from activation.

[Get started →](https://ldbypass.com/download)

## FAQ

<details>
<summary><strong>How does the overlay stay invisible?</strong></summary>
LDBypass operates at the macOS window server level. The overlay window is configured with private system APIs that exclude it from CGWindowList enumeration, screen capture, and screen recording. Proctoring software running at the application level cannot detect it.
</details>

<details>
<summary><strong>Do I need a ChatGPT or Claude account?</strong></summary>
Yes. Log into your AI provider in a regular browser first. LDBypass uses your existing session cookies — no separate AI login needed.
</details>

<details>
<summary><strong>What happens if my time runs out during an exam?</strong></summary>
The app provides warnings before expiry and includes a 30-second grace period. You can purchase more time directly in the app without interrupting your session.
</details>

<details>
<summary><strong>Does it work on Intel Macs?</strong></summary>
Yes. LDBypass is a universal binary with native support for both Apple Silicon (M1/M2/M3/M4) and Intel processors running macOS 12+.
</details>

<details>
<summary><strong>Can proctoring software detect LDBypass?</strong></summary>
No. Proctoring software like LockDown Browser, Proctorio, and ProctorU operates at the application or browser level. LDBypass operates at the macOS system level, below what these applications can monitor. The overlay does not appear in any screen capture API, window list, or recording.
</details>

<details>
<summary><strong>How do I get support?</strong></summary>
Join our <a href="https://discord.gg/saMaxDk5">Discord server</a> for real-time help, or open an issue on this repository.
</details>

## Support

- 💬 **Discord** — [discord.gg/saMaxDk5](https://discord.gg/saMaxDk5) — fastest support
- 🌐 **Website** — [ldbypass.com](https://ldbypass.com)
- 🐛 **Bug reports** — [GitHub Issues](https://github.com/privateai0/ldbypass-releases/issues)
- 💡 **Feature requests** — [GitHub Discussions](https://github.com/privateai0/ldbypass-releases/discussions)

## License

LDBypass is proprietary software. All rights reserved. Redistribution or reverse engineering is prohibited.
