# Explainers

Interactive, visual explainers. Each one is a single self-contained HTML page: minimal text, mostly things you can see, drag and hear.

| Explainer | What it covers |
|---|---|
| [Sound, made visible](sound/) | Vibration → waveform → harmonics → Fourier transform → spectrogram → mel spectrogram. Background for speech and audio models (text-to-speech and similar). |

## Run locally

```bash
python3 -m http.server 4173
```

Then open http://localhost:4173/. Each page also opens by double-clicking its `index.html`, except features that need a real web address (the microphone step in the sound explainer).

## Adding an explainer

1. Create a folder with a short name, for example `attention/`.
2. Put a self-contained `index.html` in it (no build step, no dependencies).
3. Add a card for it in the root `index.html` and a row in the table above.
