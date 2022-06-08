# ACCESS

## A Computer Controlled Electronic Spread Sheet

## For the Commodore 64 with Simons' BASIC

ACCESS is the premier spreadsheet software package for the Commodore 64 personal computer. Written in fast* Commodore BASIC with Simons' BASIC extension, you'll be blown away by the extensive features and powerful numeric calculation capabilities.

*when running with VICE Warp mode

## Background

I'd seen Lotus 1-2-3 at College and thought it was quite cool, so I thought I'd write something similar on my C64 for my UK Computer Studies A-level project.

I had a whole school year to complete the project, but 95% of the progarm was written over one crunch-mode weekend, ahead of the Monday morning hand-in deadline. I started working after school on Friday night and didn't stop until Monday morning.

There's nothing like a deadline to concentrate the mind. I remember the sun going down, coming back up again...go down...come up...etc. I got angry at one point and ripped the curtains off the curtain rail, which didn't help reflections on the telly I was using.

But most importantly, I passed the A-Level :-)

## ACCESS Key Features

- Formula calualation
- Absolute and Relative copying to multiple cells
- 72-column mode (12 columns x 6 chars) using a moving viewport
- Load and Save data files to disk (tested on 1541, examples included)
- Hardcopy to printer (tested on MPS801, example included)
- Ability to change background colour and display significant digits
- Online command help

## Getting Started

Start-up VICE C64 emulator and attach Simons' BASIC cartridge:

<img src="screenshots\0_Attach_SB_Cart.PNG" width="500px" height="auto">

Attach the ACCESS D64 disk image:

<img src="screenshots\1_Attach_ACCESS_Disk_Image.PNG" width="425px" height="auto">

Review the disk contents, load and run ACCESS:
(Files starting with a left arrow are ACCESS example spreadsheet files. Spelling & Maths is a bonus program!)

<img src="screenshots\2_LOAD_&_RUN_ACCESS.PNG" width="600px" height="auto">

Marvel at the exquisite Title Screen:

<img src="screenshots\3_Title_Screen.PNG" width="600px" height="auto">

Read the Instructions, for details, view the source code (`ACCESS_listing.bas`):

<img src="screenshots\4_Instructions.PNG" width="600px" height="auto">

Using `F1` to move the command highlight and `F7` to select it. Use `FILE` to open an example spreadsheet:

<img src="screenshots\5_Load_Example_File.PNG" width="600px" height="auto">

Move the selected cell highlight around and view the contents of the cells, the example below shows `ENTRY: @+D06*%15@24.075`, where 1st `@` signifies a formula, `D06` is a cell reference, `*%15` multiplies `D06` by `15/100` and the `@24.075` is the previously calculate value. View the source code to identify formulae are available.

<img src="screenshots\6_Formula_Example.PNG" width="600px" height="auto">

Dump your wonderful spreadsheet to a printer via VICE peripheral settings, default settings should work.

<img src="screenshots\7_Setup_Printer_for_HARD.PNG" width="600px" height="auto">

### Phillip Eaton 2022-06-09