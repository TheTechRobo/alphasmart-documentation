---
title: NEO2 Architecture
keywords: architecture neo2
summary: The architecture of the AlphaSmart NEO2
sidebar: neo2_sidebar
permalink: neo2_architecture.html
folder: neo2
---

The NEO2 has a 33MHz DragonBall VZ. That's a 68k processor.

There are 4MB of RAM, and some ROM which contains the base OS image.

{% include warning.html content="There is NO NON-VOLATILE STORAGE on board other than the ROM. Data is stored in RAM.
    As such, if both the AAs and the internal coin cell die, everything except the data in ROM is wiped." %}


The CPU is completely halted when awaiting a keypress, which allows the 700-hour battery life.