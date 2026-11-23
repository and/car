# Hatchback Parts Explorer

Interactive 3D model of a manual Indian hatchback (generic, Maruti-style layout: transverse 1.2 L petrol, 5-speed manual, front-wheel drive, right-hand drive).

Click any part, or pick it from the list, to see what it does, what to check and the warning signs. Parts are grouped by a workshop periodic-maintenance checklist (A1 Engine to A11 Body) plus cabin diagnostics.

Live site: https://and.github.io/car/

- **Step through parts:** ← → arrow keys, a presentation clicker (Page Up/Down) or the Prev/Next buttons.
- **Engine bay:** the bonnet is always open; the Engine bay view (or **L**) shows labels on the under-bonnet parts laid out like a typical Indian car (https://and.github.io/car/#engine-bay).
- **Stages:** press **S** for an animated walk-through from key-on to switch-off, one step at a time like a debugger (→ next step, Shift+→ next stage, ▶ Play steps), with a live dashboard. Every step has its own link, e.g. https://and.github.io/car/#stage-2-2.
- **Present mode:** press **P** for large text and full screen on a projector.
- **Link to a part:** every part has its own address, e.g. https://and.github.io/car/#radiator

Built with [three.js](https://threejs.org/) r128 loaded from a CDN; a single `index.html` with no build step.
