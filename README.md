# JupiTools Magnet Maker — Phase 01

Interactive prototype for designing 3D printable magnets. It includes shape and dimension controls, rounded corners, inner contour, front and body colors, text, rear magnet pockets, a 3D preview, and STL/3MF export.

## Run locally

Serve this directory with any static web server, then open `index.html`. For example:

```sh
python3 -m http.server 8000
```

Open <http://localhost:8000/>. An internet connection is needed for the JavaScript libraries and optional font assets loaded from a CDN.

## 3MF colors

The 3MF export contains separate parts and desired colors, with part-to-filament slot assignments for slicers. Check that the filament colors assigned to those slots in your slicer match the chosen colors before slicing. The file does not contain a printer profile or G-code.

This is a Phase 01 prototype. Check geometry and slicer settings before printing.
