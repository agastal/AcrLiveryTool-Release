# Changelog

## [0.4.0] - 2026-10-16

A new look, the game's folder can be chosen by hand, and the window opens where you left it.

### New
- *Preparing the cars* shows the game folder it reads from, and *Choose the game folder…* picks another one,
  for example when the game is not found in your Steam libraries. The app remembers your choice.
- The window opens where you left it, with the same size, and maximized if it was.

### Changed
- A new orange colour for the active buttons and the sliders.
- The layer buttons are icons: + Paint, + Text, + Image, + Texture, Duplicate and Delete. Their names show
  when you hover them.

## [0.3.0] - 2026-10-15

The export button moves to the sidebar, and the app shows where to race your livery.

### New
- *App → ACRK Challenge: races and standings…* opens ACRK Challenge's invitation in your browser, in the
  app's language: weekly challenges and standings for Assetto Corsa Rally drivers.
- After an export, the export window suggests taking the livery to a race there.

### Changed
- *Export to the game…* is now the last button of the sidebar, below the base coat, instead of a
  button in the top bar. *File → Export to the game…* and Ctrl+E work as before.

## [0.2.0] - 2026-10-15

The first public version: a 3D livery editor for every car of Assetto Corsa Rally.

### New
- All 18 cars of the game, prepared from your own installation on first start, each with its own livery
  as a starting point and the official UV template as a guide.
- Layers with masks, blend modes and their own roughness, metallic and clear coat.
- Brushes that paint in 3D, across panels without seams: round, spray and stamps, with left/right symmetry.
- Images and text placed on the car, also mirrored to the other side.
- Undo and redo; project files (`.acrlivery`).
- *Export* writes the livery into the game's liveries folder; the base coat colour is written as the game
  reads it.
- Menus in a top bar (File, Edit, App); the interface in English, Italian, French, German and Spanish (the
  system's language, else English; it can be changed from the App menu).
- Updates from this repository, checked at start and daily, installed with one click; the app installs only
  a setup whose signature it can verify.
