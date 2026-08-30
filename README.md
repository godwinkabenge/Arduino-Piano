# Arduino-Piano


## Overview

This project uses an Arduino, push buttons, and resistors to create a small musical keyboard. Each button produces a different musical note through a piezo.

## Objective

* Use a resistor ladder to read multiple buttons through a single analog input
* Assign different musical notes to each button
* Use arrays to store and access note frequencies
* Generate sounds using the `tone()` function

## Components used

* Arduino board
* Push buttons
* Piezo
* 220 Ω resistor
* 10 kΩ resistors
* 1 MΩ resistor
* Connecting wires

## How It Works

1. Each button produces a different voltage through the resistor ladder.
2. The Arduino reads the resulting voltage through analog pin A0.
3. The analog reading is matched to a specific button.
4. An array stores the frequency of each musical note.
5. The `tone()` function plays the corresponding note through the piezo.

## What I Learned

* Building and using resistor ladders
* Reading multiple inputs through a single analog pin
* Using arrays to organize related values
* Generating different musical notes using `tone()`

## Demonstration

A video showing the Arduino keyboard playing different notes can be seen here.

[Watch the project demonstration](./Arduino_piano.mp4)

