<a href="https://jacknet1984.github.io/textureonyourSTL/" target="_blank">
  <img src="https://github.com/user-attachments/assets/5c661173-3b06-4c5c-9ac9-8610893894d2" alt="Anteprima del progetto" width="100%" />
</a>

<img width="2473" height="1239" alt="PRONTO4" src="https://github.com/user-attachments/assets/e7026570-165a-4f04-876d-52a17224147e" />

<img width="2470" height="1246" alt="PRONTO2" src="https://github.com/user-attachments/assets/219f8a8b-9226-4929-a828-e72058748b94" />

Repository: jacknet184/textureonyourSTL
------------------------------------------------------------------------

Texture on your STL is a web-based application designed to apply 3D 

textures, patterns, and surface reliefs directly onto STL files right 

inside your web browser. 

No heavy software installations or complex 3D modeling experience required. 

It is an ideal tool for 3D printing enthusiasts, makers, and designers 

who want to quicky customize their models before slicing.

------------------------------------------------------------------------

- Zero Installation: Runs entirely in your modern web browser via WebGL.

- STL File Import: Load your own 3D STL models directly from your PC.

- Real-Time Projection: Apply and adjust textures/reliefs dynamically.

- Export Ready: Save modified models directly for slicing software 

  (Bambu Studio, OrcaSlicer, Cura, PrusaSlicer, etc.).

------------------------------------------------------------------------
HOW TO USE (LIVE DEMO)
------------------------------------------------------------------------

You can use the live online version directly in your browser at:

https://jacknet1984.github.io/textureonyourSTL/
*(or simply click on the image above)*

LOCAL RUN:

If you prefer running it locally on your computer:
1. Download or clone this repository.
2. Open the "index.html" file with any modern web browser.

------------------------------------------------------------------------
BUILT WITH
------------------------------------------------------------------------
- HTML5 / CSS3
- JavaScript (ES6)
- Three.js (3D Rendering Library)
------------------------------------------------------------------------
LICENSE
------------------------------------------------------------------------
This project is open-source and released under the MIT License.
========================================================================

<a href="https://makerworld.com/@Disagioinside" target="_blank">
  <img src="https://github.com/user-attachments/assets/e6e2db43-23cd-4c76-a912-4b01600bbf42" alt="MakerWorld Profile" width="100%" />
</a>




UPDATE:

What's new

Interface

Two languages, Italian / English. The app opens in English; the EN / IT switch is at the top of the panel. The exported zip (file names, README) also follows the selected language.
Four views like in Blender: Top, 3D, Front and Right. You can click in any view to place the image. Double-click a view to enlarge it to full size; double-click again to get the four views back.
Redesigned left panel: wider, two columns on large screens, rounded cards, nicer buttons with icons. The Prepare files for printing button is always visible at the bottom, no scrolling needed.

Supported files

Models: STL, 3MF and OBJ.
Images: PNG, JPG, WebP, GIF, BMP, SVG.
Background removal right in the site, with adjustable tolerance and an option to also remove inner areas of the same color.

Export

Fixed the "points to repair" warnings reported by slicers: the colored parts are now closed meshes (0 open edges and 0 invalid edges in our tests).
Colors stay assigned as separate parts with their own extruder, so they are not lost by mesh repair.
Changes
Removed hand drawing and the move arrows, which did not work as intended. To move the image, click on the model.
Good to know
Background removal works best on plain backgrounds.
The four views are designed for large screens; on a phone, double-click a view to enlarge it.
If your slicer still reports errors on the exported file, please open an issue and tell us which slicer you use.
