# Toastmasters_Timer_FTH_Ready

A single-file, FreeToastHost-ready Toastmasters meeting timer that follows Toastmasters brand colors (True Maroon, Loyal Blue, Cool Gray, Happy Yellow) and uses Montserrat (headings) + Source Sans Pro (body).

## Features
- Presets: Table Topics (1–2), Evaluation (2–3), Speeches (5–7, 7–9), plus Custom.
- Count Up / Count Down modes.
- Color cards: Green (min), Yellow (mid), Red (max).
- Start/Pause, Reset, Marks, keyboard shortcuts.
- Optional beep at red/max (muted by default on some browsers until user gesture).
- LocalStorage remembers your last settings.
- Single `index.html` with inlined CSS/JS — drop-in for FreeToastHost or any static host.
- PWA-ready (install prompt appears when served over HTTPS).

## Keyboard Shortcuts
- **Space** — Start/Pause
- **R** — Reset
- **F** — Fullscreen
- **U / D** — Count Up / Count Down
- **1–5** — Presets (1=TT, 2=EV, 3=S5-7, 4=S7-9, 5=Custom)

## How to use on FreeToastHost (FTH)
1. Go to your FTH site editor and create (or edit) a page.
2. Switch to **HTML source** mode.
3. Paste the full contents of `index.html` into the editor and save — or upload `index.html` as a file and link to it.
4. Test on desktop and mobile; add it to your site menu if desired.

> Tip: If you prefer an iframe, upload `index.html` somewhere (e.g., GitHub Pages) and embed with:
>
> ```html
> <iframe src="https://YOUR_HOST/Toastmasters_Timer_FTH_Ready/index.html" width="100%" height="640" style="border:0;border-radius:12px"></iframe>
> ```

## Customize
- Update the brand background gradients or fonts in the `<style>` block.
- Add more presets in the `applyPreset()` switch statement in `<script>`.
- Replace the tiny WAV in the `<audio>` tag if you prefer a different sound.

## Credits
- Built for Toastmasters clubs by your GPT assistant per project specs.
