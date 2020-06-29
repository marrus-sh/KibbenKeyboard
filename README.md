# Kibben Keyboard for macOS

This repository contains a handwritten macOS Keyboard Bundle for the input of English text using the [Kibben Orthography](https://go.KIBI.family/Documents/kibben.xhtml).

## Installation

01. Clone this repository, or download it as a ZIP and unzip its contents.

02. In Finder, click `Go > Go to Folder…` and type `~/Library`, then press Return to navigate to your user library folder.

03. Create the `Keyboard Layouts` directory if it doesn't already exist in this location.

04. Drag `Kibben.bundle` (from this repository) into the `Keyboard Layouts` folder.

05. Restart your computer.

## Usage

Open System Preferences, click on Keyboard, and then Input Sources.
Use the + button to add a new input source.
The Kibben keyboard will be available (as “Kybn”) under the English category.

## Notes

+ Caps Lock switches the keyboard into Runic input.
Additional runic characters are located at the beginning and end of the number row.

+ The keyboard is the same as a typical US keyboard layout when Caps Lock is active and the Option key is held down.

+ The four dead keys are located at Shift+`5` (for diæresis), Shift+`6` (for dot), Alt+`‘` (for grave), and Alt+`’` (for acute).
To output a standalone (spacing) diacritics, type the corresponding dead key and press space.

+ Option+Space produces a nonbreaking thin space, for use when padding punctuation.
Shift+Option+Space produces an ordinary nonbreaking space.
So, be sure to release Option if your intent is to type a breaking interword space.

## Changelog

+ **2.2:**
Fixes tilde behaviour.
Adds missing Open E characters with a slight rearrangement of the keyboard.
Removes automatic insertion of narrow spaces around punctuation.
Replaces raised omission brackets with dead keys for grave and acute accents.

+ **2.1:**
Provides remaining ASCII characters in the non‐capslocked keyboard and moves around some characters for easier access.

+ **2.0:**
Rename to “Kibben”/“Kybn”.
Basically an entirely new keyboard layout, with full support for the Kibben character set, including runes.
The vast majority of diacritic support has been dropped, as have most alternate or historical glyphs.
The former can typically be accessed through the macOS press‐and‐hold system, and the latter are unlikely to see enough use to justify a position in the keyboard.

+ **1.1:**
Bugfix for capital KRA.

+ **1.0:**
Initial release.
