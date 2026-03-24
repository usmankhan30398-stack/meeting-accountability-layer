# Meeting Accountability Layer

**Turn messy meeting notes into structured decisions, action items, and a ready-to-send follow-up email — entirely in your browser.**

Most meetings end without clear records of what was decided, who owns what, or whether the meeting needed to happen at all. This tool fixes that. Paste in any notes or transcript, and the Meeting Accountability Layer extracts the signal and gives you a clean operational output in seconds.

---

## Why I Built This

After years in strategy and operations consulting, one pattern showed up constantly: meetings happened, things were discussed, and then nothing moved. Not because people didn't care — but because there was no system to capture decisions and assign ownership in real time.

This tool is the operational layer that should exist at the end of every meeting.

---

## What It Does

| Output | Description |
|---|---|
| **Decision Log** | Every decision made in the meeting, who owns it, and why it was made |
| **Action Item Register** | Tasks with owners, deadlines, and priority levels (High / Medium / Low) |
| **Meeting Necessity Score** | A 1–10 rating for whether the meeting needed to happen, with honest reasoning |
| **Follow-Up Email Draft** | A human-sounding email ready to send to attendees — no editing required |

---

## How It Works

Paste your meeting notes or upload a `.txt` transcript. The tool sends your input to Claude (Anthropic's API) with a structured prompt that extracts all four outputs as a single JSON object, then renders each one in a clean tabbed interface.

No backend. No data storage. Your notes go directly from your browser to the Anthropic API and nowhere else.

---

## Tech Stack

- **HTML / CSS / JavaScript** — single-file, no framework, no build step
- **Anthropic API** — `claude-sonnet-4-20250514` processes and structures the output
- **GitHub Pages** — deployed as a static site, zero infrastructure
- **Google Fonts** — Inter + JetBrains Mono

---

## Live Tool

**[usmankhan30398-stack.github.io/meeting-accountability-layer](https://usmankhan30398-stack.github.io/meeting-accountability-layer)**

You'll need an Anthropic API key to use the tool. Enter it in the banner at the top of the page — it's stored only in your browser's local storage and never sent anywhere except the Anthropic API.

---

## Use Cases

- Post-meeting follow-up for ops and product teams
- Chief of Staff workflows — weekly leadership syncs, board prep
- Startup teams running fast with limited admin support
- Anyone who leaves meetings and can't remember what was decided

---

## Built By

[Usman Khan](https://github.com/usmankhan30398-stack) — Strategy & Operations professional based in San Francisco. Background in consulting at CGI and Oracle Cerner, MBA from Carnegie Mellon Tepper. Open to ops, product ops, and Chief of Staff roles at startups.
