---
layout: post
title:  "First release"
date:   2024-06-21 21:30:00 +0000
categories: releases
---

I'm glad to announce that first version of Big Number Calculator (Calcum) is 
available for public

#### Download

Here you can find an installer for windows: [link](https://github.com/mahairod/calcum/releases/tag/v0.6.4-alfa)

#### Available features
- Simple spreadsheet-like view of a single document:
  - Expandable 2-dimensional table of cells
- Each cell can contain integral number, text or formula, hexademical number format is supported
- Very big numbers are supported, with mantissa up to ~ 19 decimal digits
- Formulas support basic arithmetic operations: + - * / %. There is also support for bit shifts: << and >>
- Text concatenates with +
- Formulas can use custom fuctions which can be defined separately as a simple text
  - Predefined functions are available (mostly for string/character and list processing)
- Basic cells editing, row and columns insetion preserving correct order
- Copy/cut/paste operations of cell regions inside application
  - Data export to antoher applications through clipboard as [CSV](https://en.wikipedia.org/wiki/Comma-separated_values#Example) values
- Auto filling on region expansion
  - Convenient filling with Ctrl button pressed
  - Support for non-contigous multiple regions (with some restrictions)
- Whole table recalculation on cell value change
- Opening of file in [CSV](https://en.wikipedia.org/wiki/Comma-separated_values) format is supported
- Saving files in [CSV](https://en.wikipedia.org/wiki/Comma-separated_values) format

#### Summmary

Hope this app would be usefull for you. Enjoy.

