---
layout: docs
title: Documentation
permalink: /docs/
lead_text: ''
---

# Getting Started

Install RobotJS using npm:

```sh
npm install robotjs
```
It's that easy! npm will download one of the prebuilt [binaries](https://github.com/octalmage/robotjs/releases/latest) for your OS.

You can get npm [here](https://nodejs.org/en/download/) if you don't have it installed.

If you need to build RobotJS, see the [building](/docs/building) section. Instructions for [Electron](/docs/electron).

# RobotJS 0.8

RobotJS 0.8 adds:

* [Image and color search](/docs/syntax#image), including exact or tolerance-based matching inside a screen capture or loaded image.
* Built-in BMP loading and saving plus [optional PNG support](/docs/building#optional-png-support).
* [Display enumeration and display-aware capture](/docs/syntax#getdisplays) for multi-monitor desktops and high-density screens.
* Improved keyboard handling, including automatic Shift and AltGr selection for [`typeString`](/docs/syntax#typestringstring) on Linux and complete modifier press/release lifecycles for shortcuts.

Start with the [image search example](/docs/examples#image-search) or browse the complete [API reference](/docs/syntax).
