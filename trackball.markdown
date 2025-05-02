---
layout: default
title: Trackball
has_children: false
parent: Wired
nav_order: 1
---
## Trackball Series Keyboard Details
## Notes:

* The USB cable to the computer should be connected on the right-hand side with the trackball.<br/>
* Version 1 uses a TRS audio cable: always unplug the USB cable before connecting or disconnecting the middle cable. Do NOT hot-plug under power, as this may damage the controller and disable half the keyboard.<br/>
* Version 2 uses a CTC data cable, supports hot-plugging, and resolves Version 1 issues. All PCBs have been upgraded to Version 2.<br/>
* PCB color is standardized to black. Custom PCB colors are not available.

## Overview
* The Trackball series are wired split keyboards. There are four layouts: 39, 44, 47, and 59. They are hot-swappable kits without switches or keycaps. See layout examples below.<br/>
* Main key area supports MX switches only. Thumb clusters support MX or Kailh Choc V1/V2 low-profile switches (V1: 1350, V2: 1353). Choose one at ordering; cannot mix or change later.<br/>
* 39, 44, and 47 layouts have full keysets without knobs.<br/>
* The 59 layout offers dual knobs by default but can be ordered in one of four configurations (choose at ordering; cannot change later):<br/>
  * 59: Dual knobs<br/>
  * 60: Left knob + right key<br/>
  * 60: Left key + right knob<br/>
  * 61: Full keys (both knobs replaced by keys)<br/>
* The knobs are EC11 encoders supporting rotation and press. Each action is programmable; they function like three independent keys. If unsure, choose the 61 full-key layout.<br/>
* Based on QMK firmware and compatible with Vial. Offers more settings than VIA or Remap and maximizes QMK features.<br/>
* Controller: RP2040 with RGB Matrix lighting. All keys support underglow RGB (no top LED).<br/>
* OLED screens: Left hand shows Luna the dog (modifier and layer status); right hand shows Bongo Cat (animations based on typing speed). Press the TIinfo key to view trackball parameters on the right OLED.<br/>
* Trackball modes: Mouse Mode (standard cursor), Sniper Mode (low DPI), Scroll Mode (emulates mouse wheel with horizontal and vertical scrolling).<br/>
* Supports Automatic Mouse Layer: scroll to switch to the mouse layer. Timeout and scroll threshold are adjustable.<br/>
* Dedicated TIinfo key toggles the display of detailed trackball settings on the right OLED.<br/>
* For more details, see the links below.

## [Trackball Keycodes and Usage Guide](./Trackball Guide)
## [Customize Keys with Vial](./vial)

## Layout Examples
The images below show layout examples. Case and trackball ball colors are confirmed at ordering.

### Trackball 39
![39](/static/trackball/39.jpeg){: width="100%" }<br/>
### Trackball 44
![44](/static/trackball/44.jpeg){: width="100%" }<br/>
### Trackball 47
![47](/static/trackball/47.jpeg){: width="100%" }<br/>
### Trackball 59
![59](/static/trackball/59.jpeg){: width="100%" }<br/>

