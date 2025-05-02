---
layout: default
title: Trackball Guide
permalink: /Trackball Guide/
has_children: false
nav_order: 4
---
## Please read through this guide carefully. All trackball functions are described here, so we recommend reading from top to bottom.

### Notes:
* Connect the USB cable to the computer on the right-hand side that has the trackball.<br/>
* Version 1 uses a TRS audio cable: always unplug the USB cable before connecting or disconnecting the middle link cable. Do NOT hot-plug under power, as this can damage the controller and disable half the keyboard.<br/>
* Version 2 uses a CTC data cable, which supports hot-plugging and resolves Version 1 issues. All PCBs have been upgraded to Version 2.<br/>

## The trackball keyboard has 17 customizable keycodes for trackball functions:
Keycodes:<br/>
![key_code](/static/trackball/key_code.jpeg){: width="100%" }<br/>

## 1. Mouse Mode
Standard cursor movement. Switch to other modes for additional operations.
* 16 adjustment steps, 200 DPI per step (cursor speed).<br/>
* Range cycles from 400 to 3,400 (400 → 600 → … → 3,400).<br/>
* DPI+: increase DPI in Mouse Mode.<br/>
* DPI-: decrease DPI in Mouse Mode.<br/>

## 2. Sniper Mode
Low‑DPI movement to avoid frequent DPI switching when precise control is needed.
* 4 adjustment steps, 100 DPI per step.<br/>
* Range cycles from 200 to 500 (200 → 300 → 400 → 500).<br/>
* Snp: hold to enter Sniper Mode; release to return to Mouse Mode.<br/>
* SnpT: tap to toggle Sniper Mode on/off.<br/>
* Snp+: increase Sniper Mode DPI (does not affect Mouse Mode DPI).<br/>
* Snp-: decrease Sniper Mode DPI (does not affect Mouse Mode DPI).<br/>

## 3. Scroll Mode
Emulates the mouse wheel (supports horizontal and vertical scrolling).
* 5 adjustment steps, 100 DPI per step.<br/>
* Range cycles from 100 to 500 (100 → 200 → … → 500).<br/>
* Drg: hold to enter Scroll Mode; release to return to Mouse Mode.<br/>
* DrgT: tap to toggle Scroll Mode on/off.<br/>
* Drg+: increase Scroll Mode DPI (no impact on other modes).<br/>
* Drg-: decrease Scroll Mode DPI (no impact on other modes).<br/>

## 4. Automatic Mouse Layer
Automatically switch to the mouse layer (Layer 5 in Vial) when scrolling the trackball.
* If you are new to Vial, we recommend keeping this feature off until you are familiar with basic functions.<br/>
* Toggle ATG key to enable/disable Automatic Mouse Layer.<br/>

### Parameter Settings
* Use the TIinfo key to view real-time parameter changes.<br/>
* A50: increase layer timeout by 50 ms per press; cycles between 0–3000 ms.<br/>
* A50-: decrease layer timeout by 50 ms per press; cycles backward between 0–3000 ms.<br/>
* A100: increase layer timeout by 100 ms per press; cycles between 0–3000 ms.<br/>
* ATV: adjust scroll trigger threshold (0–7); lower = more sensitive.<br/>
* T_SAVE: save Automatic Mouse Layer settings to controller EEPROM (only these settings, not full keymap).<br/>

## 5. OLED Display for Mouse Settings

### Default Screen:<br/>
![oled1](/static/trackball/oled1.jpeg){: width="100%" }<br/>
* Right OLED: Bongo Cat animation (typing speed).<br/>
* Left OLED: keyboard name, modifier status, current layer (shows "mouse" when Automatic Layer is triggered), and Luna dog animation.<br/>

### TIinfo Screen:<br/>
![oled](/static/trackball/oled.jpeg){: width="100%" }<br/>
* AutoL: 0/1 (Automatic Mouse Layer off/on).<br/>
* M-DPI: current Mouse Mode DPI.<br/>
* ATV: scroll trigger sensitivity threshold.<br/>
* AUTO-MS: automatic layer timeout value.<br/>
* SNP-T: 0/1 (Sniper Mode off/on).<br/>
* SNP-DPI: current Sniper Mode DPI.<br/>
* DRG-T: 0/1 (Scroll Mode off/on).<br/>
* DRG-DPI: current Scroll Mode DPI.<br/>

