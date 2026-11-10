# ESSE 4360 · Interactive Optical Payloads Lab

A static, dependency-free teaching companion for Fall 2026 Optical Payloads I, II, and III at York University.

## Interactive modules

- `optics.html`: Imaging geometry (IFOV, GSD, FOV, swath); blackbody reflected-versus-emitted spectra; diffraction/Q/Rayleigh resolution and depth of focus; aliasing; scene-radiance-to-photoelectrons SNR, well capacity and read/dark/background noise; motion smear/TDI; and simplified event-camera threshold demonstrations.
- `index.html`: MTF and contrast explorer, ideal optics/pixels/motion MTF cascade, sampled-image simulation, Fast Auroral Imager example and design exercises.

## Deploy to GitHub Pages

Upload **all five files** (`index.html`, `style.css`, `script.js`, `optics.html`, `optics.js`) to the **root** of `VithurshanSuthakar/Modular_Transfer_Function`. Go to Repository → Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save.

Published paths should be:

- `https://vithurshansuthakar.github.io/Modular_Transfer_Function/`
- `https://vithurshansuthakar.github.io/Modular_Transfer_Function/optics.html`

## Scientific scope

The dynamic figures are educational models, not calibrated end-to-end instrument simulators. Geometry assumes nadir viewing and flat Earth. The spectral chart is an ideal Planck/solar-reflection approximation without atmosphere. Diffraction/Q use ideal unobstructed circular apertures. SNR treats a chosen **in-band** radiance as though photons are characterized by the selected effective wavelength. Event-camera visualizations are deterministic threshold demonstrations; they do not model real camera circuit or noise behavior. TDI assumes ideal synchronization and shot-limited signal accumulation. Real optics include stray light, distortion, aberrations and platform jitter.

Presets and equations are drawn from the uploaded *Optical Payloads I*, *Optical Payloads II*, and *Optical Payloads III* (2026) slide decks. All rendering is original canvas output.
