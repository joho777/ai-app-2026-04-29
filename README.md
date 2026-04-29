# VibeVoice Studio — Voice AI Prompt Lab

A polished, interactive single-page web app inspired by the trend "VibeVoice: Open-source frontier voice AI".

## What it does

- **Prompt composer** for voice model system prompts (persona, scenario, mic chain, style notes, guardrails)
- **Real-time KPIs** that update as you tune knobs: estimated latency, realism score, and consistency risk
- **Streaming timeline simulator** that models chunking behavior and highlights where artifacts/drift can show up
- **Local audio preview** using WebAudio synthesis (a speech-like signal; not real voice cloning)
- **Shareable URL state**, prompt export to a text file, and scene save/compare

## Live demo

After GitHub Pages is enabled:

- https://joho777.github.io/ai-app-2026-04-29/

## Trend inspiration

- VibeVoice repository: https://github.com/vibevoice/vibevoice

## Notes

This app is entirely client-side (single `index.html`) and makes no network requests.
