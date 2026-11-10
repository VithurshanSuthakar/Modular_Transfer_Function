# MTF Lab — ESSE 4360 Optical Payloads III

An interactive, static teaching companion to the Fall 2026 Optical Payloads III lecture. No dependencies, API keys, build step, or server required.

## Publish on GitHub Pages

1. Create a new public GitHub repository, for example `mtf-lab`.
2. Upload `index.html`, `style.css`, and `script.js` to the repository root (not inside a nested folder).
3. Go to **Settings → Pages → Build and deployment**.
4. Choose **Deploy from a branch**, select **main** and **/(root)**, and save.
5. After deployment, the website is available at `https://YOUR-USERNAME.github.io/mtf-lab/`.

For local testing, open `index.html` in a browser, or run `python -m http.server 8000` in this directory and visit `http://localhost:8000`.

## Scope and caveats

- Contrast demonstration uses a Gaussian MTF.
- Diffraction MTF uses the exact incoherent, unaberrated circular-aperture expression.
- Pixel MTF uses a one-dimensional rectangular-pixel sinc model.
- Motion MTF uses a constant-velocity rectangular smear model along the measurement direction.
- The point-source and image-lab illustrations use Gaussian approximations and are schematic, not a full physical optics or sensor simulation.
- FAI 0.35 stripe contrast is an approximate laboratory bar-target measurement and should not be treated as an exact sinusoidal MTF.
- Nyquist is a sampling limit, not a physical optical cutoff. Frequency components above Nyquist can alias.

Based on the user-provided *Lecture_3_York_University.pdf*, particularly slides 5–17, 22–25, 33–34, and 47.
