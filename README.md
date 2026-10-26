# Nee Doh Simulator

A browser toy: a squishy, gel-filled rounded cube (like the ice-cube style stress toys) hovering in white space, played with by two pink jelly hands. Built with three.js and a custom XPBD soft-body simulation (incompressible gel, strain-stiffening skin, frictional grip, fist-held dough that necks when stretched).

## Play

Open `index.html` in a browser (it loads three.js from a CDN), or serve the folder:

```bash
python3 -m http.server 8765
```

- **Move the cursor** to pull. The hand on the cursor's half of the screen leads; the other hand mirrors it through the centre.
- **Hold the mouse** to squeeze.
- **Scroll** to twist.
- **T** opens a panel of physics sliders.
- Colour swatches (top right) change the gel.
