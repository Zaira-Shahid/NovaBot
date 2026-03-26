# NovaBot AI

A fully-featured AI assistant with vision, voice, and document understanding — built with Llama 4 and deployed live.

**Live Demo:** https://nova-bot-two.vercel.app

---

## What Makes NovaBot Different

Most chatbots are text-only. NovaBot sees, listens, and reads.

- Upload an image — NovaBot analyzes and describes it using vision AI
- Upload a PDF or document — NovaBot reads and summarizes it
- Speak to it — voice input auto-transcribes and sends
- Ask anything — powered by Llama 3.3 70B for text and Llama 4 Scout for vision

---

## Features

- Natural conversation with memory across the session
- Image analysis using Llama 4 Scout vision model
- PDF and document reading using PDF.js text extraction
- Voice input using Web Speech API with auto-send
- Code highlighting with syntax coloring
- Clean pastel UI — professional and responsive
- Zero backend — runs entirely in the browser

---

## Tech Stack

| Feature | Technology |
|---------|------------|
| Text AI | Llama 3.3 70B via Groq API |
| Vision AI | Llama 4 Scout 17B via Groq API |
| PDF Reading | PDF.js |
| Voice Input | Web Speech API |
| Code Highlighting | Highlight.js |
| Deployment | Vercel |
| Frontend | HTML, CSS, JavaScript |

---

## How It Works
```
User input (text / image / PDF / voice)
              ↓
     Input type detected
              ↓
  Text → Llama 3.3 70B (Groq)
  Image → Llama 4 Scout Vision (Groq)
  PDF → PDF.js extracts text → Llama 3.3 70B
  Voice → Web Speech API → auto-transcribe → send
              ↓
     Formatted response rendered
```

---

## Local Setup
```bash
git clone https://github.com/Zaira-Shahid/nova-bot.git
cd nova-bot
```

Open `index.html` in Chrome — no build step, no server needed.

Add your Groq API key in `index.html`:
```javascript
const GROQ_KEY = "your_groq_api_key_here";
```

Get a free API key at: https://console.groq.com

---

## Why Groq?

Groq runs inference at 500+ tokens per second — significantly faster than most alternatives, making NovaBot feel instant and responsive.

---

## Author

**Zaira Shahid**
- LinkedIn: [linkedin.com/in/zaira-shahid-](https://linkedin.com/in/zaira-shahid-)
- GitHub: [github.com/Zaira-Shahid](https://github.com/Zaira-Shahid)
