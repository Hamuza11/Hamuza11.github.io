---
layout: post
title: "ASM OS von Grund auf bauen"
lang: de
---

# ASM OS von Grund auf bauen

Die meisten Embedded-OS-Projekte sind entweder aufgebläht oder zu stark an RTOS-Ökosysteme gebunden. Also habe ich **ASM OS** gebaut, ein eigenes, MicroPython-basiertes Betriebssystem für Low-End-Mikrocontroller — ganz ohne Host-PC.

## Ziele

- ✅ Touch-UI, die sich wie ein PDA aus den 2000ern anfühlt
- ✅ Eigene Python-Apps laden ohne Reboot
- ✅ Läuft vollständig im RAM (RP2040 oder ähnlich)

## Features

- ASM-Kernel in sauberem MicroPython
- Window-Manager + Launcher
- Funktioniert mit ST7789 und XPT2046

## Was ich gelernt habe

- MicroPython ist perfekt für schnelles Prototyping
- Ein eigenes OS bauen lässt einen Echtzeit-Logik wirklich verstehen
- RAM ist knapp — ich musste jedes Byte optimieren

Deshalb dauert es, bis alles fertig ist. Bald auf GitHub.

