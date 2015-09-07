# Pixels

Mac-centric Adobe Photoshop tips/ticks/templates used for making pixel art, specifically for video games.

## Application and tool configuration

Settings used to create pixel-precise art.

### New document

Make sure you’re using pixel units and, depending on goal, the canvas size is in multiples of 16. For example:

![new document](https://cloud.githubusercontent.com/assets/218624/9707947/8fce0c54-54c9-11e5-9334-aaf8e2f98b73.png)

### Preferences

1. Use <kbd>⌘</kbd> + <kbd>K</kbd> to open Photoshop’s preferences.
1. Navigate to <kbd>Guides, Grids & Slices</kbd>
1. Set ”Gridline Every” to your tile size (e.g., 16, 32, 64, etc.)
1. Set “Subdivisions” to 1

![screenshot 2015-09-06 20 41 01](https://cloud.githubusercontent.com/assets/218624/9708911/a1f70152-54d7-11e5-8e34-759a43b09523.png)

### Grid snapping

Be aware of grid snapping. When drawing, if the grid is visible, you typically want this feature **turned off**.

1. Show the grid using <kbd>⌘</kbd> + <kbd>'</kbd>
1. With the grid on, navigate to <kbd>View</kbd>: <kbd>Snap To</kbd> and un-check <kbd>Grid</kbd>

 ![screenshot 2015-09-06 20 47 00](https://cloud.githubusercontent.com/assets/218624/9708976/757c4852-54d8-11e5-9b05-efa648b6cce0.png)

### Pixel rulers

Showing the rulers is optional:

1. Press <kbd>⌘</kbd> + <kbd>R</kbd> to show (or hide) rulers
1. Press <kbd>^</kbd> + <code>RMB</code> click the ruler and choose “Pixels” from the contextual menu:

 ![pixel rulers](https://cloud.githubusercontent.com/assets/218624/9707847/1fc3853e-54c8-11e5-8ca2-212f47236d9b.png)

### Pixel brush

Having a 1 pixel brush is key to making good pixel art in Photoshop:

1. Download [`1px.abr`](1px.abr)
1. Choose <kbd>Edit</kbd>: <kbd>Presets</kbd> > <kbd>Preset Manager…</kbd>
1. In the “Preset Manager” window, choose <kbd>Load…</kbd>
1. Navigate to and select/load `1px.abr` from your file system
1. Once brush has loaded, drag it to the top of the brush list:

 ![preset-manager](https://cloud.githubusercontent.com/assets/218624/9708414/4495ab0a-54d0-11e5-81af-0873456ccbc2.gif)

1. Click <kbd>Done</kbd>

### Drawing and erasing

1. Use the pencil tool <img src="https://cloud.githubusercontent.com/assets/218624/9708449/ceb272dc-54d0-11e5-9035-4dbeb3bacad5.png" align="absmiddle"> for drawing …
1. … and the eraser tool <img src="https://cloud.githubusercontent.com/assets/218624/9708487/58eccc72-54d1-11e5-9793-73d08116ceba.png" align="absmiddle"> for erasing; set its mode to pencil <img src="https://cloud.githubusercontent.com/assets/218624/9708528/1444e69e-54d2-11e5-8234-b27a876d45b1.png"  align="absmiddle">

For both the pencil and eraser tool, choose the 1 pixel brush from the <kbd>Brush</kbd> menu (or, with pencil tool enabled, <code>RMB</code> on the canvas and choose the 1 pixel brush from contextual menu).

### Selection and fill

Make sure all selection tools, and the fill tool, have anti-aliasing disabled and their tolerance is set to <code>0</code>:

![screenshot 2015-09-06 20 19 56](https://cloud.githubusercontent.com/assets/218624/9708711/ab821e94-54d4-11e5-8747-8f0788d3b1eb.png)

### New window view

Info coming soon.

Depending on the art, you can cheat by using the navigator window.

## Tile map template

Template showing “block”, “blob”, “path”, and “patch” tile map guides. Creation inspired by [Pixel art for Video games: Different types of techniques (Lecture 48)](https://www.udemy.com/pixel-art-for-video-games).

![Tiles](tiles.png)