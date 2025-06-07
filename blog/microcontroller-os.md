---
layout: default
title: Building ASM OS from Scratch
permalink: /blog/microcontroller-os/
---

# Building ASM OS from Scratch

Most embedded OS projects are either bloated or too locked into RTOS ecosystems. So I built **ASM OS**, a custom MicroPython-powered operating system for low-end microcontrollers — no host PC needed.

## Goals

- ✅ Touch UI that feels like an early 2000s PDA
- ✅ Load separate Python apps without rebooting
- ✅ Run fully on RAM (RP2040 or similar)

## Features

- ASM Kernel written in clean MicroPython
- Window manager + launcher
- Works with ST7789 and XPT2046

## What I Learned

- MicroPython is perfect for fast prototyping
- Building your own OS makes you appreciate real-time logic
- RAM is *precious* — I had to optimize every byte

Because of this, it's taking a long time to finish. It'll be on GitHub soon.
