# Parity Generator

## Overview

This project implements a parity generator for a 4-bit data word using the Microwind tool. The parity generator enhances data integrity by adding a parity bit to the data, enabling error detection during data transmission. The project includes both even and odd parity generation, utilizing XOR and XNOR gates.

## Introduction

Parity is a method used in digital communication systems to detect errors. It involves adding a parity bit to ensure that the total number of ones in the data (including the parity bit) is either even (even parity) or odd (odd parity). This helps in detecting errors that may occur during data transmission, enhancing data integrity and reliability.

Example:
- Original data: 10110
- Parity bit (even): 0
- Encoded data: 101100

## Tools Used

- **Microwind**: A software tool for designing and simulating digital, analog, and mixed-signal circuits at the transistor level.

## Layout

Even Parity Generator:
<img src='./layout_evenparity' alt='even_parity'>

Schematic (Even):
<img src='./schematic_even' alt='even_schematic'>
