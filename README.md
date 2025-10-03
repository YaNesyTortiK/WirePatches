# WirePatches

This repository holds patches for Resolume Wire.
Most of the patches in this repository are created by me from ground up or i was inspired by someone's project and tried to recreate it.

ALL OF PATCHES LISTED IN THIS REPOSITORY ARE FREE TO USE

## How to download
1. Click on file with patch you want to download (for example SystemTime.wired)
2. Navigate to top right corner of screen and click on download button
3. Find your downloaded file (probably in Downloads folder)
4. First way to import:
    1. Open Resolume Arena and drag-and-drop file in there.
    2. Click "Install" in popup window.
5. Second way to import:
    1. Navigate to folder: C:\Users\user\Documents\Resolume Wire\Patches
    2. Create new folder with name of patch
    3. Move your downloaded file there
6. Find installed patch in "Sources" (if you installed patch with type "Source") or "Effects"

## Table of content
- [SystemTime](#systemtime) | [DOWNLOAD](https://raw.githubusercontent.com/YaNesyTortiK/WirePatches/refs/heads/main/SystemTime.wired)
- [Timer](#timer) | [DOWNLOAD](https://raw.githubusercontent.com/YaNesyTortiK/WirePatches/refs/heads/main/Timer.wired)
- [StopWatch](#stopwatch) | [DOWNLOAD](https://raw.githubusercontent.com/YaNesyTortiK/WirePatches/refs/heads/main/StopWatch.wired)
- [Randomizer](#randomizer) | [DOWNLOAD](https://raw.githubusercontent.com/YaNesyTortiK/WirePatches/refs/heads/main/Randomizer.wired)
- [CreateScreensaver](#createscreensaver) | [DOWNLOAD](https://raw.githubusercontent.com/YaNesyTortiK/WirePatches/refs/heads/main/CreateScreensaver.wired)
- [Game Pong](#game-pong) | [DOWNLOAD](https://raw.githubusercontent.com/YaNesyTortiK/WirePatches/refs/heads/main/Pong.wired)

# Patches Preview

## SystemTime
This patch is providing a digital clock with hours, minutes, seconds and milliseconds with ability to disable any of these individually. Also you can change text color and scale text.

[>DOWNLOAD<](https://raw.githubusercontent.com/YaNesyTortiK/WirePatches/refs/heads/main/SystemTime.wired)

Patch info:
* Type: Source
* Resolution: 1920x1080 (1080p, Full HD)
* Texture Bit Depth: 8bpc
* Minimal Version: 7.21.0

Screenshots:

![Preference View from Arena](https://github.com/YaNesyTortiK/WirePatches/blob/main/img/SystemTime/Arena-Properties.png?raw=true)

![Preview-1](https://github.com/YaNesyTortiK/WirePatches/blob/main/img/SystemTime/Preview-1.png?raw=true)

![Preview-2](https://github.com/YaNesyTortiK/WirePatches/blob/main/img/SystemTime/Preview-2.png?raw=true)

![Preview-3](https://github.com/YaNesyTortiK/WirePatches/blob/main/img/SystemTime/Preview-3.png?raw=true)

## Timer
This patch is providing a digital timer with hours, minutes, seconds and milliseconds with ability to disable any of these individually. Also you can change text color and scale text. You also can change color for text when timer will stop on 0 seconds and change refresh rate. Timer can go below zero (minus sign can be toggled off).

[>DOWNLOAD<](https://raw.githubusercontent.com/YaNesyTortiK/WirePatches/refs/heads/main/Timer.wired)

Patch info:
* Type: Source
* Resolution: 1920x1080 (1080p, Full HD)
* Texture Bit Depth: 8bpc
* Minimal version: 7.21.0

Screenshots:

![Preference View from Arena](https://github.com/YaNesyTortiK/WirePatches/blob/main/img/Timer/Arena-Properties.png?raw=true)

![Preview-1](https://github.com/YaNesyTortiK/WirePatches/blob/main/img/Timer/Preview-1.png?raw=true)

![Preview-2](https://github.com/YaNesyTortiK/WirePatches/blob/main/img/Timer/Preview-2.png?raw=true)

![Preview-3](https://github.com/YaNesyTortiK/WirePatches/blob/main/img/Timer/Preview-3.png?raw=true)

## StopWatch
This patch is providing a digital stopwatch with hours, minutes, seconds and milliseconds with ability to disable any of these individually. Also you can change text color, scale text, change refresh rate.

[>DOWNLOAD<](https://raw.githubusercontent.com/YaNesyTortiK/WirePatches/refs/heads/main/StopWatch.wired)

Patch info:
* Type: Source
* Resolution: 1920x1080 (1080p, Full HD)
* Texture Bit Depth: 8bpc
* Minimal Version: 7.21.0

Screenshots:

![Preference View from Arena](https://github.com/YaNesyTortiK/WirePatches/blob/main/img/StopWatch/Arena-Properties.png?raw=true)

![Preview-1](https://github.com/YaNesyTortiK/WirePatches/blob/main/img/StopWatch/Preview-1.png?raw=true)

![Preview-2](https://github.com/YaNesyTortiK/WirePatches/blob/main/img/StopWatch/Preview-2.png?raw=true)

## Randomizer
Generates random numbers in range ["Min Number", "Max Number"]. If "Generating Time" is set more than 0, then every "Swapping Speed" hertz new random number will appear for "Generating Time" seconds and then stops at some random number. "Reset" will set value on screen to "Min Number".

[>DOWNLOAD<](https://raw.githubusercontent.com/YaNesyTortiK/WirePatches/refs/heads/main/Randomizer.wired)

Patch info:
* Type: Source
* Resolution: 1920x1080 (1080p, Full HD)
* Texture Bit Depth: 8bpc
* Minimal Version: 7.21.0

![Preference View from Arena](https://github.com/YaNesyTortiK/WirePatches/blob/main/img/Randomizer/Arena-Properties.png?raw=true)

![Preview-1](https://github.com/YaNesyTortiK/WirePatches/blob/main/img/Randomizer/Preview-1.png?raw=true)

![Preview-Gif](https://github.com/YaNesyTortiK/WirePatches/blob/main/img/Randomizer/Preview-Gif.gif?raw=true)

## CreateScreensaver
Effect that emulates legendary DVD logo bouncing on screen with any source.

Instruction:

0. Initial parameters:
    - Horizontal Speed = 0.1 hz
    - Vertical Speed = 0.1 hz
    - Center X = 960 pz
    - Center Y = 540 px
    - Width = 500
    - Height = 500
    - Animate = False
    - Crop Result = False
    - Show Borders = True
1. Change parameters Center X, Center Y, Width and Height in such way, that region which you want to bounce is located inside red rectangle.
2. if you want to crop other parts of input texture set parameter "Crop Result" to True.
3. To start animation set parameter "Animate" to True and set "Show Borders" to False to disable red rectangle.

[>DOWNLOAD<](https://raw.githubusercontent.com/YaNesyTortiK/WirePatches/refs/heads/main/CreateScreensaver.wired)

Patch info:
* Type: Effect
* Resolution: 1920x1080 (1080p, Full HD)
* Texture Bit Depth: 8bpc
* Minimal Version: 7.21.0

Screenshots:

![Preference View from Arena](https://github.com/YaNesyTortiK/WirePatches/blob/main/img/CreateScreensaver/Arena-Properties.png?raw=true)

![Preview-Gif](https://github.com/YaNesyTortiK/WirePatches/blob/main/img/CreateScreensaver/Preview-Gif.gif?raw=true)

## [GAME] Pong
Game Pong (re)created with wire just for fun.

Instruction:

0. Initial parameters:
    - Pause - True
    - Player1 - 0.5
    - Player2 - 0.5
    - Center Y = 540 px
    - Ball speed - 30
1. Press Reset Game trigger (or else score will not count first ball).
2. To start game - set Pause to false and ball will start moving.
3. To control players change value in fields Player1 and Player2 (0 - bottom of the screen, 1 - top of the screen).
4. When ball passes one of the players and touches left or right edge of the screen, point is added to opposite player and ball spawns in center and starts moving immediately.
5. To reset score press Reset Game trigger. Both scores will be set to 0 and ball will spawn in center.

[>DOWNLOAD<](https://raw.githubusercontent.com/YaNesyTortiK/WirePatches/refs/heads/main/Pong.wired)

Patch info:
* Type: Source
* Resolution: 1920x1080 (1080p, Full HD)
* Texture Bit Depth: 8bpc
* Minimal Version: 7.23.0

Screenshots:

![Preference View from Arena](https://github.com/YaNesyTortiK/WirePatches/blob/main/img/Pong/Arena-Properties.png?raw=true)

![Preview-Gif](https://github.com/YaNesyTortiK/WirePatches/blob/main/img/Pong/Preview-Gif.gif?raw=true)

# Contact info
Email: [ya.nesy.tortik.email@gmail.com](mailto:ya.nesy.tortik.email@gmail.com)