# AI_PurvaTare


**AI-Powered Knowledge-Graph → Manim Animation Automation**


This repository contains a minimal, reproducible prototype and scaffold for an educational system that turns textbook concepts into animated Manim videos using a Knowledge Graph + LLM-driven slide/script generation.


## What this repo contains
- `examples/gradient_descent.json` — sample slide JSON to render a short video.
- `manim_templates/manim_renderer.py` — minimal script that converts slide JSON into a Manim scene and renders a video.
- `requirements.txt` — Python dependencies for the prototype.
- `docs/presentation_notes.md` — short demo script and talking points for a placement drive.


## Quick start (local)
1. Clone the repo and create a Python environment:


```bash
git clone https://github.com/<your-username>/AI_PurvaTare.git
cd AI_PurvaTare
python -m venv venv
source venv/bin/activate # on macOS / Linux
venv\Scripts\activate # on Windows
pip install -r requirements.txt
