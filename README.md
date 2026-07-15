# MacroPad — 9-Key Stream Deck-Style Macro Pad

> A custom **9-key macro pad** powered by an **RP2350 (Pico 2)**, with a **4″ 320×480 SPI TFT (ST7796)** beneath **custom transparent-window keys** featuring **soft-touch switches** on each key.


![Project Status](https://img.shields.io/badge/status-in%20development-yellow)

## Overview

This is a personal skill-building project to design and build a fully custom macro pad from scratch. This includes hardware, firmware, enclosure, and desktop configuration app.

### Key Features

*   **9 programmable keys** with 3×3 grid layout
    
*   **4″ 320×480 SPI TFT** (ST7796) driven by a custom DMA-accelerated driver
    
*   **Custom transparent-window key caps** with soft-touch switches (4 per key)
    
*   **USB HID**: enumerates as keyboard + consumer control, no drivers needed
    
*   **On-device LCD icons** with press-feedback animations
    
*   **Multiple profiles & layers** switchable from the device
    
*   **Cross-platform desktop configuration app** (key mapping, icon library, profile management)
    
*   **Custom PCB** (KiCad) and **3D-printed enclosure**

## Hardware

| Component | Detail |
| --- | --- |
| **MCU** | RP2350 (Raspberry Pi Pico 2) |
| **Display** | 4″ 320×480 SPI TFT (ST7796 driver) |
| **Keys** | 9 keys, each with 4 soft-touch switches |
| **Connectivity** | USB-C (HID + CDC serial debug) |
| **PCB** | Custom 4-layer design in KiCad |
| **Enclosure** | 3D-printed with ~5° tilt, rubber feet |