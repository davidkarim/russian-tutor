# Russian Tutor – 7-day audio-first course

One self-contained file: `index.html` (no build, no libraries, no network calls).

## Run it
- **Mac:** double-click `index.html` (opens in your default browser; Chrome, Safari or Edge all work).
- **iPhone:** the file must be opened in a *browser*, not the Files preview.
  - Easiest: on your Mac, in this folder run `python3 -m http.server 8000`, then on the iPhone (same Wi-Fi) open Safari to `http://<your-mac-ip>:8000` (Mac IP: System Settings → Wi-Fi → Details). Tap Share → *Add to Home Screen* for an app-like icon.
  - Or AirDrop/save `index.html` to your iPhone and use Share → *Open in Safari* (if your iOS version offers it). If progress doesn't stick that way, use the local-server method.
- Tap any button once to start: browsers only allow sound after a tap.

## Sound
The app uses your device's own Russian voice (Web Speech API). If you see an orange "No Russian voice found" note:
- **iPhone:** Settings → Accessibility → Spoken Content → Voices → Russian → download one (e.g. Milena).
- **Mac:** System Settings → Accessibility → Spoken Content → System Voice → Manage Voices… → Russian.
- Chrome/Edge usually have Russian voices online already. Reload the page after adding a voice.
- Can't hear anything on iPhone? Check the volume and the silent switch.

The microphone "Say it" button (Days 4–5) is optional and only appears where the browser supports speech recognition (Chrome/Edge, some Safari). It never blocks you; you always rate yourself with **Got it / Stumbled**.

## How the week works
1. **Day 1–2:** 20 letters in 4 sessions of 5 (look-alike traps В Е Н Р С У Х first). Hear, see, quiz.
2. **Day 3:** last 13 letters, then "Sound it out" word drills (мама, там, да, нет, кот, дом, город, метро, парк, банк, ресторан…).
3. **Day 4–5:** 12 survival phrases: slow, normal speed, then say it back; Day 5 ends with a practice round.
4. **Day 6:** mixed review of letters, words and phrases.
5. **Day 7:** relaxed listening mode: auto-play, no quizzes, pause/next/back.

Every session starts by circling back to tricky/due items (spaced repetition, Leitner boxes), then adds only 3–5 new things. Sessions can be repeated. Pick any day with the Day selector, or "Jump to today".

## Your data
Saved in your browser's localStorage under `ruTutor.v1` (separate per browser/origin, so file:// and http://localhost don't share it). Progress → Export/Import copies it as JSON text; Reset wipes it (asks first).
