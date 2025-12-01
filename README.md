# HopeBot - You Are Not Alone 🫂

**A 100% private, instantly accessible, life-saving mental health first-aid chatbot.**

One single HTML file.  
Zero servers. Zero tracking. Zero accounts.  
Works offline after first visit.  
Detects suicidal ideation or severe distress in real time and immediately connects to crisis hotlines.

Live Demo → https://github.com/LHMisme420/Mental-Health-first-aid-bot.git

## Why HopeBot exists
Every 40 seconds, someone dies by suicide (WHO).  
Millions more are in crisis right now with nowhere safe to turn.

HopeBot was built to be shared in a single link or QR code and be ready to help in under 5 seconds — exactly when someone needs it most.

## Features
- 100% client-side — nothing ever leaves your device
- Real-time suicide/self-harm detection using TensorFlow.js (runs locally)
- Immediate crisis response with global hotlines
- 5-4-3-2-1 grounding exercise
- Works offline after first load (PWA-ready)
- Single file, < 200 lines of code
- Fully open-source & forkable

## Live in one click
https://YOUR-USERNAME.github.io/hopebot

Just open. No install. No sign-up. Works on any phone or computer.

## How YOU can save lives today
1. Star this repo
2. Share the link everywhere (bio, stories, Discord, Reddit, crisis resource lists)
3. Fork & translate into your language
4. Add your local hotlines (see below)

Every share = another life potentially saved.

## Add your country's hotline (takes 10 seconds)
Edit the `HOTLINES` object in `index.html`:

```js
const HOTLINES = {
  US: "988 or text HOME to 741741",
  UK: "Samaritans: 116 123",
  CA: "1-833-456-4566",
  AU: "Lifeline: 13 11 14",
  IN: "AASRA: 91-9820466726",
  // Add yours here →  "YOUR COUNTRY CODE": "Your hotline"
  default: "befrienders.org (find your country)"
};
