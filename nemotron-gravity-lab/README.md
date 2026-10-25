# Cheap Model of the Week: NVIDIA Nemotron 3 Ultra

A reproducible JavaScript debugging challenge.

## Contents
- `gravity_lab_BROKEN.html` — the deliberately broken Canvas simulation used in the video
- `repair_prompt.txt` — the repair instructions

## How to reproduce
1. Open `gravity_lab_BROKEN.html` locally in a browser.
2. Verify the three bugs: dragging repels particles, Pause doesn't freeze the simulation, and Reset appends 240 more particles rather than resetting to 240.
3. Open NVIDIA Nemotron 3 Ultra on OpenRouter, paste `repair_prompt.txt`, then append the *entire contents* of `gravity_lab_BROKEN.html`.
4. Save the model's full HTML output as a new `.html` file and open it in the browser.
5. Check the three behaviors and whether the visual design remains intact.

## Reproducibility note
The repaired code from the video is not included in this package; it contains the deliberately broken starter plus the repair instructions. Free endpoint access may change.
