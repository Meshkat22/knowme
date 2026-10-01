---
layout: page
title: MINDGAN BCI Suite
description: A desktop application that ties the whole motor-imagery BCI workflow together — real-time EEG inference, training, and drone control.
importance: 1
category: bci
github: https://github.com/Meshkat22/MINDGAN_BCI_SUITE
date: 2026-05-01
---

**MINDGAN BCI Suite** is a desktop application I built to tie my motor-imagery BCI research together — one program for the whole loop instead of a folder of loose scripts. It is built around the Emotiv EPOC X headset.

- Real-time inference engine that reads EEG from LSL streams or the Emotiv Cortex API
- The MINDGAN training pipeline (cDCGAN curriculum) with automatic figure export
- DJI Tello drone control driven by motor-imagery classification
- Six modules covering recording, preprocessing, training, and online testing

The models inside are the same ones from my [MINDGAN paper](https://ieeexplore.ieee.org/document/11659043).

**Stack:** Python, PyTorch, Tkinter, LSL, Emotiv Cortex API

**Code:** [github.com/Meshkat22/MINDGAN_BCI_SUITE](https://github.com/Meshkat22/MINDGAN_BCI_SUITE)
