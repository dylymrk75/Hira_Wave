# Hira_Wave
# Hira-Joshi Wave Studio

A standalone, browser-based generative polyrhythmic sequencer and ambient soundscape engine. Built for live performance, hardware MIDI sequencing, and deep-focus audio generation.

## The Philosophy
Hira-Joshi Wave Studio treats the browser as a hardware instrument. It uses a physics-based collision engine where pendulums swing back and forth across custom boundary shapes. Every collision triggers a note locked to the Japanese **Hirajoshi scale** (Root, Major 2nd, Minor 3rd, Perfect 5th, Minor 6th).

By slightly offsetting the frequency of each pendulum, the engine generates complex, endlessly shifting polyrhythms that drift in and out of phase (Unison → Serpent → Crossing → Chaos → Re-Align).

## Core Features
* **Web MIDI Integration:** Route generated sequences out of the browser directly into hardware synthesizers (e.g., Korg Volca Keys, NTS-1 mkII) via USB or an audio interface (like the Edirol UA-25).
* **Multi-Channel Loop Banks:** Capture live "slices" of the sequence and loop them independently. Assign different loops to different MIDI channels to drive multiple hardware synths simultaneously.
* **Browser Synthesis Engine:** Built-in Web Audio API synthesizers ranging from Harps and Pianos to FM Bells and Chiptune squares.
* **Triple Audio Sampler:** Three independent sample slots (A, B, and C) allowing you to upload `.wav`, `.mp3`, or `.m4a` files (or record directly from the mic) and trigger them via the physics engine.
* **Procedural Ambience:** Infinite, algorithmically generated noise beds (Brown noise ocean waves, Pink noise rain, Vinyl crackle, Fireside pops, and sweeping Prairie winds) layered with a custom ambient track uploader.
* **Zen Mode:** A distraction-free, full-screen visualizer for live performances or ambient listening.

## Output Modes
* **BROWSER SYNTH:** All audio is generated internally through the computer speakers/headphone jack.
* **DAW / MIDI ONLY:** Internal synthesis is muted. The engine acts purely as a MIDI brain sending note data to outboard gear or a DAW.
* **HYBRID:** Both internal audio and external MIDI are triggered simultaneously. 

## Visual Engine
The UI relies on an accordion-style hardware rack to manage parameters without context-switching. The visualizer supports 16 aesthetic themes, including 80s Kankyo Ongaku-inspired ambient horizons (Resonance) and high-contrast environments for live video overlays. 
