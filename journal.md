---
title: "Coderkeeb"
author: "Kashyap @kashsuks"
description: "A low profile mechanical keyboard meant for programmers based on the keycool 84"
created_at: "2025-06-03"
---

## June 3, 2025
Today I sketched the keyboard layout for my keyboard using [Keyboard Layout Editor](https://www.keyboard-layout-editor.com/#/). Here is the sketch of the rows and columns
I came up with using the Keycool 84 preset. I also decided to make an ortho layout just because... why not?

![Keyboard](https://hc-cdn.hel1.your-objectstorage.com/s/v3/d45e775a0e12d9c6da83300791aa8dc812f6fae9_image.png)

Through some research I found that I need specific low-profile switches and keycaps, and through some **more** research I found the specific footprints I needed. I decided on the Kailh Choc Siwtches since they're low profile and seem to be pretty cheap.

Here is the repo for the [footprints](https://github.com/daprice/keyswitches.pretty)

Through another hack-clubber, I was told that I could add a neopixel, and I might. For that, I want to be able to create a interface that allows me to set the lights for the neopixel so I can make cool designs!!

Tomorrow, I plan on creating the row column plan for the ortho layout, I did some rough planning and came to a conclusing that I will need 21 GPIO pins for the keeb and be left with 5 pins, of which 3 are going to be used for the EC11 rotary encoder, 1 for a battery led, and 1 for the neopixel

**Time Spent this session: 2 hours**

## June 4, 2025

Today I mostly worked on my schematic for the keyboard. I followed Joe Scottos video on how to make mechanical keyboard pcb's with KiCad. Here's whatI have so far

Schematic:

![Schematic](https://hc-cdn.hel1.your-objectstorage.com/s/v3/cef2b444d9ea50f6e015f6afa8b3e00eefd8b7ff_image.png)
