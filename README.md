# Khushi Koli (KuHuuu) — 19th Birthday Website — v2, 11 Nov 2026

File: `index.html` — single-file, open in any browser / phone. No build step.
Birthday: Thursday 12 November 2026 · born 12 November 2007 · turns 19.
First met: 5 October 2025 (college program, start of first year) → 403 days to her birthday (verified by date arithmetic).

## What changed in v2 (Rajas, 11 Nov 2026, 18:05 IST)
- **Nickname KuHuuu** used warmly throughout: welcome subtitle "For KuHuuu ♡", gallery heading "KuHuuu's Magical Photo Gallery", shayari card, cake copy, letter envelope, finale.
- **Shayari #2 — featured, verbatim** — in a dedicated shayari card AND as the opening of the Roman Hindi letter tab:
  > Pyar mein pagal hain, isliye thode nadaan hain, / Tumhari ek muskurahat pe hum kurbaan hain, / Kehne ko toh bahut kuch hai dil mein, / Bas tumhare saamne aate hi hum bezubaan hain... 🥹
  (The other 5 shayari from his list of 6 are not used, per his selection.)
- **Signature kept:** "Someone who is genuinely happy that your paths crossed" (English letter). The Roman Hindi tab only is signed "Tumhara Rajas", as in the original letter.
- **Gallery: exactly 12 photo frames** (was 8) — because her birthdate is the 12th. His 4 captions cycle 1→4, 1→4, 1→4: "A smile that makes everything brighter." / "Some pictures deserve to be remembered forever." / "Simply beautiful, just the way you are." / "A little sunshine in human form. ☀️"
- **Music:** in-browser WebAudio gentle piano now plays the public-domain "Happy Birthday" melody on a loop (royalty-free, no copyrighted track). Starts only after tapping "✨ Open Your Surprise ✨". Controls: play/pause, mute, volume slider; preference saved in sessionStorage (`kuhuuu-vol`, `kuhuuu-music-muted`, `kuhuuu-sound`).
- **Polish:** 120 twinkling stars, glassmorphism cards, 3-tier CSS cake with strawberries + gold, fuller typewriter letter, animated 0→403 counter, canvas fireworks with heart particles, replay button, custom 💗 cursor on desktop only, reduced-motion support, fullscreen photo viewer with Esc/close.

## What's in it
- Welcome: night sky, 120 stars, floating hearts, falling petals, glowing heart, "Khushi Koli" letter-by-letter, "Open Your Surprise" → click sound, heart explosion, smooth scroll, music starts.
- Cake: exactly 19 flickering candles, each tappable; "Blow Out the Candles" → all out + smoke/particles; wish verbatim: "May every little wish hidden in your heart find its way to reality. You deserve all the happiness in this world. ❤️"; "Relight the Candles".
- Gallery: 12 polaroid frames, 3D tilt/zoom on hover, click opens fullscreen viewer. Loads `photos/photo-01.jpg` … `photos/photo-12.jpg` with lazy loading; `onerror` falls back to an elegant placeholder. **No AI faces, no generated photos, no stock faces — placeholders only until Rajas uploads real photos.**
- Story: 403-day counter, timeline 5 Oct 2025 / days that followed (only talked and laughed together, no invented events) / 12 Nov 2026.
- Letter: envelope tap-to-open, typewriter reveal, tabs English (verbatim from brief) + Roman Hindi "Pehli Mulaqat" (shayari #2 opening, short body, 403 days, signed "Tumhara Rajas"). Title "Pehli Mulaqat" is still first-option default, not confirmed.
- Surprises: 6 floating hearts with his 6 messages verbatim + "Tap for a Little Happiness 💝" cycling them.
- Finale: pink/gold fireworks canvas, heart particles, falling petals, "Happy 19th Birthday, Khushi Koli! ❤️" + closing paragraphs verbatim + "Some surprises are created with code, but the feelings behind them are real. 💗"

## Still needed from Rajas
1. **12 real photos** — create `photos/` inside this folder and drop `photo-01.jpg` … `photo-12.jpg` (see the comment at the top of `index.html`). No photos have been uploaded yet as of 11 Nov 18:05 IST.
2. Optional: a music audio file to replace the WebAudio piano, if he wants his own track.
3. How to share it: GitHub + Cloudflare Pages deployment is the parent agent's next step (not done by this rebuild).

## Not done / caveats
- Not hosted / not sent to Khushi. Do not share with anyone except Rajas.
- Not tested on his phone yet — preview on desktop/mobile browser first.
- Verification performed: JS extracted and `node --check` passed; all IDs referenced in JS were grepped against the HTML (see rebuild report).
